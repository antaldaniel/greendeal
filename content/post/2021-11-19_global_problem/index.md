+++
title = "100,000 Opinions on the Most Pressing Global Problem"
subtitle = "Which of the following do you consider to be the single most serious problem facing the
world as a whole?"
date = 2021-11-25T09:41:00+01:00
lastmod = 2021-11-25T09:41:00+01:00
draft = false

authors = ["daniel_antal"]

tags = ["survey harmonization","data-as-service", "retroharmonize", "climate awareness", "Europe"]

summary = "Imagine if you could compare data easily from surveys taken about climate change from all European countries, maybe even from other contients, from different years? If you could work with a sample of not only n=1000, n=4000, or n=10,000 but n=100,000? What type of granularity it would give you about the perception of climate change or supported policy measures?  That is exactly what our survey harmonization software allows for you to do."

projects = ""

# Featured image
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"

  # Show image only in page previews?
  preview_only = true

+++

<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/global_problem_1_climate_change_5_plots.png" caption="A reprezentative sample of n=100793 from 5 years on the most serious global problem." numbered="false" >}}</td>

You can use and verify our software: it is a perfectly documented, open source, peer-reviwed scientific software. But for most users, a bit too difficult to handle.  This is why we are building the Green Deal Data Observatory as a user-centric API around the software.  The Green Deal Data Observatory is processing climate-change related data from variuos survey, sensory, satellite data sources, and places them into tidy, easy-to-import datasets and visualizations.

Survey harmonization means various social science, statistical and data processing steps to make data comparable and joinable from various questonnaire answers taken in different countries, lanugages, and years. To demonstrate the power of retrospective survey harmonization, we have made an indicator, visualizations and a data animation from more than a hundred nationally representative surveys, which asked more than 137,000 europeans about what they considered to be the single most serious problem facing the world as a whole?

![](/media/gif/blogposts_2021/global_problem_1_climate_change_800.png)

Survey data harmonization refers to procedures that improve the data comparability or the possibility to make policy or scientific comparisons between data from surveys conducted in different countries or in different years. Our retroharmonize software helps this tedious, laborous, difficult data processing task. 

The result is stunning compared to a survey of 1000, 4000 or even 10,000 people.  In this video we have harmonized the answers from more than 137,000 Europeans surveyed in more than 20 languages. As you can see in the data animation, people got more and more concerned about climate change... until Covid struck.

Our data shows that more urban and higher educated people tend to be more and more concerned about climate change. Concern is higher and higher as younger and younger people are asked. (Our data source, the Eurobaromter survey is asking Europeans from the age of 15.)

There are huge national differences in Europe: people in the countries that we defined as Nordic (Scandinavia and Finland) are much more serious about climate change than the rest of the continent. It also matters when was the question asked: between 2013-2019 anxiety over the climate has been growing rapidly, but it peaked in 2019.  In 2020, the Covid pandemic has altered the problem map of the European population, with ‘infectious diseases’ other important global problems. But apart from the time of asking the question, and the place of asking, there are important patterns emerging all over Europe which are shared regardless of the time and place.


<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/CART_global_problem_1_climate_change.png" caption="Our classification tree model shows what factors play an important role in determining if somebody believes that climate change is the most important global problem." numbered="false" >}}</td>

People with no formal education rarely think that climate change is the most important global problem. People with secondary school education care less than people with tertiary education, and people with tertiary aducation or a bachelor's degree care less than people who have a university degree or who are committed to life-long learning. This effect is further emphasised by level of urbanization: the more urbanized are the respondants, the more likely they think that climate change is the single most important problem facing humanity. (Urban people tend to have higher education levels, too.)

Another important factor is age: the younger the respondent, the more likely to believe that climate change is the single most important problem.

One takeaway is that generally, people's climate awareness is rising: Europeans tend to be more urbanized and more educated, and this works in favor of recognizing this problem.  The coming younger generations are also more aware of climate change. Yet, as Covid-19 shows, a global trauma can alter the picture quickly.

