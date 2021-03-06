# Hotels

## Introduction

The idea for the training application **Hotels** comes from an old project developed for Origina S.r.l. 
in which an application was displaying the data received from a web API offering hotel booking service.
This will be useful for the main target of this exercitation: accessing the data from a **remote source**.

To achieve this, the app uses a free account of the API offered by [hotels4.p.rapidapi.com](https://rapidapi.com/apidojo/api/hotels4).
Through these, it is possibile to get the list of cities matching a destination name, the hotels near the 
selected city and the details about the choosen hotel. The data offered from the API are not very consistent
with the expectations (a search of 'Rome' will display everything but the italian capital) but the offered
protocol is still meeting the requirements of the application.

## App features

The user interface consists in a basic **wizard** with navigation buttons *Back* and *Next* that will show
three panels:

1. **Travel details**: destination selection, checkIn and checkOut dates and adults in up to three rooms
2. **Hotel selection**: a list of the hotels near the selected city
3. **Hotel details**: address, picture and amenities of the selected hotel

The app uses the same **GenericPanel** component to display both error alerts and date selection popup.

## Dependencies

In order to create this app, the following packages has been installed:

1. react-native-popup-dialog
2. react-native-dropdown-picker
3. react-native-date-picker


