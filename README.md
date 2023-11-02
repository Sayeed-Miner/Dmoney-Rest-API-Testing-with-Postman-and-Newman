# DMoney Rest API Testing with Postman and Newman

## How to run this project:
- Dowload "Dmoney Rest API Testing.postman_collection.json" file
- Open Command Prompt(CMD) on your system
- Newman install command
```bash
npm install -g newman
```
- HTML extra install command 
```bash
npm install -g newman-reporter-html
```
- Copy folder path where file downloaded
```bash
cd [Path]
```
Example: cd C:\Users\Sayeed\Downloads
- Run command for test collections
```bash
newman run "Dmoney Rest API Testing.postman_collection.json"
```
- Run command for newman report
```bash
newman run "Dmoney Rest API Testing.postman_collection.json" -r htmlextra
```

## Tools:
- Postman
- Newman

## API Documentation:
https://documenter.getpostman.com/view/30384615/2s9YXbA6RD
  
## Test Cases: 
https://docs.google.com/spreadsheets/d/1BNN8V2vacGDyZvG9shyrSROSU5ZMZ8gPdn3WxDL2G3A/edit?usp=sharing

## Bug and Improvement Report:
https://docs.google.com/spreadsheets/d/1eWzoWq0kT7ttBBP0K_Q66glhsww_TeOHi9LKp4ZkaZM/edit?usp=sharing

## Newman Report Screenshot:
![Newman Report](https://github.com/Sayeed-Miner/Dmoney-Rest-API-Testing-with-Postman-and-Newman/assets/52811620/aea577e5-6b53-4755-931d-6faf171345e1)
