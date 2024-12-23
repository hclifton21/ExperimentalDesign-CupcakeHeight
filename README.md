# ExperimentalDesign-CupcakeHeight
Authors: Harley Clifton, Madelaine Brown, and Kyle Rutten 

## Overview
Investigating the Impacts of Oven Temperature on Pillsbury Funfetti Cupcake Height.

This is a Self Designed Experiment, Pilot Study, Data Collection, Visualization, and Analysis.

## Project Description
When baking cupcakes, it is generally preferred to have cupcakes that are as tall as possible. Taller cupcakes have a cone shape which is more ideal for frosting compared to flat cupcakes. Cupcake Height serves as a stand-in for many other measures that are more descriptive, but much harder to measure such as cupcake moisture and cupcake density. Thus, this metric is a general stand-in that we seek to optimize. While each box of cupcake mix will provide a recommended baking time and temperature, each individual oven can vary greatly in how it heats up and holds its temperature. These differences in individual oven temperatures can lead to variations in Cupcake Height. We aim to identify the ideal temperature setting on Harley’s oven that will result in the tallest Pillsbury Funfetti Cupcakes; therefore, making the best cupcakes possible in a given amount of time.

## Code and Resources Used
This project was coded using R/RStudio. 

The following packages were used: 
- yarrr
- ggplot2
- ggthemes
- tidyverse
- knitr
- gtsummary
- multcomp
- effects



# Data
Data was collected from experiments conducted at various oven temperatures. The dataset is available in the data/ directory.

The data was gathered by baking cupcakes at different temperatures (300°F, 325°F, 350°F, and 375°F) and measuring their heights.

## Variables
The following variables were measured:

- Study: pilot or experiment
- Temp.F: oven temperature in Fahrenheit
- Batch.Number: batch number, different for each pan that entered the oven
- Box.Number: indicator variable for the different boxes of cake mix
- Location: location in pan (1-6)
- Height.cm: height of the cupcake in centimeters



# Results and Evaluation
Based on our results, there may be a meaningful difference between cupcake height when comparing baking temperatures 300°F and 375°F (4.02 cm and 4.5 cm, respectively). All other baking temperature comparisons did not result in a meaningful difference. With this information, we can conclude that baking cupcakes at 375°F will result in better cupcakes than baking at 300°F, in regards to height alone. 

The results indicate that baking at 375°F yields the tallest cupcakes, averaging 4.5 cm. Visualizations of cupcake heights at different temperatures can be found in the Final Report pdf file.



# Future work
Other factors that may contribute to cupcake satisfaction are cupcake moisture, density, and overall taste; further exploration of these qualities would require us to conduct additional experiments. 



# License
For this github repository, the License used is [MIT License](https://opensource.org/license/mit/).
