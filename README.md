# TagUI-Automation
This automation flow downloads a specific recurring report from Wave cloud accounting software.
![image WebSigIn](https://github.com/MinionsAnalyst/TagUI-Automation/blob/master/WebSigIn.PNG)

TagUI Workflow
```
// Visit Wave Accounting login homepage
click chromelogo.png
click newtab.png
keyboard https://my.waveapps.com[enter]

// Enter credentials and login
click email.png
keyboard your_email
click password.png
keyboard your_password
click loginbutton.png
wait 5 seconds 

// Navigate to report
click report.png
click profitloss.png
wait 5 seconds

// Export the report as pdf
click export.png
click pdf.png
wait 5 seconds

// Log out so that users can sign in again
click personal.png
click signout.png
wait 3 seconds
```

For anyone who is interested in TagUI, please download it @ https://tagui.readthedocs.io/en/latest/setup.html
