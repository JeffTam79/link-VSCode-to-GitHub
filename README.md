# Guide to Using VSCode with GitHub

## Software to Download
*Please run both softwares as Administrators to your local desktop*
*Please have a GitHub account set up and logged in beforehand*
1. [Microsoft Visual Studio Code (VSCode)](https://code.visualstudio.com/download#)
2. [Git](https://git-scm.com/downloads/win)

# Downloading, Installing, and Setting Up VSCode

## Step 1
Open the Microsoft Visual Studio Code download page. Select the **"System Installer - x64"** option, which is most compatible with Windows 11 systems. (Please check your computer's settings!)

![VSCode Download Page](<Screenshot 2025-10-02 102014.png>)

## Step 2
Save the executable (.exe) file to your downloads folder.

![Save VSCode .exe to Downloads](<Screenshot 2025-10-02 102051.png>)

## Step 3
Once the download is complete, right click the file and select **Run as administrator**.

![Run VSCode as Administrator](<Screenshot 2025-10-02 102114.png>)

## Step 4
Run through the installation prompts and accept all the defaults as shown in the following screenshots.

![Installation Prompt 1 - Select Agree](<Screenshot 2025-10-02 102156.png>) 
![Installation Prompt 2 - Select Next](<Screenshot 2025-10-02 102205.png>) 
![Installation Prompt 3 - Select Next](<Screenshot 2025-10-02 102213.png>) 
![Installation Prompt 4 - Select Next](<Screenshot 2025-10-02 102226.png>) 
![Installation Prompt 5 - Select Install](<Screenshot 2025-10-02 102236.png>) 
![Installation Prompt 6 - Select Finish](<Screenshot 2025-10-02 102314.png>)

## Step 5
VSCode will launch with a welcome page. (*Not shown in the screenshots below*) Please click through all the initial prompts and adjust the GUI to your own liking.

![VSCode Start Page](<Screenshot 2025-10-02 102352.png>)

## Step 6
Next, select the profile icon on the bottom left corner and click on **"Sign in to Sync Settings"**. At this point, you will be prompted to sign in to your GitHub account (please have this ready beforehand!). Once it is clicked on, the web browser will reopen prompting the user to authorize VSCode access to GitHub. Select continue and **"Open Visual Studio Code"** when prompted.

![Sign in to GitHub](<Screenshot 2025-10-02 102716.png>)
![Choose User to Authorize Access](<Screenshot 2025-10-02 102802.png>) 
![Continue to VSCode](<Screenshot 2025-10-02 102752.png>)

# Installing and Setting Up Git
Git needs to be downloaded in order for VSCode to sync directly to GitHub.

## Step 1
Go to the Source Control tab on VSCode (third tab). It will prompt for the download of Git for Windows. Click **open** when prompted to do so. It will then redirect to the official Git download page. 

Make sure to download the Windows x64 option or the option that is most compatible with the operating system.

![Download Git VSCode](<Screenshot 2025-10-02 102829.png>) ![Click Open](<Screenshot 2025-10-02 102840.png>)
![Download x64 Git](<Screenshot 2025-10-02 102910.png>)

## Step 2
Save the download file to the downloads folder. Then, **"Run as administrator"** and follow and accept the default settings in each prompt.

![Save to Downloads](<Screenshot 2025-10-02 102933.png>) 
![Run as administrator](<Screenshot 2025-10-02 103005.png>) 
![Installation Prompt 1 - Select Next](<Screenshot 2025-10-02 103032.png>) 
![Installation Prompt 2 - Select Next](<Screenshot 2025-10-02 103039.png>) 
![Installation Prompt 3 - Select Next](<Screenshot 2025-10-02 103045.png>) 
![Installation Prompt 4 - Select Next](<Screenshot 2025-10-02 103053.png>) 
![Installation Prompt 5 - Select Next](<Screenshot 2025-10-02 103101.png>) 
![Installation Prompt 6 - Select Next](<Screenshot 2025-10-02 103109.png>) 
![Installation Prompt 7 - Select Next](<Screenshot 2025-10-02 103118.png>) 
![Installation Prompt 8 - Select Next](<Screenshot 2025-10-02 103124.png>) 
![Installation Prompt 9 - Select Next](<Screenshot 2025-10-02 103131.png>) 
![Installation Prompt 10 - Select Next](<Screenshot 2025-10-02 103139.png>) 
![Installation Prompt 11 - Select Next](<Screenshot 2025-10-02 103146.png>) 
![Installation Prompt 12 - Select Next](<Screenshot 2025-10-02 103154.png>) 
![Installation Prompt 13 - Select Next](<Screenshot 2025-10-02 103202.png>) 
![Installation Prompt 14 - Select Install](<Screenshot 2025-10-02 103209.png>) 
![Installation Prompt 1 - Select Finish](<Screenshot 2025-10-02 103318.png>)

## Step 3
A Git command line will open. Type the following codes in to establish the username and email that will be used to save the changes to the associated user in the file history of GitHub.

### This command sets your username for all Git repositories on your system. Replace "Your Name" with your actual name.
`git config --global user.name "Your Name"`

### This command sets your email address for all Git repositories on your system. Replace "your.email@example.com" with your actual email address.
`git config --global user.email "your.email@example.com"`

### You can check if your username and email have been set correctly by running these commands:
`git config user.name`
`git config user.email`

*Alternatively, to view all your global Git configurations, use:*
`git config --list --global`

See the below screenshots for examples of what to put:
![Blank Git Command Line](<Screenshot 2025-10-02 103401.png>) 
![Set Username](<Screenshot 2025-10-02 103433.png>) 
![Set Email](<Screenshot 2025-10-02 103456.png>) 
![Verify Information](<Screenshot 2025-10-02 103642.png>)

## Step 4
Return to VSCode and reload the source control screen to confirm that Git is installed.

![Reload](<Screenshot 2025-10-02 103814.png>) 
![Git Installed Properly](<Screenshot 2025-10-02 103733.png>)



1. Open Folder
2. Go to Source Control
3. Initialize Repository
4. Add the remote: https://github.com/JeffTam79/lab5.git
5. Name the remote
6. Pull From: "lab5"
6. Publish Branch
