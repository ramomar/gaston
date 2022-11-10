# gaston

<p align="center">
   <img src="https://user-images.githubusercontent.com/10622989/200959888-a9ad3d00-98e4-4431-87cd-0e4a38042680.gif" />
</p>

Gaston is an app for organizing personal finance.

You can read a nice blog post[here](https://ramomar.medium.com/gaston-55052ab661af) (spanish).


## Features

- User login
- Account movements by date screen
- Review movement screen
- Movement details view



## Project structure

The project is contained in many repos.

|Repository name | Description |
|----------------|-------------|
| [Gaston Frontend](https://github.com/ramomar/gaston-frontend) | The frontend of Gaston made with React. |
| [Gaston Backend](https://github.com/ramomar/gaston-backend) | The AWS based serverless backend for Gaston. |
| [Gaston Data](https://github.com/ramomar/gaston-data) | Scripts for processing bank account movements data. |
| [banes](https://github.com/ramomar/banes) | A library for scraping bank account movement information from Banorte notification emails. |
| [gmail-email-extractor](https://github.com/ramomar/gmail-email-extractor) | Script for downloading emails from gmail given a query string. |


## Backend diagram

<p align="center">
   <img src="https://user-images.githubusercontent.com/10622989/200975223-466dac5c-3beb-481c-8c69-c82a574c0e65.png" />
</p>




