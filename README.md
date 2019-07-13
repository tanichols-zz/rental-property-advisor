[![Build Status](https://travis-ci.org/tanichols/rental-property-advisor.svg?branch=master)](https://travis-ci.org/tanichols/rental-property-advisor) [![Sonar](https://sonarcloud.io/api/project_badges/measure?project=rental-property-advisor%3Amaster&metric=alert_status)](https://sonarcloud.io/dashboard?id=rental-property-advisor%3Amaster) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=rental-property-advisor%3Amaster&metric=coverage)](https://sonarcloud.io/component_measures?id=rental-property-advisor%3Amaster&metric=coverage)

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

The Rental Property Advisor is a simple React/Redux application with a Node/Express backend that enables a user to determine if they are likely to make a profit renting the property in question. The advisor uses public API's to determine the age of the property, the value of the property, as well as the expected rental value. This data is used to compute an expected maintenance expense, vacancy expense, and total expense in order to provide a more accurate recommendation than considering only mortgage and known expenses.

The goal of the project was to deliver a meaningfully valuable application pithing the project timeframe. I also built a complete CI/CD pipeline with unit tests, static code analysis, and production deployment. If I were to do the project again, I would include containerization and would work with a UX partner in order to develop a more usable interface.
