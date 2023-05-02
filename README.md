# Heat_Demand_Forecast
Forecast heat demand for a communal heat plant in rural Bavaria, Germany. Data was generously provided by Naotilus GmbH. 

## Data
The Variables in the files are:
* S1: heat power
* S2: flow rate
* S3: leader temperature (initial temperature)
* S4: return temperature

For the years 2020 and 2021 we also have the outside temperature at the location of the heat plant. 

We also have: 
* holydays in Bavaria (a lot!)
* school vacations in Bavaria

## Contents
Please find the relevant stuff in the respective notebooks
* 01_plot_the_data (first plot for visual inspection)

## Set up environment
To set up, please execute the following lines of code

~~~
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
~~~