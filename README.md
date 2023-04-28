# Project 2: twoShops

An app to help you find two shops in close proximity of each other

## Technologies used

- Firebase to store data sets (Firestore)
- REST API calls (fetch) made from firebase
- React App
- MUI component library

## General Approach

Data stored in firebase consists of store name, address, longitude and latitude. The data is used to differentiate store's data set which is then used to calculate the displacement between 2 points (lat, lon). The displacement is calculated with the Haversine Formula which accounts for the radius of the Earth. The data is then filtered and a nested For loop is then used to iterate through the data to compare data and calculate the displacement if required. Items are pushed in to an array which is then mapped into a display modal.

## Link to the application

- not yet deployed

## Description of unsolved problems

Data set only consists of 3 stores (koi, heytea and playmade). other queries will return a blank result.
