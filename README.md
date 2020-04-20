# Random ID-Generator

![Version](https://img.shields.io/badge/version-1.0.1-blue.svg?cacheSeconds=2592000)
![Status: In progress](https://img.shields.io/badge/status-in%20progress-blueViolet)
![License: ISC](https://img.shields.io/badge/License-MIT-yellow.svg)

Tool that generates random unique identifier (id) based on letters and numbers and prints to console. 
Created as exercise for Kodilla bootcamp (module 20.5).

# Prerequisites

You will only need Node.js and npm or yarn installed in your environment.

# Install

In your console run one of following commands to install: 

`$ yarn add @natkalia/randomid-generator`

or 

`$ npm i @natkalia/randomid-generator`

# Features

* accepts one param: desiredi id length as integer
* generates random unique identifier (id) 
* based on letters and numbers 
* prints generated random id to console

# Usage

```
const randomID = require('@natkalia/randomid-generator');

console.log(randomID(10)); // provide desired id length (integer) as param
```
