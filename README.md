# Android-App

This repository contains Android development assignments created as part of my coursework. These assignments are designed to help understand the fundamentals of Android app development, including UI design, user input handling, and basic functionality implementation using Java/Kotlin.

Each assignment focuses on different concepts and practical implementations in Android Studio.

## 1. Student Details App

###  Description
Assignment 1 is a simple Android application that collects student information from the user and displays it using a Toast message.

###  Features
- Takes input from the user:
  -  Name
  - City
  - Email
  - Phone Number
- Uses EditText fields for input
- Uses a Button to submit the data
- Displays entered details using a Toast message

### Working
1. User enters the required details in input fields.
2. When the user clicks the submit button:
   - The app collects all input data.
   - Combines the data into a single message.
   - Displays the message using a Toast.

### Purpose
The main objective of this assignment is to:
- Understand Android UI components (EditText, Button)
- Learn how to take user input
- Implement click events
- Display output using Toast

### 📷 Output
When the button is clicked, a Toast message appears showing all entered student details.
  <img width="386" height="859" alt="Screenshot 2026-04-17 212057" src="https://github.com/user-attachments/assets/444650e8-77bf-4d3a-a55d-b6f5bac4ba5d" />

###  Technologies Used
- Android Studio
- Java 
- XML (for UI Design)



  
## 2: Welcome Screen with User Input

###  Description
This assignment is a simple Android application that displays a welcome message and allows the user to enter their name. The app provides a basic user interface and demonstrates how to take input and handle button click events.


### 🛠️ Features
- Displays a welcome message at the top
- Input field for entering user's name
- A button to trigger an action
- Clean and simple UI design

---
###  Working
1. The app displays a welcome message like "WELCOME [User Name]".
2. The user enters their name in the input field.
3. When the user clicks the button:
   - The app reads the entered name

###  Objective
- Learn basic UI design in Android
- Understand EditText usage
- Handle Button click events

###  Components Used
- TextView (for welcome message)
- EditText (for user input)
- Button (for interaction)



###  Technologies Used
- Android Studio
- Java
- XML

- <img width="501" height="814" alt="Screenshot 2026-04-17 214413" src="https://github.com/user-attachments/assets/71201ea7-4693-4370-a9cf-48af7b0ca69e" />


  ## 3: Basic Calculator App

###  Description
This assignment is a simple Android calculator application that performs basic arithmetic operations like addition, subtraction, multiplication, and division.


###  Features
- Takes two numbers as input
- Performs:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Displays result for each operation


###  Working
1. User enters two numbers.
2. Clicks any operation button (Add, Sub, Mul, Div).
3. The app calculates and displays the result instantly.


### Objective
- Understand user input handling
- Learn button click events
- Perform basic calculations in Android



### Components Used
- EditText (for number input)
- Button (for operations)
- TextView (for displaying results)


<img width="388" height="847" alt="Screenshot 2026-04-17 215630" src="https://github.com/user-attachments/assets/a808d955-a014-48a0-b783-8f8d5c3819a7" />

## 4: User Preference Application

###  Description
This assignment is an Android application that allows users to select their preferred device and app features. The selected options are displayed after submission.


### Features
- Select one device using Radio Buttons:
  - Android
  - iOS
  - Windows
- Select multiple features using Checkboxes:
  - Notification
  - Dark Mode
  - Location Services
  - Cloud Backup
- Submit button to display selected options



###  Working
1. User selects a device (only one option).
2. User selects one or more features.
3. On clicking the submit button:
   - The app collects selected options
   - Displays selected device and features on the screen


###  Objective
- Learn RadioButton (single selection)
- Learn CheckBox (multiple selection)
- Handle user input and display output



###  Components Used
- RadioGroup & RadioButton
- CheckBox
- Button
- TextView

<img width="371" height="819" alt="Screenshot 2026-04-17 221231" src="https://github.com/user-attachments/assets/70e7917d-3daa-4bea-ac14-1aaf5a1e876f" />

## Assignment 5: Alarm & Notification App

### 📖 Description
This assignment is an Android application that allows users to set an alarm. When the alarm time is reached, the app plays a ringtone and shows a notification with an option to cancel the alarm.

---

### Features
- Set alarm time (Hour, Minute, AM/PM)
- Alarm rings at the selected time
- Displays notification when alarm triggers
- Option to cancel/stop the alarm from notification


### Working
1. User selects the desired alarm time.
2. Clicks on "Set Alarm" button.
3. At the scheduled time:
   - Alarm ringtone starts playing
   - Notification appears on the screen
4. User can stop the alarm using the cancel option.


###  Objective
- Learn AlarmManager usage
- Implement notifications
- Handle background tasks in Android


###  Components Used
- Time Picker / Number Picker
- Button
- AlarmManager
- BroadcastReceiver
- Notification Manager


###  Conclusion
This assignment helps in understanding how alarms and notifications work in Android and how to handle time-based events.


<img width="371" height="822" alt="Screenshot 2026-04-21 110438" src="https://github.com/user-attachments/assets/8f1248dd-ee3c-4d69-a7be-ff1bae120226" />
