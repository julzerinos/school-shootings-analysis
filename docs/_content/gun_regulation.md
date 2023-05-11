# Let's talk about guns

An important question, when discussing shootings, is about the source of the guns which fuel this violence. 

The below analysis is done with the additional use of the [State-Level Estimates of Household Firearm Ownership](https://www.rand.org/pubs/tools/TL354.html) database.

## Gun ownership correlation

A simple conclusion is that states with more gun-owning households is more prone to gun violence in the form of school shootings. The choropleth below displays gun ownership vs casualties from shootings to follow this train of thought.

{% include us_gun_ownership.html %}

What comes as quite a surprise is that the states with the highest percentage of households with guns have some of (if not the most) lowest consequences of shootings. For example, Montana, Wyoming and Idaho - three states with an ownership ratio above `60%` (and up to `66%`) - not only do not have any casualties from shootings - these states have had no recorded shootings in this data set!

Stating that there is no correlation between ownership and shootings is also another simple conclusion. Ownership ratios do not reflect the true number of firearms in the state as well as the proportion of guns to people.

From a previous section, California was established as the state with the highest number of shootings. California has a population of `21.5 million` ([2021 census](https://www.census.gov/quickfacts/fact/table/CA/PST045221)), whereas Wyoming has a population of `0.58 million` ([2021 census](https://www.census.gov/quickfacts/fact/table/WY/PST045221)). This is an enormous difference which is easy to overlook and indicates that interpretations should be considered carefully. 

California has `13.2 million` households and with firearm ownership rates of `28.32%`, that tallies to around `3.7 million` households with firearms. In Wyoming, `0.18 million` out of `0.27 million` households have firearms (`66.22%`). It is true that a household in Wyoming is more than twice as likely to own or have access to firearms, but there are `20` times more such households in California.

The above doesn't take into consideration unregistered firearms, illegally purchased weapons or "ghost guns" (lacking serial numbers).

## Firearm source

In the data set there are `105` records of source of the weapon used by the shooter. While there are many singular, specific descriptions such as "constructed from parts purchased by the shooter" or "ghost gun", most can be categorized as obtained (via theft, gift or lending) from a relative at `49` instances. The majority of those were obtainment from the perpetrators father at `16` instances. In either case, these count as household sources, implying that there is a pattern in shooters using firearms they have access to in their homes.
