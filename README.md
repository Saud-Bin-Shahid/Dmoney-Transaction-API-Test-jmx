# Dmoney Transaction API Test With Jmeter

## Test Scenario
The Jmeter Project involves testing the DmoneyAPI by creating test cases for multiple API requests. The ramp-up and the number of threads in jmeter setting were kept as 1.

## Project Scenario (Request)
1. Login to admin account
2. Create a new agent account
3. Create a new customer account
4. Deposit money from the system to newly created agent account
5. Deposit money from agent to customer account
6. Check balance of the customer account
7. Customer withdraws money through an agent
8. Payment can be completed by the customer to a merchant account

## Technology and Tool Used
- Apache Jmeter
- JAVA

## Pre-requisite
1. Install jdk 11 or any LTS version
2. Download and extract Apache Jmeter latest version
3. Configure JAVA_HOME and JMETER_HOME in system environment variable

## To Run This Project
1. Clone this project or download the .jmx file in the project directory.
2. You can generate your own HTML summary report by running the following code in the terminal:
3. jmeter -n -t DmoneyAPI.jmx -l DmoneyAPI.csv -e -o Reports

## HTML Summary Report
![screencapture-file-C-Users-Suhada-Downloads-Compressed-apache-jmeter-5-6-2-bin-Reports-index-html-2023-09-02-18_19_24](https://github.com/Saud-Bin-Shahid/Dmoney-Transaction-API-Test-jmx/assets/134185250/3b402f12-8b40-4b35-bae3-7338fb3101f5)

## Whole project structure in Jmeter
![Test_Plan](https://github.com/Saud-Bin-Shahid/Dmoney-Transaction-API-Test-jmx/assets/134185250/5693d432-a6ad-4aac-8005-da5b9ea15679)

## Results from 'View Results Tree'
![View Result](https://github.com/Saud-Bin-Shahid/Dmoney-Transaction-API-Test-jmx/assets/134185250/769ce9d9-5cac-4315-9262-fbe291e47f82)

## Jmeter Summary Report
![Summery Report](https://github.com/Saud-Bin-Shahid/Dmoney-Transaction-API-Test-jmx/assets/134185250/f2baee35-8b86-471c-bd80-61d87f4494d5)

