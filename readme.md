Intro
=====
These are the automator scripts that I have created to make my every day life easier

Services
========
All of the below are intended to be used as services.  That way the are accessible from any program.  In fact the way I use them is to bind a keyboard short cut to the workflow.  And being a service this causes the keyboard shortcut to be available no matter what the active program is.

Add keyboard shortcuts to a service (snow leopard):

1. Open System Preferences
1. Go to Keyboard (in Hardware)
1. Go to Keyboard Shortcuts
1. Choose "Services" on the left side
1. Scroll to the task (usually in general)
1. Click to add a shortcut (mine are always ctrl+alt+cmd and a letter)

Fast User Switching (ctrl+alt+cmd+space)
-------------------
I hate the normal fast user switching menu.  I don't want to have to waste Menu space on the icon and I don't want to have to find "Login Menu" when I want to lock my screen.

All this does is run the shell command that suspends the current UI session.  Thereby returning the user to the login screen, but keeping them logged in.

Task Update (ctrl+alt+cmd+t)
----------------------------
At work, in addition to meetings where we must talk about our status, we have to send an email to a distro list containing the status of individual tasks.  That way a bot (or possibly a person, not sure) can take the info and update an MS Project chart.  And as annoying as that sounds it is still better then having to use rally. :)

But since I am lazy and often get the email format wrong, I have created this script which will prompt for the important bits, format the email, and open mail with the new message.