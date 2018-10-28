# ANP Exploratory Data Analysis

Repo that contains an exploratory data analysis of pre-salt wells and geo data from public ANP data base.
You can check by yourself the data base clicking [here](http://www.anp.gov.br/dados-estatisticos).

For the present analysis, we provide all necessary data files, check out "data" dir. There you can find all data related to the
general wells and pre-salt wells.

The georeferencing data is sited in "Campos" dir. There you can find `.shp` files related to some Petroleum fields provided by ANP.

**Remark:** This work IS NOT related to our jobs. We do it in our free time.

## Where is the analysis?

You can find what we are doing in the `eda_anp_presentation_pyBR14.ipynb` sited in "notebook" dir. Check it out! That notebook was used as a base to the
presentation Diego did at [Python Brasil[14]](https://2018.pythonbrasil.org.br/), the biggest brazilian Python conference.

To enjoy the best, download the `.ipynb` and run locally in your computer (instructions below).

## What did you used?

Essentially we did an exploratory data analysis to answer and visualizate more easily some data related to wells. Special attention
was given to pre-salt wells, knowing that they are a very promising energy source to Brazil.

So, looking for an easy visualization, we employ some data analysis over a map. Breafly speaking, we used:

* [pandas](https://pandas.pydata.org/) for handling the data set;
* [GeoPandas](http://geopandas.org/) for handling georeferencing `.shp` and associate files;
* [Folium](http://python-visualization.github.io/folium/) to build maps;
* [Altair](https://altair-viz.github.io/), [Seaborn](https://seaborn.pydata.org/) and [Matplotlib](https://matplotlib.org/) to data
visualization.

## I want to try myself, what I have to do?

We use [conda](https://conda.io/docs/) envs and strongly recommend you do the same. If you use conda, we provide our `environment.yml`
for you, just install from our file and you will have the same environment than us, readily reproducible.

Others package manager will be available soon.

## Amazing work! How I can contribute?

* Install our environment;
* Create a branch to your work;
* Do your contribution in your branch;
* After you finished, send us a PR.

**Remark:** If you added some extra packages to the environment, please update the `environment.yml` in the PR too.

## I like the way you do it, can I touch this?

Yes, but please cite us properly under MIT license.

## Oh, I want to talk with who did this work

One can contact us through the emails:

* Diego Volpatto: diego@esss.co
* Eduardo Bürgel: burgel@esss.co
