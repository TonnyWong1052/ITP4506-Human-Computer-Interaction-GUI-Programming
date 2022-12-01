# ITP4506 - Human Computer Interaction & GUI Programming
> ITP114105 Software engineering (Tuen Mun) Year2 2022/12

> Programming language - html, css, js(JQuery)

# Demon
## frontend
![Home](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/Home.png)
![PassengerInfo](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/PassengerInfo.png)
![SeatSelect](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/SeatSelect.png)
![ConfirmOrder](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/ConfirmOrder.png)
![Payment](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/payment.png)

## Data Management
![Home-backend](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/backend-home.png)
![Profile](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/profile.png)
![Staff](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/Staff.png)
![EditStaff](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/EditStaff.png)
![CreateStaff](https://github.com/TonnyWong1052/ITP4506/blob/main/demon/createStaff.png)

# Account
```
Role: User 
Account: user
Password: user
```

```
Role: Operator 
Account: operator
Password: operator
```

```
Role: Administrator 
Account: admin
Password: admin
```


# Functions of the System:
## 1) Register and Login
There are THREE types of user accounts: Administrator, Operator, and Normal_user.

After logging in, the main pages for Administrator, Operator, and Normal_user are different.
Normal_user could create an account by self-registration. While Operator accounts are created by Administrator manually. When Operator login to the system at the first time, they are required to reset their password. Users could renew their password through their registered email if they forget their password.

The system should help users to set a 'STRONG' password.

## 2) Searching
An advanced search function is required for the booking system. Users can search the flight information by the arrival airport and the traveling date and time.

Search results may include flight number, departure airport, estimated ticket price, etc. The information meeting the criteria will be displayed on the screen, which may be extended more than one page. Each searching record should have at least TWELVE items for the prototype.

## 3) View and Reserve
After a searching record is selected, users can look on it detailed, for example, the price for each class and seat availability of each class. After this, normal users decide whether to reserve a seat on the search or not, if it is available. A UI for reservation flow should be included in this prototype to guide the user to finish their booking. For example, choose the suitable class, ask the user whether they would like to fix a seat, reserve the meal, etc.
After that, a detailed booking information preview will be shown to the user before the final payment. In addition, users could view their previous booking information. However, they should only update and cancel their booking THREE days before the schedule.

# Set-up
open following html file
```
html/Home.html
```
