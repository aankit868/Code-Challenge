# Code-Challenge

## description
This is a mini version of Loan repayment system built with Laravel framework. 
The APIs will allows to handle user loans. 
The following features/functions will be includes.

**user's functions**
 - user can register
 - user login via API & token will return (that token have to used for all the functions below)
 - user can request a loan (if there is no outstanding repayment)
 - user can view his requested loans
 - user can view the loan that had offered to him
 - user can accept the offered loan
 - user can make payment
 
 **admin's functions**
  - admin can register
  - admin login via API & token will return (that token have to used for all the functions below)
  - admin can offer a new loan
  - admin can view loan details
  - admin can view overdued loans



## installation

```
(1) create database
(2) configure config/database.php
(3) php artisan migrate
(4) php artisan passport:client --personal
 ```
 
## testing tool
[Postman](https://www.getpostman.com/)


      
