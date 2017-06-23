# What operating systems and versions does the IDE work on?

OSX 10.8+

ubuntu 16.04+ (64 bit)

# Do I have to use the IDE?

Yes. If you are unable to use the IDE due to your operating system not meeting the requirements, please email tech@greyatom.com

# Can IDE works without internet?

No, IDE requires persistence internet connection to work. Without internet it will not work at all.

# How can I add file/folder to my repo using the IDE?

Right click on the folder where you would like to add the file/folder to the Commit.Live IDE. Select Add File/Add Folder and add the name of file/folder. 

# How can I change the font size in the IDE terminal? In the text editor?

`CTRL + +/-` on Ubuntu, `CMD + +/-` on Mac, `ALT + up/down` on Windows.

# How can I do login/logout in IDE?

You can go to File Menu ->Packages-->Commit Live-->Log In/Out 

![ide-log-in-out.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/log-in-out.png)

Once you do that You will see signup page with Github(Use same Github account you used before for Commit.Live ) like below

![ide-github-login.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/ide-github-login.png)

After successfull Github login you should see Terminal and file tree. If you are still unable to login/logout contact at tech@greyatom.com

# When I am trying to login in IDE it is showing "Reauthorization Required" and I am not able to see any authorization button also. How do I login in IDE now ?

This means you have attempted login/logout in IDE to many times in very sort span of time. You screen will look something like this in IDE

![ide-reauthorization.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/ide-reauthorization.png)

To solve this you have to go at `app.commit.live` and do logout and login again. 

![web-logout.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/web-logout.png)

Once above steps are done, now reload(as describe in next step below) the IDE and login again. You should be able to login using your Github account now.

# How can I Reload/Refresh the IDE?

Press `CTRL+SHIFT+P` on Ubuntu, `CMD+SHIFT+P` on Mac, `CTRL+SHIFT+P` on Windows. Now type `Windows:Reload` and hit enter. This will reload the IDE.

![ide-reload.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/ide-reload.png)

If above instruction does not work then quit and restart the IDE. JUST PRESSING THE (X) AT THE TOP OF THE WINDOW AND CLOSING IT IS NOT ENOUGH, you must close the Commit.Live IDE by using the menu options.

# The IDE isn't working for me. The text is "Unable to connect to Commit Live" in the terminal and I can’t type. how can I fix this?

Is there a red Commit Live...reconnect? warning at the bottom right of the terminal? 

![ide-disconnected.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/ide-disconnected.png)

To reconnect click on the red Commit Live...reconnect? 

or

You can also go to Packages-->Commit Live-->Reconnect.

![ide-reconnect.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/ide-reconnect.png)

If you are connected you will see the following bottom right of the terminal in gree color:

![ide-connected](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/ide-connected.png)

# I see '401 - Bad Credentials.' in the terminal while `clive` command. What does this mean, and how can I fix it?

This means your Github Token has been expired. Your Github account need to be reauthorized with Commit.Live account. Contact tech@greyatom.com to know how to fix this.

# `clive submit/test` command showing "It doesn't look like you're in a lesson directory.Please cd into an appropriate directory and try again", how can I fix this?

![cli-github-username-changed.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/cli-github-username-changed.png)

This means one of two things:

1. Your not in lesson directory. Go to lesson directory by runing `cd ~/Workspace/code/<lesson-name>`

or

2. You changed your GitHub username between when your account was created on the IDE server and when you tried to do clive command. You should change your Github username back to what it was at time of Commit.Live signup.

If above solution does not work ask for help from the Commit.live at tech@greyatom.com

# I see 'No passwd entry for user "undefined/username"' and cannot work in the IDE, how can I fix this?

This means one of two things:

1. Your account was not created on the IDE server

or

2. You changed your GitHub username between when your account was created on the IDE server and when you tried to connect.

Then ask for help from the Commit.live at tech@greyatom.com

# Can I use Commit.Live IDE across more than one computer? 

Yes, the Commit.Live IDE can be used across multiple computers.

Instructions to get an already started or already completed lab from one computer to another with the Commit.Live IDE:

