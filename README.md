# API Testing - SOAP

## Project Name: Number Conversion Service
### Project URL
[Number Conversion Service API Documentation](#) <!-- Replace # with your actual URL -->

## Project Description
- This project involves testing the SOAP API for number to words conversion. The API converts numerical input into its English word equivalent. The testing focuses on validating the functionality of the API endpoint and handling various input scenarios.

## Test Cases
- A set of Postman test cases have been created to cover different scenarios for the number to words conversion API. These include positive and negative test cases to ensure robustness and accuracy in conversion results.

## Running Tests with Newman
- Newman is a command-line collection runner for Postman. It allows you to run and test a Postman collection directly from the command line.

## Prerequisites
- Node.js installed on your system.
- Newman installed globally via npm.
  
## Installation
1. **Install Node.js**  
   Visit the [Node.js website](https://nodejs.org/) and download the installer for your operating system. Follow the instructions to install Node.js.

2. **Install Newman globally using npm**
    ```sh
    npm install -g newman
    ```

# Generating HTML Reports with Newman

To generate detailed HTML reports, you can use the `newman-reporter-htmlextra` reporter.

## Prerequisites

Install the `newman-reporter-htmlextra` reporter globally via npm:

```sh
npm install -g newman-reporter-htmlextra
```
# Running Tests and Generating HTML Reports

To execute the tests and generate an HTML report, follow these steps:

## Command to Run Tests and Generate HTML Reports

Run the following command in your terminal:

```sh
newman run Py3x_ATB API Testing Porject#1.postman_collection.json -r cli,htmlextra
```

## NEWMAN Report
![image](https://github.com/user-attachments/assets/de150e41-0e47-4dd5-9b10-d63fe22b5a48)


## How to generate NEWMAN Allure Report
### Prerequisites
- Install: Newman alloure report Globally in CMD
 ```sh
newman i -g newman-reporter-allure
```
- Now, go to your JSON file directory, open command line terminal, type
```sh
newman run Py3x_ATB API Testing Porject#1.postman_collection.json -r allure
```
- Now allure report will be generated
## ALLURE Report
![image](https://github.com/user-attachments/assets/82be0ac5-9214-499c-a65b-14aa5e6efa47)
