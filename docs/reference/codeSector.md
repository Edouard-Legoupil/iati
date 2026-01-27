# codeSector

DAC 5 Digit Sector External URL:
http://www.oecd.org/dac/stats/dacandcrscodelists.htm

## Usage

``` r
codeSector
```

## Format

A data frame with 323 rows and 6 variables:

- `code`:

  double code

- `name`:

  character name

- `description`:

  character description

- `category`:

  double category

- `url`:

  character url

- `status`:

  character status

## Source

<https://iatistandard.org/en/iati-standard/203/codelists/>

## Examples

``` r
{
knitr::kable(head(codeSector, 10))
}
#> 
#> 
#> |  code|name                                           |description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | category|url |status |
#> |-----:|:----------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------:|:---|:------|
#> | 11110|Education policy and administrative management |Education sector policy, planning and programmes; aid to education ministries, administration and management systems; institution capacity building and advice; school management and governance; curriculum and materials development; unspecified education activities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |      111|NA  |active |
#> | 11120|Education facilities and training              |Educational buildings, equipment, materials; subsidiary services to education (boarding facilities, staff housing); language training; colloquia, seminars, lectures, etc.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |      111|NA  |active |
#> | 11130|Teacher training                               |Teacher education (where the level of education is unspecified); in-service and pre-service training; materials development.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |      111|NA  |active |
#> | 11182|Educational research                           |Research and studies on education effectiveness, relevance and quality; systematic evaluation and monitoring.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      111|NA  |active |
#> | 11220|Primary education                              |Formal and non-formal primary education for children; all elementary and first cycle systematic instruction; provision of learning materials.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |      112|NA  |active |
#> | 11230|Basic life skills for youth and adults         |Formal and non-formal education for basic life skills for young people and adults (adults education); literacy and numeracy training. Excludes health education (12261) and activities related to prevention of noncommunicable diseases. (123xx).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |      112|NA  |active |
#> | 11231|Basic life skills for youth                    |Formal and non-formal education for basic life skills for young people.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |      112|NA  |active |
#> | 11232|Primary education equivalent for adults        |Formal primary education for adults.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |      112|NA  |active |
#> | 11240|Early childhood education                      |Formal and non-formal pre-school education.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |      112|NA  |active |
#> | 11250|School feeding                                 |Provision of meals or snacks at school; other uses of food for the achievement of educational outcomes including “take-home” food rations provided as economic incentives to families (or foster families, or other child care institutions) in return for a child’s regular attendance at school; food provided to adults or youth who attend literacy or vocational training programmes; food for pre-school activities with an educational component. These activities may help reduce children’s hunger during the school day if provision of food/meals contains bioavailable nutrients to address specific nutrition needs and have nutrition expected outcomes in school children, or if the rationale mainstream nutrition or expected outcome is nutrition-linked. |      112|NA  |active |
```
