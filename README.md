---
title: README
subtitle: Homemade Foaming Handsoap Recipe
author: John D. Fisher
email: jdfenw@gmail.com
version: 1.3
---

<!--
# Convert markdown to html using pandoc
pandoc  --from="markdown+grid_tables" --to="html" --output="README.html" \
  --standalone --template="pandoc.html5" --toc --highlight-style="breezedark" \
  --css="pandoc.css" "README.md"
-->

## Homemade Foaming Hand Soap Recipe

We're fond of
[Thieves Foaming Hand Soap](https://www.youngliving.com/en_US/products/thieves-foaming-hand-soap)
from Young Living but wanted to reduce our cost and environmental impact--i.e.,
stop shipping bottles of mostly water and buy ingredients in large enough
quantity to meet our needs for several months. After searching
[Google](https://www.google.com/search?q=diy+foaming+hand+soap&oq=DIY+foaming&aqs=chrome.1.69i57j0l5.6062j0j7&sourceid=chrome&ie=UTF-8),
I found three recipes; see [References](#references).

The recipes either call for vegetable glycerin or oil to make the soap
moisturizing and to lubricate the soap dispenser's moving parts. Glycerin may
also work as a preservative for essential oils added for fragrance. With oils
alone, the soap is smooth; glycerin alone generates more friction. Friction may
be a property of the castile soap, reduced by the amount of oil added. Using
both glycerin and oil, generates a smooth feeling soap which is also
shelf-stable--i.e., the oil and essential oils are less likely to break down
over the course of a month at room temperature.

The original recipe assumed a 12 ounce bottle and equal amounts of glycerin
and oil (almond and fractionated coconut oil
,summer[^fractionated_coconut_oil], both work nicely). The raw amounts are
converted to milliliters and scaled for a 7 ounce (207 ml) bottle. Milliliters
are convenient because, for liquids similar to water, grams and milliliters
are the close to the same. I have a gram scale but do not have measuring
spoons for
the odd fractions of a teaspoon the recipe calls for. Measuring by weight is
easier anyway.

After regular use, we discovered the soap tends to dry our hands. Increasing
the amount of oil from 3 to 6 g, solved the problem. So the revised recipe
increases the amount of oil and reduces the water by the same amount to
maintain the total at 12 oz and hit the target mass of 6 g in the 7 oz bottle.

[^fractionated_coconut_oil]:

  Fractionated coconut oil may solidify at cooler temperatures: Under our
  kitchen sink (exterior wall), the bottle solidified well above the freezing
  temperature. We've relocated it to the bathroom vanity to see if it melts.
  It's probably best to use almond oil in the winter.

### Ingredients

<!-- markdownlint-disable MD013 -->

| Ingredients              |  Raw Amt | Raw Units |  Amount | Scaled Vol | Density | Scaled Mass |
| ------------------------ | -------: | --------: | ------: | ---------: | ------: | ----------: |
| Water                    |     10.5 |        oz |     309 |        181 |    1.00 |         181 |
| Soap                     |      2.0 |       tbs |      30 |         17 |    1.01 |          17 |
| Fractionated Coconut Oil |      2.2 |       tsp |      11 |          6 |    0.96 |           6 |
| Glycerin                 |      1.0 |       tsp |       5 |          3 |    1.25 |           4 |
| **Total**                | **12.0** |    **oz** | **355** |    **207** |         |     **208** |
| _Units_                  |          |           |    _ml_ |       _ml_ |  _g/ml_ |         _g_ |

Table: Hand Soap Ingredients Scaled for 7 ounces (207 ml)

<!-- markdownlint-enable MD013 -->

Thirty (30) drops of essential oil, per 7 ounces of soap, works nicely for
strong fragrances, like
[Thieves Essential Oil Blend](https://www.youngliving.com/en_US/products/thieves-essential-oil-blend)
from Young Living.

### Steps

1. Measure water, oil and glycerin.
2. Add to foaming hand soap bottle and shake to blend.
3. Measure and add soap to foaming hand soap bottle.
4. Add 30 drops of essential oil to foaming hand soap bottle.
5. Put the pump/cap on the bottle and gently rotate to mix soap without
   generating suds.

### Adjusting Recipe Amounts

The [Ingredients for 7 ounces of hand soap](#ingredients) derive from an
[Excel spreadsheet](Soap_blend.xlsx).

- To change the bottle size, enter the desired bottle-size in cell `I2`.
- If the desired bottle size is in milliliters, change the units in cell `J2`
  to `ml`.
- Other units may be used, but cells, `D7:E7` and `L2` must use the same SI
  units of volume. Use Excel `CONVERT()` function unit abbreviations, such as
  `l` for liters.
- The ingredients list provides a drop-down menu for changing oil and glycerin.
  Excel table `Ingredients[Name]` provides the list of possible ingredients. To
  add others, fill in the information below the last row of Excel table
  `Ingredients[Name]`.

## References

1. [Homemade Moisturizing Foaming Hand Soap](https://wholenewmom.com/whole-new-budget/homemade-foaming-soap/)
2. [How To Make Foaming Hand Soap](https://www.onegoodthingbyjillee.com/foaming-hand-soap/)
3. [DIY Foaming Hand Soap](https://wellnessmama.com/8631/foaming-hand-soap/)
