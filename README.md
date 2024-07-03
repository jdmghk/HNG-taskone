# HNG-taskone
# User and Group Management Script
This Bash script automates user and group management on a Linux system. It reads usernames and associated groups from a file, creates users with random passwords, assigns them to groups, and logs all actions.

# Overview
Functionality: Creates users, sets up home directories, assigns users to specified groups, generates random passwords, and logs actions.<br>
Logging: Logs all actions to ```/var/log/user_management.log.```<br>
Password Storage: Stores generated passwords securely in ```/var/secure/user_passwords.txt.```<br>
Detailed Information: For detailed explanation of each step and how to run the script, please refer to the blog <a href="https://hashnode.com/draft/668408e54be983e484791b69">here</a>

# Execution Steps

# 1.Clone the repo: 
```
https://github.com/jdmghk/HNG-taskone
cd HNG-taskone
```

# 2.Make the script executable:
```
chmod +x create_users.sh
```

# 3. Run the script with an input file:
```
   sudo ./create_users.sh <input_file>
```

4.Verify: ``
*Check the log file for performed actions:
```
cat /var/log/user_management.log
```
*View the generated passwords: ``
```
sudo cat /var/secure/user_passwords.txt 
```

# Blog Post

