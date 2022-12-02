# FYPJ-AttendanceCheckIn
Automatically helps you Check In/Out of the NYP FYPJ 2.0 System!

# Features
- Sends Notifications to your phone
- Automatically Logs into the portal to Check In/Out
- [Prevents Window from auto-locking you out](https://towardsdatascience.com/how-to-keep-windows-from-sleeping-570d2042b338)

# Requirements
- [Twilio Account w SMS enabled](https://www.twilio.com/login)
- Python v3.10.0
- Packages from requirements.txt
- Windows 10

# Instructions
### Step 1
Clone the repository
```
git clone 'https://github.com/Akari-light/FYPJ-AttendanceTakingSystem'
```
Alternatively, download and unzip the Attendence_System.zip
### Step 2
Launch your command prompt (CMD) and install the packages required.

Command:
```
python -r requirements.txt
```
### Step 3
Configure `credentials.txt` with your login and twilio credentials.
Sample:
```
username     : <FYPJ Login Username>
password     : <FYPJ Login Password>
account_sid  : <Twilio Account SID>
auth_token   : <Twilio Authentication Token>
twilio_phone : <Twilio's Phone Number>
usr_phone    : <Phone number to receive notifications>
```

**Note: Twilio's Account Info can be found at your twilio account console page.**
### Step 4
From your command prompt (CMD), navigate to the directory where to programme is stored and start Attendance_System.py

Command:
```
python Attendance_System.py
```
### Step 5 (Optional)
If your computer auto locks-out, Open a new command prompt (CMD) and run the coffee.py to emulate random clicking on the screen

Command:
```
python Coffee.py
```
# DISCLAMER 
Use the programme responsibily!!