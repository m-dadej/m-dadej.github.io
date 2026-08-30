---
title: "Data visualization"
description: "Data visualisations built in R and ggplot2 — Polish and Central and Eastern European macroeconomic, financial market, election and public health charts."
permalink: /data_viz/
author_profile: true
---

A selection of charts I have made in R, mostly with ggplot2. They cover Polish and
Central and Eastern European macroeconomics, financial markets, elections and public health.

If you would like the code behind any of these, feel free to [get in touch](mailto:mateuszdadej@gmail.com) —
I don't usually keep these scripts on my [GitHub](https://github.com/m-dadej).

## Financial markets and investing

![Line chart showing the distribution of annualised returns on the S&P 500 total return index by holding period, from minimum to maximum percentile, using data since 1930. Returns converge as the horizon lengthens, and after roughly 20 and a half years the historical return was always positive.](/images/data_viz/hold_time_rets.svg){: loading="lazy" width="792" height="504"}

*Distribution of returns from investing in the S&P 500 for different holding periods. Twenty and a half years is the horizon after which the historical rate of return was always positive. Data: stooq.pl, Nasdaq.*

![Scatter plots faceted by sector showing one-year stock returns against the price-to-earnings ratio at the end of the previous year, for 171 Warsaw Stock Exchange companies split evenly across sectors, panel data since 2009.](/images/data_viz/facet_pe.svg){: loading="lazy" width="720" height="504"}

*How well the price/earnings ratio predicts returns, by sector, on the Warsaw Stock Exchange. Based on 171 randomly selected companies, panel data since 2009. Data: infostrefa.com and stooq.pl.*

![Animated bar chart race showing the changing composition of the largest companies in Poland's WIG stock index over time.](/images/data_viz/wig_race.gif){: loading="lazy" width="620" height="480"}

*A bar chart race of the largest constituents of the WIG index on the Warsaw Stock Exchange.*

<!--
  The IPO debuts chart (debiuty_gpw.svg) is temporarily removed.
  The source SVG is 62 MB because ggplot writes every data point as its own <path>
  node, which made this page roughly 78 MB to load.
  To restore it, re-export from R as a raster and drop the PNG in images/data_viz/:
      ggsave("debiuty_gpw.png", width = 8, height = 5, dpi = 150)
  Expect roughly 150 KB. Then re-add the image below with alt text.
  The original SVG is still in the repo at images/data_viz/debiuty_gpw.svg.
-->

## Polish macroeconomy and society

![Animated chart of the Polish WIBOR interbank interest rate curve shifting over time.](/images/data_viz/wibor_curve15_eng.gif){: loading="lazy" width="550" height="430"}

*The WIBOR interest rate curve in Poland, animated over time.*

![Nine small maps of Poland by county, shaded by average apartment area in square metres, one map per construction period from before 1918 through 2017 to 2021. Apartments become consistently larger in the more recent periods.](/images/data_viz/avg_space_plot1.png){: loading="lazy" width="3300" height="3300"}

*Average apartment area across Poland by the period in which the building was constructed. Data: Polish census 2021 (GUS NSP21).*

![Heatmap ranking around forty European and post-Soviet countries across roughly twenty spending categories by price level, from Switzerland and Iceland as the most expensive to Ukraine and Georgia as the cheapest. Poland is highlighted.](/images/data_viz/price_struct_tile_ang.png){: loading="lazy" width="1200" height="1200"}

*Price index by spending category, 2021. Switzerland has the tenth most expensive alcoholic beverages but the highest general price level. Data: World Bank International Comparison Program.*

![Line chart of Polish parliamentary election polling from December 2019 to March 2021, with smoothed curves and 90 percent confidence intervals for Zjednoczona Prawica, Koalicja Polska, Konfederacja, Lewica and Polska 2050.](/images/data_viz/polls_plot_recent.svg){: loading="lazy" width="864" height="504"}

*Polish parliamentary election polling. Points are individual polls; the curve smooths them with a 90% confidence interval. Data: europeelects.eu.*

## COVID-19 in Poland

![Animated line chart of weekly deaths in Poland, with one line added per year from 2000 to 2020, showing the 2020 line rising far above every previous year.](/images/data_viz/smiertelnosc.gif){: loading="lazy" width="620" height="480"}

*Mortality in Poland, one time series per year from 2000 to 2020. Data: Eurostat and the civil registry via money.pl.*

![Ridgeline chart in the style of the Joy Division Unknown Pleasures album cover, showing standardised two-week moving averages of coronavirus case dynamics across all sixteen Polish voivodeships.](/images/data_viz/joy_div_plot_corona.svg){: loading="lazy" width="648" height="727"}

*Coronavirus in Poland by voivodeship — a standardised two-week moving average, drawn to resemble the Joy Division "Unknown Pleasures" cover. Someone apparently made themselves a t-shirt of this one and sent me a picture of it.*

![Ridgeline chart showing the development of coronavirus cases across Polish voivodeships as a weekly moving average standardised to each region's maximum, with individual peaks marked.](/images/data_viz/ridge_covid.svg){: loading="lazy" width="648" height="727"}

*Coronavirus development by voivodeship, weekly moving average standardised against each region's maximum. Data: Polish Ministry of Health.*

![Animated bar chart race of COVID-19 vaccination progress across countries.](/images/data_viz/vacc_race.gif){: loading="lazy" width="620" height="480"}

*A bar chart race of COVID-19 vaccination rollout by country.*

![Line chart of the percentage of population vaccinated against COVID-19 by days since each country's first vaccination, as of February 2021. Israel leads at close to 50 percent, followed by the United Kingdom and the United States, with Poland, Czechia and the European Union clustered near the bottom.](/images/data_viz/acc_countries.png){: loading="lazy" width="2100" height="2400"}

*How countries ran their vaccination campaigns — share of population vaccinated against days since the first vaccinated person, as of 19 February 2021. Data: Our World in Data.*

## Europe

![Dot density map of Europe on a black background showing electric vehicle charging points in green, densely clustered in the Netherlands, Germany, France and the United Kingdom and sparse across Central and Eastern Europe.](/images/data_viz/mapa_ev2_ang.png){: loading="lazy" width="1892" height="2100"}

*Where you can charge an electric vehicle in Europe. Data: OpenStreetMap.*

![Scatter plot of the change in log GDP correlation with the United Kingdom against each country's exports to the UK as a share of GDP at purchasing power parity, coloured by log distance in kilometres, with an upward-sloping fitted curve. France, Australia and New Zealand are labelled.](/images/data_viz/cross_section_corr.PNG){: loading="lazy" width="1419" height="810"}

*Business cycle comovement against trade intensity with the United Kingdom. This is the kind of question I look at in [my paper on business cycle transmission between France and the United Kingdom](/publications/business-cycle-transmission-france-uk/), published in the Journal of Economic Studies.*
