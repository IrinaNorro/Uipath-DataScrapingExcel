# Project: Uipath-DataScrapingExcel

### Briefly about this project
This is originally a school assignment for RPA beginners' course. In this project I wanted to exctract data from a web page, use filter buttons on web page and place filtered data  in Excel sheet. Finally send as attachment by email. 

Check out also UseCase.pdf (in English) where I got inspiration for this project. For more information on this project you can find in Documentation.pdf. It is a school report (in Finnish) about this UiPath process, including code snippets, requirenment specification (vaatimusmäärittely), documentation and testing.

### Prerequisite
Before pushing Run button, you need to have:
- installed UiPath
- Firefox Exctension installed in UiPath
- Register to web page jimms.fi 
- Create credential Asset in your Orchestrator for web page jimms.fi and save it as "jimms.Kirjautuminen".
- place your Gmail account signing in details into "Send SMTP Mail Message" -Activity

### What to improve?
In order this project to work as it is in Use Case, we need to
- place extracted data from web page to (a.) Excel sheet
- need to have another (b.) Excel sheet to which we compare extracted data to
- place filtered data in third (c.) Excel sheet
- possibly convert exctracted data from Objects or String value to Double value
- possibly convert Decimals to Double 
- Figure out safer way of sending an email, since this one is possibly vulnerable way 

### Watch it on Youtube
https://youtu.be/OH6__NCZiFE 



![Vuokaavio_lopputyö_väri](https://user-images.githubusercontent.com/80334153/151970320-07f04603-1ea9-49f2-a963-ffb3993d3907.PNG)

### Thank you for your time and making it this far =) 
### Have fun with my projects and hit me with some feedback if you want to!

