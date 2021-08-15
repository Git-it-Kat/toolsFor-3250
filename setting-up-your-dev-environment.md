# Welcome to the toolFor-3250 guide!

Steps for Setup:

1) confirm you are an admin on your computer before attempting any setup

2) install GIT

3) install bash

Development Environment:
How to create an administrator account on your computer (Avoid having issues installing files onto your computer by confirming you are downloading and installing as an administrator).

Mac: Instructions for [MacOs](https://support.apple.com/guide/mac-help/set-up-other-users-on-your-mac-mtusr001/mac) 

Microsoft Window: [WindowsOS](https://support.microsoft.com/en-us/windows/create-a-local-user-or-administrator-account-in-windows-10-20de74e0-ac7f-3502-a866-32915af2a34d)

Update your browser:
 links for [Firefox](https://support.mozilla.org/en-US/kb/update-firefox-latest-release) and [[Chrome](https://www.google.com/chrome/update/)](https://www.google.com/chrome/)

Note concerning your Computer's User Account Name:

In development, you will generally want to avoid using spaces in file and folder names with spaces in them because they can cause issues. Some tools can malfunction when dealing with such files and folders because they are looking for a single-word name.
This applies to your computer's user account as well. If your user account has a space in it, such as "Jane Doe", then create a new user account at this time to use for your course that does not have a space in it, such as "JaneDoe". Make sure to set it up as an administrative account. This will prevent potential issues later in the course.

# Setting up Git on your computer

For Windows:

Download the executable installer for Git from this link: [https://git-scm.com/download/win.](https://git-scm.com/download/win)
Run the installer and accept all the default values by pressing "Next". 
At the final screen of the installation wizard, before clicking on "Finish", make sure to check the box for "Launch Git Bash" (and uncheck the box for "View Release Notes") then click "Finish". 


For macOS:

Note: You will use the Terminal application to install Homebrew for macOS, which you will then use to install Git.
 
To install Homebrew, copy the following text command, paste it into your Terminal window, and press enter:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"


Note: If you are asked for a password, be aware that you will **not** be able to see anything being entered into the terminal when you type in your password for security reasons.


Homebrew should now be installed! Next, use Homebrew to install Git by entering this command into your Terminal:

brew install git

Once the installation is complete, close your Terminal window and open a new one. 

**Install Git Bash**

With Git installed, Windows users can also now use Bash by using Git Bash.
 
By default, Git Bash is installed so that you can right click on or inside a folder in File Explorer and open Git Bash at that location. 

In macOS, you can right click on a folder and choose "New Terminal at Folder". If you do not see this option, follow the instructions at this link to enable it: [Launch an OS X Terminal Window from a Specific Folder](https://lifehacker.com/launch-an-os-x-terminal-window-from-a-specific-folder-1466745514).

# RESOURCES:

# [course on web development html and python](https://youtu.be/zFZrkCIc2Oc)

# [w3schools](https://www.w3schools.com/)

# [Javascript.info](https://javascript.info/)

# [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

# [stack**overflow**](https://stackoverflow.com/)

# [JS library](https://www.khanacademy.org/computing/computer-programming/html-css-js/using-js-libraries-in-your-webpage/a/whats-a-js-library)
# [Markup Validator w3c](https://validator.w3.org/)
