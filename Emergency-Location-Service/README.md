Emergency-Location-Service
============

This Task lets others request for your phone's location through an SMS message.

Tasker will look for a "magic word" of your choice, and it will attempt to 
figure your phone's location. It sends an acknowledgement reply at first, 
followed with a link to your location (and discernible latitude and longitude 
coordinates), as well as its accuracy and battery status.

In the event that it cannot lock your location, Tasker will reply your last 
detected location instead after two minutes.

Useful for friends and family to know your location in case of an emergency, 
since this is a pure SMS + GPS solution, which doesn't require your phone to 
connect to the internet (although it'll perform better if it's available).


Usage
------------

- Import as usual.
- Under Triggers, change KEYWORD to the keyword that you want Tasker to 
look out for.
- Save and done!


(TIP: Try texting yourself or have someone else text you to see if the 
keyword works or not! Also, make sure your phone's Location settings 
are enabled!)