Using the [implemented machine learning](https://christophm.github.io/interpretable-ml-book/) R software package of Christoph Molnar, we calculated the importance of various socio-demography variables in predicting who will think that climate change is the most imporatnt problem facing us.

<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/importance_global_problem_1_climate_change.png" caption="Out of the variables we investigated, time spent in education is the most important factor contributing to climate awareness, closely followed by the time when the question was asked." numbered="false" >}}</td>


The importance of age, time, and even the time spent in education (age of leaving formal education) show that there is very significant change over time. Unfortunately, this change is not monotonous, until 2019 climate awareness was growing by this indicator, then it declined due to Covid.

If you would ask a European citizen about the most important global problem today, the following decision tree would help guessing if she or he would reply "climate change". 

<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/CART_global_problem_1_climate_change.png" caption="Our classification tree model shows what factors play an important role in determining if somebody believes that climate change is the most important global problem." numbered="false" >}}</td>

The education level, the age, and the question of asking are very important variables, and so is the fact if the respondent has at least one child.  Interestingly, parents are less likely to be concerned about climate change then other people. In other words, the children are more concerned than their parents. 


[](https://greendeal.dataobservatory.eu/post/2021-06-18-gold-without-rush/)




<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/noaa-WWVD4wXRX38-unsplash-edited.png" caption="In the previous blogpost we explained how we added value with documenting the data following the *FAIR* principle and with the professional curatorial work of placing the data in context, and linking it to other information sources that are not depending on the English language, and can connect our radio dataset to other data, books, publications, regardless if they are described in English, or in German, or Slovak. Photo: Atmospheric Research Observatory, South Pole, Antarctica Photo: [NOAA](https://unsplash.com/photos/WWVD4wXRX38)." numbered="false" >}}</td>

Completing missing datapoints requires statistical production information (why might the data be missing?) and data science knowhow (how to impute the missing value.) If you do not have a good statistician or data scientist in your team, you will need high-quality, complete datasets. This is what our automated data observatories provide.

## Why is data missing?

International organizations offer many statistical products, but usually they are on an ‘as-is’ basis. For example, Eurostat is the world’s premiere statistical agency, but it has no right to overrule whatever data the member states of the European Union, and some other cooperating European countries give to them. And they cannot force these countries to hand over data if they fail to do so. As a result, there will be many data points that are missing, and often data points that have wrong (obsolete) descriptions or geographical dimensions. We will show the geographical aspect of the problem in a separate blogpost; for now, we only focus on missing data.

Some countries have only recently started providing data to the Eurostat umbrella organization, and it is likely that you will find few datapoints for North Macedonia or Bosnia-Herzegovina. Other countries provide data with some delay, and the last one or two years are missing. And there are gaps in some countries’ data, too.


<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/zenodo_global_problem_1_climate_change.png" caption="See the authoritative copy of the [dataset](https://zenodo.org/record/4775787#.YYqevmDMLIU)." numbered="false" >}}</td>

This is a headache if you want to use the data in some machine learning application or in a multiple or panel regression model. You can, of course, discard countries or years where you do not have full data coverage, but this approach usually wastes too much information--if you work with 12 years, and only one data point is available, you would be discarding an entire country’s 11-years’ worth of data. Another option is to estimate the values, or otherwise impute the missing data, when this is possible with reasonable precision. This is where things get tricky, and you will likely need a statistician or a data scientist onboard.

## What can we improve?

Consider that the data is only missing from one year for a particular country, 2015. The naive solution would be to omit 2015 or the country at hand from the dataset. This is pretty destructive, because we know a lot about the R&D allocations in this country and in this year! But leaving 2015 blank will not look good on a chart, and will make your machine learning application or your regression model stop.

A statistician or an innovation expert will tell you that you know more-or-less the missing information: the total allocation was most likely not zero in that year.  With some statistical or innovation, or public finance specific knowledge you will use the 2014, or 2016 value, or a combination of the two and keep the country and year in the dataset.

Our improved dataset added backcasted (using the best time series model fitting the country's actually present data), forecasted (again, using the best time series model), and approximated data (using linear approximation.) In a few cases, we add the last or next known value.  To give a few quantiative indicators about our work:

- Increased number of observations: 29.2%
- Reduced missing values: -26.4%
- Increased non-missing subset for regression or AI: +64.7%


If your organization is working with panel (longitudional multiple) regressions or various machine learning applications, then your team knows that not havint the +66.67% gain would be a deal-breaker in the choice of models and punctuality of estimates or KPIs or other quantiative products. And that they would spent about 90% of their data resources on achieving this +66.67% gain in usability.

If you happen to work in an NGO, a business unit or a research institute that does not employ data scientists, then it is likely that you can never achieve this improvement, and you have to give up on a number of quantitative tools or visualizations. If you  have a data scientist onboard, that professional can use our work as a starting point.

## Can you trust our data?

We believe that you can trust our data better than the original public source. We use statistical expertise to find out why data may be missing. Often, it is present in a wrong location (for example, the name of a region changed.)

If you are reluctant to use estimates, think about discarding known actual data from your forecast or visualization, because one data point is missing.  How do you provide more accurate information? By hiding known actual data, because one point is missing, or by using all known data and an estimate?

Our codebooks and our API uses the [Statistical Data and Metadata eXchange](https://sdmx.org/?page_id=3215/) documentation standards to clearly indicate which data is observed, which is missing, which is estimated, and of course, also how it is estimated. 
This example highlights another important aspect of data trustworthiness. If you have a better idea, you can replace them with a better estimate.  

Our indicators come with standardized codebooks that do not only contain the descriptive metadata, but administrative metadata about the history of the indicator values. You will find very important information about the statistical method we used the fill in the data gaps, and even link the reliable, the peer-reviewed scientific, statistical software that made the calculations. For data scientists, we record the plenty of information about the computing environment, too-–this can come handy if your estimates need external authentication, or you suspect a bug.

## Avoid the data Sisyphus


If you work in an academic institution, in an NGO or a consultancy, you can never be sure who downloaded the [GBARD by socioeconomic objectives (NABS 2007)](http://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=gba_nabsfin07&lang=en) Eurostat folder from Eurostat. Did they modify the dataset? Did they already make corrections with the missing data? What method did they use? To prevent many potential problems, you will likely download it again, and again, and again...

<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/Sisyphus_Bodleian_Library.png" caption="See our [The Data Sisyphus](https://reprex.nl/post/2021-07-08-data-sisyphus/) blogpost." numbered="false" >}}</td>

We have a better solution. You can always rely on our API to import directly the latest, best data, but if you want to be sure, you can use our [regular backups](https://zenodo.org/record/5652118#.YYhGOGDMLIU) on Zenodo. Zenodo is an open science repository managed by CERN and supported by the European Union. On Zenodo, you can find an authoritative copy of our indicator (and its previous versions) with a digital object identifier, in this case, [10.5281/zenodo.5661169](https://doi.org/10.5281/zenodo.5661169). These datasets will be preserved for decades, and nobody can manipulate them. You cannot accidentally overwrite them, and we have no backdoor to modify them.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5661169.svg)](https://doi.org/10.5281/zenodo.5661169)

[![rOG-badge](https://ropengov.github.io/rogtemplate/reference/figures/ropengov-badge.svg)](http://ropengov.org/)
[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/retroharmonize)](https://cran.r-project.org/package=retroharmonize)
[![metacran downloads](https://cranlogs.r-pkg.org/badges/retroharmonize)](https://cran.r-project.org/package=retroharmonize)
[![DOI retroharmonize](https://zenodo.org/badge/DOI/10.5281/zenodo.5710064.svg)](https://doi.org/10.5281/10.5281/zenodo.5710064)

*Are you a data user? Give us some feedback! Shall we do some further automatic data enhancements with our datasets? Document with different metadata? Link more information for business, policy, or academic use? Please  give us any [feedback](https://reprex.nl/#contact)!*
