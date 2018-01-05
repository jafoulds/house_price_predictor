# Predicting Housing Prices in Vancouver & Victoria
## Created by Jack Belford, Jared Foulds, Jeremy Krenbrink, & Carl Marais

This program works by scraping data from www.remax.ca using Node.js and Google’s Puppeteer library and putting the data into a .json file. Specific pieces of data of each house listing are then extracted from the .json file and put into a "House" object. A list of these house objects is then thrown into multiple classifiers and the results are then printed.

