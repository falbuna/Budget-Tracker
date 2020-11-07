# Budget-Tracker

Homework for Week 18

The Budget Tracker Application can be found here: [https://shrouded-caverns-93980.herokuapp.com/](https://shrouded-caverns-93980.herokuapp.com/)

## Introduction

This application allows the user to add transactions to a Budget that will Add or Subtract funds from a transaction list. The application also has offline functionality that will allow the user to enter deposits and expesnes offline, which will be added to the tracker when brought back offline.

## Table of Contents
* [Description](#Description)
* [Usage](#Usage)
* [Questions](#Questions)

## Description

The application uses IndexedDB and Mongo to create the database, Express to handle the api routes, and manifest.webmanifest and service-worker for offline functionality. This will allow the page to create transactions offline, and update the database when going back online.

## Usage

When the user first reaches the page, this is what they will see. The user can input a transaction with the amount of the transaction, and either Add or Subtract funds.

![]()

After inputting transactions, the page will update with either the additional or subtraction of funds from the budget. The total on the top of the page will also update.

![]()

When the user goes offline, the page transactions will get saved and updated to the page when their connection is back online.

![]()

## Questions

If you have any questions regarding this application, please reach me at: falbuna1@gmail.com

My Github can be found here: [https://github.com/falbuna/](https://github.com/falbuna/)