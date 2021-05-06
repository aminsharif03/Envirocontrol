# Envirocontrol
For this deliverable I learnt how to create user interfaces in python code. Here Is an example of a simple login screen that I designed on visual studio code using python with the help of an add on called tinter which is a graphical user interface that allows us to see what we are coding.

 ```from tkinter import *

root = Tk()
root.title("login")
root.geometry("250x150")
root.resizable(width=False, height=False)


def login():
    lblResult = Label(root, text="logging in")
    lblResult.grid(row=9, column=0)


# creating a label widget
lblWelcome = Label(root, text="welcome to EnviroControl", padx=55)
lblLogin = Label(root, text="login or new user", padx=55)

lblBlankLine = Label(root, text="      ")

lblUserName = Label(root, text="username:")
lblPassword = Label(root, text="password:")
entUserName = Entry(root, width=15)
entPassword = Entry(root, width=15)

# place onscreen
lblWelcome.grid(row=0, column=0, columnspan=3)
lblLogin.grid(row=1, column=0, columnspan=3)
lblBlankLine.grid(row=2, column=0)
lblBlankLine.grid(row=3, column=0)```

https://youtu.be/qHtZv0Zauwc

1. What was your goal for this deliverable, as defined on your Learning Plan?
To learn how to create a user interface and also learn how to create a sign up/login page

2. Did you meet this goal? If not, why?
I did meet this goal and am now able to create my own pop ups swell as a sign up/login page.

3. What needs to happen for you to stay on schedule from this point forward (e.g., change of plan, putting in extra time, getting help, etc.)? 
Next I have to combine what I Learned this week with what I learned last week to create the foundations of the program.

Date|semester Milestone|Project Milestone
----|------------------|------------------
Sun 02 21|Deliverable 1: new learning|What is home automation What are the components required to have a fully functioning home automation system
Sun 03-07|Deliverable 2: new learning|Learn what a database is: How it functions and what’s required to make it run smoothly. Learn how to set one up
Sun 03-28|Deliverable 3: project foundation or new learning|How to design an intuitive user interface that is easy to use.Learn how to set up a signup/login window to allow access to different users.
Sun 04-11|Deliverable 4: adding features & debugging| Integrate a user interface with a database of stored values for the different features in the program like, lighting, thermostat, and shutters. Also going to run multiple tests to see whether or not the database, save function, sign-in function, and delete functions are all working together. Tests will be done by making multiple different users and entering different values for each of the different fields.
Thu 05-06|Deliverable 5: using feedback to improve/debug|Create a simple program that takes the saved data and exports it to a connected raspberry pi which then executes the different functions such as turning on the thermostat at a certain time and having it be a certain temperature, turning the lights on and off at set times, and lowering and raising the shutters after sunset and after sunrise.


For this deliverable I learned what a database was and how exactly it works. I now understand that a databse is an organized colection of data that is stored electronically on a computer. It is controlled using a databse Database Management System (DBMS). Databases come in many shapes and forms and each one has its own uses. I wanted to focus on personal databases since these personal databaases which are used to store a users personal information like Usernames and passwords and in the case of this projects the different prefrences for the times that the lights, shutters, and thermostats turn on aswell as the temperature of the thermostat. The databse will also contain all the different rooms that each user has. The way that I have decided to store information is on an excel spreadsheet as there is some sensitive information like passwords that for most people is one password that is used for every account they own.

https://youtu.be/uKsWzCzZ7-8

1. What was your goal for this deliverable, as defined on your Learning Plan?
My goal was to completely understand what databases were and hey they worked, alongside how to set them up in a way to store data.

2. Did you meet this goal? If not, why?
I did meet this goal

3. What needs to happen for you to stay on schedule from this point forward (e.g., change of plan, putting in extra time, getting help, etc.)?
next I need to learn how to design a user interface using code and not just designing it by hand.

4. Paste your current, accurate learning plan below.

Date|semester Milestone|Project Milestone
----|------------------|------------------
Sun 02 21|Deliverable 1: new learning|What is home automation What are the components required to have a fully functioning home automation system
Sun 03-07|Deliverable 2: new learning|Learn what a database is: How it functions and what’s required to make it run smoothly. Learn how to set one up
Sun 03-28|Deliverable 3: project foundation or new learning|How to design an intuitive user interface that is easy to use.Learn how to set up a signup/login window to allow access to different users.
Sun 04-11|Deliverable 4: adding features & debugging| Integrate a user interface with a database of stored values for the different features in the program like,lighting, thermostat, and shutters. AAlso going to run multiple tests to see whether or not the database, save function, sign-in function, and delete functions are all working together. Tests will be done by making multiple different users and entering different values for each of the different fields.
Thu 05-06|Deliverable 5: using feedback to improve/debug|Create a simple program that takes the saved data and exports it to a connected raspberry pi which then executes the different functions such as turning on the thermostat at a certain time and having it be a certain temperature, turning the lights on and off at set times, and lowering and raising the shutters after sunset and after sunrise.

A program that controls a houses lights thermostat and automatic window shutters based on user inputs through a simple interface.
