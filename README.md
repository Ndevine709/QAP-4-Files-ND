## Introduction
This repository contains all the files needed for QAP 4 of semester one of Software Development. Included in this repository is a zipped file for my Python project containing the main Python file (QAP4.py) and the .dat files needed for the data (const.dat & policy.dat). Also included is a zipped file for the JavaScript portion of this QAP which includes the main html page (index.html) and the JavaScript file (motel.js). Finally we have a pdf which contains the ERD diagram and some extra fields that could be added to the ERD to make it better (done by Noah Devine, Laura Wiseman & Christopher Meadus of group # 2)

## One Stop Insurance Company - Python Project
The files included in "QAP 4 Python.zip" are used to help the One Stop Insurance Company calculate insurance policy payments/costs and display the information out to the user. Along with this, the program also manipulates list in order to display previous claim information.

To get started, dowload the "QAP 4 Python.zip" file and unpack it in your destination of choice. Then open the folder via your shell of choice (VSC works well).

- Once you start the program, you will be required to input multiple pices of information about the customer for the claim (Ex. name, address, phone number)

- The program will also ask you to make choices on different options (Ex. do you want glass coverage?)

- Near the end of the programs inputs, it will ask you to input a previous claim number, date and amount. This section is wrapped in a loop and for the purpose of the project, you should run through the loop three times (running through it three times will basically store three different sets of previous claim information in lists and will display that information to the user at the end)

- Once your inputs are are complete, the program will perform all required calculations and display a well designed reciept for the user and save the data to the "policy.dat" file (while this is being done, the program will show a flashing message to the user to indicate that the data is being saved).

- Along with this, the program will also then add 1 to your policy number counter and save it back to the "const.dat" file. This is done so that when you close out the program and run it again, the next policy number will be used and not repeat the same policy number for each customer.

- Finally the program will ask you if you would like to process another claim or end the program.

## Motel ERD Project - Group #2 (Noah Devine, Laura Wiseman, Christopher Meadus)
Included in this repository is a pdf containing an ERD diagram completed for a motel database done by our group. This diagram lists the required fields for the database and shows the relationships between each field. at the end of this pdf is a page explaining possible fields that could be added to make the ERD more efficent.

## Motel Customer - JavaScript Project
For this project, I've created an object in JavaScript that contains attributes and methods for a motel customer. this program makes use of sub-objects and arrays, along with also using object methods to perform various calculations such as determining the customers age and duritation of their stay. At the end of the program, I used a template literal string to write a paragraph to the html page describing the customer I defined in my object.

- If you are using VSC with a "live server" extension, you can right click the index.html file and open in live server.

- Assuming the user is operating on Google Chrome, you can right click the screen and then left click "inspect"

- From there, left click the console tab and from there you can see the JavaScript in action.

- The first line will show the customers age, then how many days they stayed at the motel, then a paragraph describing the customer (this can also be seen on the html page).
