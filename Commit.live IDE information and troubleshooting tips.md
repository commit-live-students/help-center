# What operating systems and versions does the IDE work on?

OSX 10.8+

ubuntu 16.04+ (64 bit)

Windows 8+ (10 preferred)

# Do I have to use the IDE?

Yes. If you are unable to use the IDE due to your operating system not meeting the requirements, please email tech@greyatom.com

# How can I change the font size in the IDE terminal? In the text editor?

`CTRL + +/-` on Ubuntu, `CMD + +/-` on Mac, `ALT + up/down` on Windows.

# The IDE isn't working for me. The text is "Unable to connect to Commit Live" in the terminal and I can’t type. What do I do?

Is there a red Commit Live...reconnect? warning at the bottom right of the terminal? 

![ide-disconnected.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/ide-disconnected.png)

To reconnect click on the red Commit Live...reconnect? 

or

You can also go to Packages-->Commit Live-->Reconnect.

![ide-reconnect.png](https://raw.githubusercontent.com/commit-live-students/help-center/master/ide-reconnect.png)

If you are connected you will see the following bottom right of the terminal in gree color:

![ide-connected](https://raw.githubusercontent.com/commit-live-students/help-center/master/ide-connected.jpg)

# I see '401 - Bad Credentials.' in the terminal while `clive` command. What does this mean, and how can I fix it?

This means your Github Token has been expired. Your Github account need to be reauthorized with Commit.Live account. Contact tech@greyatom.com to know how to fix this.

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