1. From the computer that has your latest work, make sure your code has been pushed up to GitHub by using `clive Submit`

The Commit.Live IDE will now have an updated copy of your work, and will automatically remain synced to new computer. If you want to switch back to a different computer, you'll need to follow the above steps again.

# I cloned a lab using `clive open` but can't see it in the file tree. What’s going on?

Are you using the Commit.Live across multiple computers? If so, the latest code may not show up in the Commit.Live IDE. In this case, follow the instructions in the scenario above (Can I use Commit.Live IDE across more than one computer?).

If you are not using multiple computers, Quit and restart the IDE. JUST PRESSING THE (X) AT THE TOP OF THE WINDOW AND CLOSING IT IS NOT ENOUGH, you must close the Commit.Live IDE by using the menu options.

# I installed the IDE and now Atom doesn't work?

The current version of Commit.Live IDE and Atom both can't work together. You need to uninstall Atom editor before installing Commit.Live IDE. Uninstall both Atom and IDE and do the fresh installation of Commit.Live IDE.

# When I click on the Commit.live Open button, it does not open the IDE

If you already have Atom editor installed see the information above(I installed the IDE and now Atom doesn't work). 

Then open the IDE manually and while the IDE is open, click on the Commit.Live open button and it should open in the IDE.

# The 'clive open' command in the IDE is opening the wrong lab

If that is the case, go to app.commit.lve and open the current lessson and copy lesson name form URL. For example if you current lesson is Introduction to Python Intermediate your URL will look like `https://app.commit.live/lesson/intro-to-python-intermediate`

Copy eveything after `https://app.commit.live/lesson/` from URL. In this case it is `intro-to-python-intermediate`

Now command you have to run in IDE terminal would be `clive open intro-to-python-intermediate`. That should open the proper lab.

# My IDE does not show the file tree, how can I get it to appear? 

Quit and restart the IDE. JUST PRESSING THE (X) AT THE TOP OF THE WINDOW AND CLOSING IT IS NOT ENOUGH, you must close the Commit.Live IDE by using the menu options.

# I keep getting a “Reconnecting...” message, how can I fix this?

Most likely your ports are blocked on your network. Let’s try checking for this using the following steps:

In your local Terminal for Ubuntu, Mac and Command Prompt in windows (NOT THE COMMIT.LIVE IDE), 
run: `telnet 35.154.245.107 3000` . After you run command, you'll have to use ctrl + c to kill the connection. Command should return something that looks like this:

```
Trying 35.154.245.107...
Connected to ec2-35-154-245-107.ap-south-1.compute.amazonaws.com.
Escape character is '^]'.
```

If telnet command returns something like: `Could not open connection to the host on port xxxx`, then there is an issue with the your network settings and we recommend trying to use a different network (try using a different netweork and see if it works. You can also try downloading a VPN and connecting through that).

# I am getting "Uncaught typeError: Cannot set property '0' of undefined" and now am not able to type anything in terminal, how can I fix this? 

![0-of-undefined](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/0-of-undefined.png)

This happens when you try to open file using vi/nano (or some similiar file editor command). In this case file format which you are trying to open is not support in teminal. 

To solve this quit and restart the IDE. 

# I am getting "SFTP connection attempt failed" and I am not able to see file tree. How can I get it to appear?

![sftp-connection-failed](https://raw.githubusercontent.com/commit-live-students/help-center/master/img/sftp-connection-failed.png)

There seems to some problem while installing the IDE. To solve this follow below instructions

1. Logout from IDE, that can be done by File Menu ->Packages-->Commit Live-->Log In/Out 
2. Close the IDE.JUST PRESSING THE (X) AT THE TOP OF THE WINDOW AND CLOSING IT IS NOT ENOUGH, you must close the Commit.Live IDE by using the menu options.
3. Open your native terminal (not IDE terminal), run command `rm -rf ~/.atom/.commit-live`
4. Open the IDE again now, sign in using your Github Account again.
5. You should be good to go now.

# My lesson statuses are not updated on web app.commit.Live although I have done `clive open/test/submit` successfully.

Some time you have to reload the web page to see the updated lesson statuses. 


