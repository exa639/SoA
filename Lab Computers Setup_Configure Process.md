Lab Computers Setup/Configure Process

0) Enter BIOS and assign password: 3314@UmSoa!and setup time.

1) Place Windows 11 USB Flash Drive.

2) Turn on computer and hit F2.

3) Erase Hard drive and create New.

4) Select United States.

5) Select US keyboard.

6) Skip.

7) Shift+F10 to get CMD prompt and enter: start ms-cxh:localonly

8) Create soait user.

9) Rename Computer.

9) Enable Administrator, Re-start computer and login with Administrator.

11) Register Mac Address in NAC.MIAMI.EDU.

12) Create computer in CGCENTdomain specific OU.

3) Enable Wired Auto Config.

4) For 802.1x, select User Authentication, SAVE.

5) Delete profile sor soait.Enable Administrator account.

6) Log out soait, Login as Administrator.

7) Enable Power Option to NEVER

Turn off the Display: Never

Put the computer to sleep: Never

Change Advance Power Settings: Turn off Hard Drive: Never

8) Apply All Windows Updates

9) Copy Mdot2\Software to C:\

10) Go to Terminal as Administrator.

Type

cd c:\software

Set-ExecutionPolicy -Scope Process -ExecutionPolicy bypass

.\Install-Rhino.ps1

11) Install Crowdstrike

12) Run Classroom

13) gpupdate /force