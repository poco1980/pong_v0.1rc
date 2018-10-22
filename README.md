*****THIS IS A WORK IN PROGRESS*****



++++Prerequisites++++++

Python 3.6.6
Kivy 1.10.1
Passenger 5.3.5

+++++++++++++++++++++++



This is the start of something that will be added to a webapp/site I'm working on

For starters, this will be exclusive to Linux. I know it will be on a Ubuntu with
Apache.

I plan on using Passenger done by Phusion(They are here on Github as well).

Their instructions to install are located on their site(http://www.phusionpassenger.com)
and here on Git.

This project also uses Kivy(https://kivy.org) and here on Github

Installation instructions are on site or here on Github as well.

For those of you who don't know where the conf file goes it goes in your
/etc/apache2/sites-available directory.

After you do that use the "a2ensite pong" to enable it

I am using Python 3.6.6.

I had to edit some things in Ubuntu to use Python 3.6.6 as default.

Now I know when you go to the directory that you cloned this to and "python main.py"
It shows a uncompleted Pong board

Now, if you followed everything on the deployment tutorial on Passenger's site, it should be working,
but I'm having an issue where it crashes.
