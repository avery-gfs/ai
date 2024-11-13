## Cause and Effect

https://en.wikipedia.org/wiki/Correlation_does_not_imply_causation

_Correlation does not imply causation._

**Correct cause and effect**

> People are more likely to carry umbrellas on rainy days. _Therefore, rainy
> days cause people to carry umbrellas._

**Reverse Causality**

> People are more likely to carry umbrellas on rainy days. _Therefore, carrying
> umbrellas causes rain._

**Common Cause**

> People are more likely to carry umbrellas on days when they wear rain jackets.
> _Therefore, rain jackets cause people to carry umbrellas._

A historical example of this is that Europeans in the Middle Ages believed that
lice were beneficial to health since there would rarely be any lice on sick
people. The reasoning was that the people got sick because the lice left. The
real reason however is that lice are extremely sensitive to body temperature. A
small increase of body temperature, such as in a fever, makes the lice look for
another host. The medical thermometer had not yet been invented and so that
increase in temperature was rarely noticed. Noticeable symptoms came later,
which gave the impression that the lice had left before the person became sick.

![](https://www.tylervigen.com/spurious/correlation/image/1519_popularity-of-the-first-name-aria_correlates-with_hydopower-energy-generated-in-equatorial-guinea.png)
![](https://www.tylervigen.com/spurious/correlation/image/1254_masters-degrees-awarded-in-education_correlates-with_gmo-use-in-corn-grown-in-ohio.png)
![](https://www.tylervigen.com/spurious/correlation/image/7036_popularity-of-the-distracted-boyfriend-meme_correlates-with_the-number-of-statisticians-in-new-jersey.png)
![](https://www.tylervigen.com/spurious/correlation/image/1036_milk-consumption_correlates-with_burglary-rates.png)

## Base Rate Neglect

https://en.wikipedia.org/wiki/Base_rate_fallacy

> A type of fallacy in which people tend to ignore the base rate (e.g., general
> prevalence) in favor of the individuating information (i.e., information
> pertaining only to a specific case).

**Example: Breathalyzer Accuracy**

Imagine you stop a random driver on the road and have them take a breathalyzer
test. The test comes back positive. How much information does this result give
you that the driver is in fact drunk?

In this scenario, let's say:

- Breathalyzers are have a `5%` false positive rate (`5` in `100` sober drivers
  will test positive; `95` in `100` sober drivers will test positive).
- At any given time, `0.1%` of drivers on the road are drunk.

Do the math out for `100000` drivers:

|                       | Sober                      | Drunk                     | Total    |
| --------------------- | -------------------------- | ------------------------- | -------- |
| Count                 | `100000 * 0.999 = 99900`   | `100000 * 0.001 = 100`    | `100000` |
| Positive              | `99900 * 0.05 = 4950`      | `100 * 1.00 = 100`        | `5050`   |
| Positive of Positives | `4950 / 5050 = `**`0.98`** | `100 / 5050 = `**`0.02`** |          |
