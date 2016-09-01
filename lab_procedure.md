## Guide for submitting labs

### **Step 1: Navigate to today's repo on Github**

### **Step 2: Click 'Fork' button at top right**
Fork to your own Github user account

### **Step 3: Clone your forked copy using Terminal (command line interface)**
Type `git clone https://github.com/<yourusername>/<forkedrepo>`

### **Step 4: Work, do stuff**
Note: You should abide by the 'ABC' rule while working: **A**lways **B**e **C**ommitting. This is effectively "saving" your work as you go. To do this, cycle through Steps 4-7 as you work.

### **Step 5: Add changes (and check status)**
Check for changes between your repo on Github and your cloned repo on your computer using `git status`

Type `git add <filename>`to add the changes to `<filename>`.

If you want to add changes for multiple files (`<filename1>` & `<filename2>`), type `git add <filename1> <filename2>`

Or, add all changes for all files using `git add .`

### **Step 6: Commit changes**
Commit your changes and add a descriptive message describing what you changed using `git commit -m whatever` (write something else besides "whatever")

### **Step 7: Push changes to your Github repo**
Push your changes to your forked repo on Github. `git push`  or `git push origin master` should work, but to be more exact, you can type `git push https://github.com/<yourusername>/<forkedrepo>`

### **Step 8: Submit pull request on the gU version of the repo**
+ Navigate to gU repo that you originally clicked 'Fork' on.
+ Click on the 'Pull Requests' tab (sandwiched between 'Issues' and 'Wiki')
+ Click the green button that says 'New Pull Request'
+ **Write your name and your lab partner's name in the pull request title**
+ Finish by clicking 'Submit'
