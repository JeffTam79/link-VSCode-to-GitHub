# Guide to Using VSCode with GitHub

## Software to Download
*Please run both softwares as Administrators to your local desktop*
*Please have a GitHub account set up and logged in beforehand*
1. [Microsoft Visual Studio Code (VSCode)](https://code.visualstudio.com/download#)
2. [Git](https://git-scm.com/downloads/win)

# Downloading, Installing, and Setting Up VSCode

## Step 1
Open the Microsoft Visual Studio Code download page. Select the **"System Installer - x64"** option, which is most compatible with Windows 11 systems. (Please check your computer's settings!)

<img src="img/Screenshot 2025-10-02 102014.png" alt="VSCode Download Page">

## Step 2
Save the executable (.exe) file to your downloads folder.

<img src="img/Screenshot 2025-10-02 102051.png" alt="Save VSCode .exe to Downloads">

## Step 3
Once the download is complete, right click the file and select **Run as administrator**.

<img src="img/Screenshot 2025-10-02 102114.png" alt="Run VSCode as Administrator">

## Step 4
Run through the installation prompts and accept all the defaults as shown in the following screenshots.

<img src="img/Screenshot 2025-10-02 102156.png" alt="Installation Prompt 1 - Select Agree">
<img src="img/Screenshot 2025-10-02 102205.png" alt="Installation Prompt 2 - Select Next">
<img src="img/Screenshot 2025-10-02 102213.png" alt="Installation Prompt 3 - Select Next">
<img src="img/Screenshot 2025-10-02 102226.png" alt="Installation Prompt 4 - Select Next">
<img src="img/Screenshot 2025-10-02 102236.png" alt="Installation Prompt 5 - Select Install">
<img src="img/Screenshot 2025-10-02 102314.png" alt="Installation Prompt 6 - Select Finish">

## Step 5
VSCode will launch with a welcome page. (*Not shown in the screenshots below*) Please click through all the initial prompts and adjust the GUI to your own liking.

<img src="img/Screenshot 2025-10-02 102352.png" alt="VSCode Start Page">

## Step 6
Next, select the profile icon on the bottom left corner and click on **"Sign in to Sync Settings"**. At this point, you will be prompted to sign in to your GitHub account (please have this ready beforehand!). Once it is clicked on, the web browser will reopen prompting the user to authorize VSCode access to GitHub. Select continue and **"Open Visual Studio Code"** when prompted.

<img src="img/Screenshot 2025-10-02 102716.png" alt="Sign in to GitHub">
<img src="img/Screenshot 2025-10-02 102802.png" alt="Choose User to Authorize Access">
<img src="img/Screenshot 2025-10-02 102752.png" alt="Continue to VSCode">

# Installing and Setting Up Git
Git needs to be downloaded in order for VSCode to sync directly to GitHub.

## Step 1
Go to the Source Control tab on VSCode (third tab). It will prompt for the download of Git for Windows. Click **open** when prompted to do so. It will then redirect to the official Git download page. 

Make sure to download the Windows x64 option or the option that is most compatible with the operating system.

<img src="img/Screenshot 2025-10-02 102829.png" alt="Download Git VSCode">
<img src="img/Screenshot 2025-10-02 102840.png" alt="Click Open">
<img src="img/Screenshot 2025-10-02 102910.png" alt="Download x64 Git">

## Step 2
Save the download file to the downloads folder. Then, **"Run as administrator"** and follow and accept the default settings in each prompt.

<img src="img/Screenshot 2025-10-02 102933.png" alt="Save to Downloads">
<img src="img/Screenshot 2025-10-02 103005.png" alt="Run as administrator">
<img src="img/Screenshot 2025-10-02 103032.png" alt="Installation Prompt 1 - Select Next">
<img src="img/Screenshot 2025-10-02 103039.png" alt="Installation Prompt 2 - Select Next">
<img src="img/Screenshot 2025-10-02 103045.png" alt="Installation Prompt 3 - Select Next">
<img src="img/Screenshot 2025-10-02 103053.png" alt="Installation Prompt 4 - Select Next">
<img src="img/Screenshot 2025-10-02 103101.png" alt="Installation Prompt 5 - Select Next">
<img src="img/Screenshot 2025-10-02 103109.png" alt="Installation Prompt 6 - Select Next">
<img src="img/Screenshot 2025-10-02 103118.png" alt="Installation Prompt 7 - Select Next">
<img src="img/Screenshot 2025-10-02 103124.png" alt="Installation Prompt 8 - Select Next">
<img src="img/Screenshot 2025-10-02 103131.png" alt="Installation Prompt 9 - Select Next">
<img src="img/Screenshot 2025-10-02 103139.png" alt="Installation Prompt 10 - Select Next">
<img src="img/Screenshot 2025-10-02 103146.png" alt="Installation Prompt 11 - Select Next">
<img src="img/Screenshot 2025-10-02 103154.png" alt="Installation Prompt 12 - Select Next">
<img src="img/Screenshot 2025-10-02 103202.png" alt="Installation Prompt 13 - Select Next">
<img src="img/Screenshot 2025-10-02 103209.png" alt="Installation Prompt 14 - Select Next">
<img src="img/Screenshot 2025-10-02 103318.png" alt="Installation Prompt 15 - Select Finish">

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

<img src="img/Screenshot 2025-10-02 103401.png" alt="Blank Git Command Line">
<img src="img/Screenshot 2025-10-02 103433.png" alt="Set Username">
<img src="img/Screenshot 2025-10-02 103456.png" alt="Set Email">
<img src="img/Screenshot 2025-10-02 103642.png" alt="Verify Information">

## Step 4
Return to VSCode and reload the source control screen to confirm that Git is installed.
 
<img src="img/Screenshot 2025-10-02 103733.png" alt="Reload">
<img src="img/Screenshot 2025-10-02 103814.png" alt="Git Installed Properly">

# Setting up VSCode with GitHub Repository Connection
Make sure there is a project folder located on the computer and know it's directory path.

## Step 1
Select "Open Folder" and find the project folder.

<img src="img/Screenshot 2025-10-02 103834.png" alt="Open Folder">
<img src="img/Screenshot 2025-10-02 104059.png" alt="Select Folder">
<img src="img/Screenshot 2025-10-02 104116.png" alt="Folder Open in VSCode">

## Step 2
In Source Control, select Initialize Repository. Select the three elipses by "Changes" to open a drop down menu. Then select "Remote" and "Add Remote."

<img src="img/Screenshot 2025-10-02 104129.png" alt="Initialize Repository">

## Step 3
Add a remote (connect to GitHub repository).

<img src="img/Screenshot 2025-10-02 104328.png" alt="Add Remote">

## Step 4
When prompted, go to the GitHub repository of your choosing. Then, click the "Code" drop down and copy the link shown below. Then, paste it into the VSCode prompt. 

VSCode will then prompt to rename the remote. Keep it simple.

<img src="img/Screenshot 2025-10-02 104351.png" alt="Copy GitHub Link">
<img src="img/Screenshot 2025-10-02 104454.png" alt="Paste GitHub Link">
<img src="img/Screenshot 2025-10-02 104516.png" alt="Rename the Remote">

## Step 5
Next, we need to sync or pull from the GitHub repository to make sure VSCode has all of GitHub's changes to avoid errors later. Select the three elipses next to "Changes" and select "Pull, Push" and then "Pull from...".

<img src="img/Screenshot 2025-10-02 104539.png" alt="Pull From">

## Step 6
Next, VSCode will prompt the user to select a branch. Select the option with the "Main" branch.

<img src="img/Screenshot 2025-10-02 104605.png" alt="Select Main Branch">

## Step 7
Select "Publish Branch"

<img src="img/Screenshot 2025-10-02 104624.png" alt="Publish Branch">

# Syncing Changes on VSCode with GitHub

## Step 1
Any changes on VSCode will need to be synced with GitHub. It is also good practice to make notes of what was done. Under the "Changes" section, add a comment noting the changes done. Make sure to copy this comment.

Then, select "Commit" and select "Yes" when a pop-up appears.

Afterwards, paste the comment from the "Commit" and select "Sync Changes." Press Okay, but make sure the pop-up message states that changes will be pushed to the "main" branch.

<img src="img/Screenshot 2025-10-02 104743.png" alt="Commit">
<img src="img/Screenshot 2025-10-02 104754.png" alt="Yes">
<img src="img/Screenshot 2025-10-02 104812.png" alt="Sync">
<img src="img/Screenshot 2025-10-02 104822.png" alt="Ok">

## Step 2
Refresh the GitHub repository page to see the changes.

<img src="img/Screenshot 2025-10-02 104836.png" alt="Confirm Changes">

# Summary of the Above Steps
1. Open Folder
2. Go to Source Control
3. Initialize Repository
4. Add the remote: https://github.com/JeffTam79/lab5.git
5. Name the remote
6. Pull From: "lab5"
6. Publish Branch
