# Generate Plot Description with AI (Phase 3)

This function serves as the "Semantic Generator," combining structure
and statistics to prompt an LLM for a structured description.

## Usage

``` r
generate_description(
  structure,
  stats,
  provider = NULL,
  model = NULL,
  max_tokens_short_desc = 30,
  max_tokens_long_desc = 500
)
```

## Arguments

- structure:

  Metadata list returned by \`extract_structure\`.

- stats:

  Statistical profile returned by \`profile_data\`.

- provider:

  The LLM provider (e.g., "openai", "azure", "anthropic").

- model:

  The specific model to use.

- max_tokens_short_desc:

  Maximum token limit for the short desc - typically to be used for a
  chart subtitle

- max_tokens_long_desc:

  Maximum token limit for the short desc - typically to be used for a
  long narrative illustration

## Value

A list containing:

- short_desc:

  A concise, WCAG-compliant alt text string.

- long_desc:

  A detailed analytical description of the visualization.

## Examples

``` r
library(ggplot2)
p <- ggplot(mtcars, aes(x = wt, y = mpg)) +
  geom_point() +
  unhcrthemes::theme_unhcr(grid = "Y", axis = "X", axis_title = FALSE) +
  labs(
    title = "Vehicle Efficiency",
    subtitle = "Fuel consumption vs weight",
    caption = "Source: mtcars dataset"
  ) 
story <- generate_description(structure= extract_structure(p),
                      stats = profile_data(p),
                      provider = "azure",
                      model = "gpt-4.1-mini",
                      max_tokens_short_desc = 30,
                      max_tokens_long_desc= 500 ) 
```
