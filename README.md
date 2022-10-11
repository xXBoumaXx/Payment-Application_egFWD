# Payment-Application-
This project is built under supervision of EgFWD program.
___
# Project description
This project is payment order application. It is a simulation for the mini pay device that we're all use for paying in shops. 
Software is designed to be modular, reliable, maintainable and reusable.
## Project Software Architecture
![PA_SWA](https://g.top4top.io/p_2475nj5yb1.png)
## Folder Structure
Folder structure:
```
└───PaymentApplication
│   └───Card
│       └─── card.h
│       └─── card.c
│   └───Terminal
│       └─── terminal.h
│       └─── terminal.c
│   └───Server
│       └─── server.h
│       └─── server.c
│   └───Application
│       └─── application.h
│       └─── application.c
│   └───main.c
│   └───PaymentApplication.exe
```
## Modules
Card module: The module used to handle the card informations.
Terminal module: The module used to handle the real time input payment data.
Server module: The module used to process the payment transaction.
Application module: The module used to handle the modules and make them work together.

Project is built with error handling that can help the user/developer to maintin and develop the program.
___
#Credits
The credits back to the EgFWD Embedded Systems Professional Track specially
Eng Yehia M.Abu Eita (The instructor)
