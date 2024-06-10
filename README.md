# Python-hypothesis-testing-men-and-women-football-matchproject-

![A soccer pitch for an international match.](soccer-pitch.jpg)

We're working as a sports journalist at a major online sports media company, specializing in soccer analysis and reporting. We've been watching both men's and women's international soccer matches for a number of years, and our gut instinct tells you that more goals are scored in women's international football matches than men's. This would make an interesting investigative article that our subscribers are bound to love, but we'll need to perform a valid statistical hypothesis test to be sure!

While scoping this project, our acknowledge that the sport has changed a lot over the years, and performances likely vary a lot depending on the tournament, so we decide to limit the data used in the analysis to only official `FIFA World Cup` matches (not including qualifiers) since `2002-01-01`.

We create two datasets containing the results of every official men's and women's international football match since the 19th century, which we scraped from a reliable online source. This data is stored in two CSV files: `women_results.csv` and `men_results.csv`.

The question we'are trying to determine the answer to is:

> Are more goals scored in women's international soccer matches than men's?

We assume a **10% significance level**, and use the following null and alternative hypotheses:

$H_0$ : The mean number of goals scored in women's international soccer matches is the same as men's.

$H_A$ : The mean number of goals scored in women's international soccer matches is greater than men's.
