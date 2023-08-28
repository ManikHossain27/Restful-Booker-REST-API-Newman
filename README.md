# Restful-Booker-REST-API-Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -d Booker_Herokuapp.csv
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -d Booker_Herokuapp.csv -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/26899722/2s9Y5Zu1bb

## Test case list:
1. ### Create Booking
	  1. > Create Data Sets using csv file
	  2. > Verify Status code is 200
2. ### Booking Status
  > In the test case you need to validate the following field values:
	  1. > First Name
	  2. > Last Name
	  3. > Total Price
	  4. > Deposit Paid
	  5. > Checkin Date
	  6. > Checkout Date
	  7. > Additional Needs
	  8. > Response Time below 350ms

3. ### Token
  > Generate Token
  
4. ### Update Booking
  > In the test case you need to validate the following field values:
	  1. > Successfull message
	  2. > Response Time below 350ms

5. ### Booking Status after Update
  > In the test case you need to validate the following field values:
	  1. > First Name
	  2. > Last Name
	  3. > Total Price
	  4. > Deposit Paid
	  5. > Checkin Date
	  6. > Checkout Date
	  7. > Additional Needs
	  8. > Response Time below 350ms 

6. ### Delete Booking
> Verify Status code


## Newman Report Summary:
![Newman Report Summary](https://github.com/ManikHossain27/Restful-Booker-REST-API-Newman/assets/131261253/34acdbdc-aefb-416d-9972-911f0f3bf515)
![Newman Report Summary](https://github.com/ManikHossain27/Restful-Booker-REST-API-Newman/assets/131261253/3c199ff8-b2bf-4132-b548-dea0fbec67d7)
![Newman Report Summary](https://github.com/ManikHossain27/Restful-Booker-REST-API-Newman/assets/131261253/5aa52c24-e8f5-4455-917f-3c49e69f673c)



