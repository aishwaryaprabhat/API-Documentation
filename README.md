# API-Documentation
Cheatsheet/Guide for writing API Documentation

## Introduction

### What are APIs?
- Application Programming Interface
- How two pieces of software talk to each other
- APIs allow developers to create apps that "mash up" data from different sources

### What is REST?
- Represntational State Transfer
- A request is the client asking "what is my state"
- A response is the server saying "I am trasferring you some data that represents the state"
- Auth:
  - Client must prove identity to the server
  - Authentication:
    - Username and password
  - Authorization:
    -  Use token
    -  Authority to make a request
 - OAuth is a popular platform 


## General Data Types
- Integers (int)
- Decimals (float/double)
- Text (string)
- True/False (boolean)
- Dates
- Custom Types (Objects, dictionaries etc)
- Collections
  - Arrays
  - Dictionaries

JSON has 3 types:
- Number
- String
- Boolean
XML has one type:
- String

## JSON

### What is JSON?
- JavaScript Object Notation
- JSON was originally created to hold structured data to be used in JS
- Commonly used for sending data for Web APIs

### Data Types
- Strings: enclosed in single or double quotation marks
- Numbers: Integer or decimal, positive or negative
- Booleans: true or false (no quotation marks)
- null: no quotation marks
- Arrays: comma separated lists; can have multiple data types inside them
- Objects: JSON dictionaries, key-value pairs separated by commas; keys and values can be any data type

Objects and arrays can be nested within each other

### Documenting JSON
- Start with a one sentence description
- JSON details are best documented in one or more tables
- Good to also include additional information
- One possible way of documentation is by using tables
  - JSON responses: 

  | Element  | Description  | Type   | Notes   | 
  |---|---|---|---|


  - JSON requests:

  | Element  | Description  | Type   | Required   | Notes |
  |---|---|---|---|---|



