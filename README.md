# KAMILIMU DATA SCIENCE TRACK GROUP ASSIGNMENT

This repo is in compliance with the set working standards of sharing worksamples as per the Kamilimu Data ScienceTrack.

Having been impacted with the introductory skills in datascience, we were tasked to come up with a real world solution to an identified problem with our data skills.

In our solution, we were guided by the following approaches:

- Frequentist - This involves peeling a number of onions to find the number of layers they have and using this to infer how many layers our onion has.

- Bayesian - Here we peel onions and improve on this information as we peel more onions either by increasing it or not.

In this process of learning gradually made to some approximations of parameters we were working on More of this can be foung on the notebooks.

## The process of Data Science

We can split the process of Data Science into 3 stages:

_Extraction, Exploration and Experience._

### Extraction

-This is the process of acquiring the data you need into the **environment** you want to use.

### Exploration

-This is the process of learning about the dat you have, fixing the errors you have as well as making intermediate conclusions about it.

### Experience

-Here we decide how the end users of the data will use our findings. This can be surmaries or visualizations. However, most people prefer dashboards.

#### Meta Data

-This is the information we have about the data i.e. how it's collected, by whom, how frequently and for what purpose. This is necessary in making an analysis plan.

##### Preferred Tools for Data Science

Technically Data Science relies on math. **It's always been math** but running your functions in a programming environment solves issues to do with reproducibility, schedulability and collaboration.

For our solution used Python3 in an ubuntu environment.

############################### BREAK ###############################

# Diving in

## Getting the environment ready

We first need to create an environment within which we can install and use python3. This we achieve through using virtual enviroment.

`sudo apt-get install python3-pip`
`pip3 install virtualenv`
`python3 -m venv kamilimuds`
`source kamilimuds/bin/activate`
`pip install pandas numpy seaborn jupyterlab`
`jupyter lab`

## Data Extraction

We intend to use publicly available datasets in this analysis with obvious choices being:
