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
print(story$long_desc)
#> [1] "In the quest to optimize humanitarian logistics, vehicle efficiency emerges as a critical strategic priority. Our analysis of 32 vehicle data points reveals a strong inverse relationship between vehicle weight and fuel consumption, with average weights around 3.22 tons and fuel efficiency averaging 20.1 miles per gallon. Heavier vehicles demonstrate up to a 20% decrease in fuel efficiency, directly translating to higher operational costs and larger carbon footprints. This situation challenges our resource mobilization, as fuel expenditures consume a significant portion of emergency response budgets. Given the direct link between vehicle weight and fuel consumption, targeting investments to upgrade or substitute heavy vehicle fleets with lighter, more fuel-efficient models presents a powerful impact multiplier. This shift could reduce fuel consumption by an estimated 20%, significantly lowering costs and enhancing operational sustainability. Moreover, integrating vehicle efficiency metrics into partnership frameworks unlocks opportunities to collaborate with innovative transport technology providers, aligning donor interests with impactful environmental accountability goals. We recommend prioritizing funding toward scalable fleet modernization programs as a strategic lever to amplify cost efficiencies and sustainability outcomes. Immediate action to leverage these findings will not only maximize return on investment but also position our operations as global exemplars of green humanitarian logistics, thus attracting large-scale donor commitments dedicated to innovation and resilience-building in challenging contexts."
```
