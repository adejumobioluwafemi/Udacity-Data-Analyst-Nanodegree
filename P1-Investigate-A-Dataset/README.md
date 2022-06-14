
## P1: Investigate A Dataset (Gapminder World Dataset)

### Prerequisites

Additional installations: 

* [Missingno](https://github.com/ResidentMario/missingno)
* [pycountry](https://bitbucket.org/flyingcircus/pycountry)
* [pycountry-convert](https://pycountry-convert.readthedocs.io/en/latest/)

## Project Overview

### Data Sources

**Name: Population total**

- Definition: Total population
- Source: http://gapm.io/dpop
- Version: 6

**Name: Life expectancy (years)**

- Definition: The average number of years a newborn child would live if current mortality patterns were to stay the same.
- Source: http://gapm.io/ilex
- Version: 12

**Name: Income per person (GPD/Capita, PPP$ inflation-adjusted)**

- Definition: Gross domestic product per person adjusted for differences in purchasing power (in international dollars, fixed 2011 prices, PPP based on 2011 ICP).
- Source: http://gapm.io/dgdppc
- Version: 27

### Wrangling

For the analysis, following countries were dropped out of the dataframe due to too much missing data:

- Andorra, Dominica, Holy See, Liechtenstein, Marshall Islands, Monaco, Nauru, Palau, San Marino, St. Kitts and Nevis, Tuvalu


### Summary

- We can see an overall and continuing upward trend in the world population, per capita income, and life expectancy.   
- Between 1950 and 1975, in particular, there was a considerable growth in all three metrics.     
- The global population is rapidly growing, with one apparent reason being an increase in general life expectancy.
- We also discovered that there is a clear association between per capita income and life expectancy. Although an increase in income does not ensure an increase in life expectancy, it is likely to happen to some extent.

### Authors

* Oluwfemi Adejumobi
* Udacity

## License

* <a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/"> Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>

<a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/">
	<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" />
</a>
