Set Home Location (If there is no previous event within 6 or so hours, assume you are coming from home)

Get Location of Event from Calendar (Alternately Text Box to add location)
Write location from Text box if there is no location for the event)

Get location of Previous event. (Writable Text Box to override this in case you are coming from somewhere else)

Pass Previous event to goole maps api as Source:
Pass Next event to google maps api as Destination:

Set (Arrive by) Time to be 7 Minutes before the next event:

Set Travel Time Options:
Drive
Transit
Bike
Walk

Get directions Back

Write Duration as a new Calendar event
Put short description (F to Church Ave…) and link to Directions in the comments for that event.

Continuously poll the Maps API for updates (Service Updates, Traffic changes etc… and update the event accordingly)

Maybe overlay the whole interface as an add/edit event window over a render of the google Calendar GUI 
or else make a newui for this
