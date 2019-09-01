---
title: README
subtitle: Homemade Foaming Handsoap Recipe
author: John D. Fisher
email: jdfenw@gmail.com
version: 1.0
---

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

The following recipe assumes a 12 ounce bottle and equal amounts of glycerin and
oil (almond and fractionated coconut oil both work nicely). The raw amounts are
converted to milliliters and scaled for a 7 ounce (207 ml) bottle. Milliliters
are convenient because, for liquids similar to water, grams and milliliters are
the same. I have a gram scale but do not having measuring spoons for the odd
fractions of a teaspoon the recipe calls for. Measuring by weight is easier
anyway.

### Ingredients

| Ingredients              |  Raw Amt | Raw Units |  Amount | Scaled Vol |
|--------------------------|---------:|----------:|--------:|-----------:|
| Water                    |     10.7 |        oz |     315 |        184 |
| Soap                     |        2 |       tbs |      30 |         17 |
| Fractionated Coconut Oil |        1 |       tsp |       5 |          3 |
| Glycerin                 |        1 |       tsp |       5 |          3 |
| **Total**                | **12.0** |    **oz** | **355** |    **207** |
| *Units*                  |          |           |    *ml* |       *ml* |

Table: Hand Soap Ingredients Scaled for 7 ounces (207 ml)

Thirty (30) drops of essential oil, per 7 ounces of soap, works nicely for
strong fragrances, like
[Thieves Essential Oil Blend](https://www.youngliving.com/en_US/products/thieves-essential-oil-blend)
from Young Living.

### Steps

1. Measure water, oil and glycerin.
2. Add to foaming hand soap bottle and shake to blend.
3. Measure and add soap to foaming hand soap bottle.
4. Add 30 drops of essential oil foaming hand soap bottle.
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
