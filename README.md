# Vegetable-Prices

Sourced from [Eenadu newspaper](http://epaper.eenadu.net/)

## Process

Everyday, values are manually entered from the district edition.

Data available from 1st Dec 2018 until 20th March 2019

## Names

| Name | Other names |
| ---- | ------------------ |
| bhendi | Okra |
| kakarakaya | Bitter gourd, Karela |
| beerakaya | Ridge gourd, |
| dondakaya | Ivy gourd, Tindora |
| chikkudukaya | Broad beans |
| gokarakaya | Cluster beans |
| keera | Cucumber |
| dosakaya | Yellow cucumber |
| sorakaya | Bottle gourd |
| potlakaya | Snake gourd |
| chamagadda | Yam |
| kanda | Yam, Elephant foot yam |

## Overview

### Distribution of prices

Instances where vegetable prices aren't available (sporadic reporting) are replaced with zeros.

![prices](prices.png)

### Trend of vegetable prices

Gaps in trend are due to unreported instances.

![trend](trend.png)

### Correlation of prices

Pairwise (vegetable pairs) correlation (Pearson's) is determined and visualized. While values towards `1` are positively correlated, values towards `-1` are negatively correlated.

![correlation](correlation.png)

## TODO

- Scrape from Eenadu online newspaper
- Extend for other districts and zones
