## Meet

## Feature 1:  Filter Events By City
## Scenarios 1: When user hasn't searched for a city, show upcoming events from all cities
Given the user hasn't searched for any city, 
When the user views the list of upcoming events, 
Then events from all cities are displayed.

## Scenarios 2: User should see a list of suggestions when they search for a city 
Given the user is on the event search page,
When the user starts typing in the city search box,
Then a list of city suggestion should appear.

## Scenarios 3: User can select a city from the suggested list.
Given the user is on the event search page,
When the user selects a city from the suggested list,
Then the events from the selected city are displayed.


## Feature 2:Show/ Hide Events Details  
## Scenarios 1: An event element is collapsed by default
Given an event is listed on the page,
When the user views the event list,
Then the event details are initially collapsed.

## Feature 3:Specify Number of Events
## Scenarios 1: When user hasn’t specified a number, 32 events are shown by default
Given the user hasn’t specified the number of events to display,
When the user views the list of upcoming events,
Then 32 events are displayed by default.

## Feature 4: Use the App When Offline
## Scenarios 1: Show cached data when there’s no internet connection
Given the user has previously used the app and cached data is available,
When the user tries to access the event list without internet connection,
Then the app displays the events using the cached data.

## Feature 5: Add an App Shortcut to the Home Screen
## Scenarios 1: User can install the meet app as a shortcut on their device home screen
Given the user is on the app's home screen,
When the user accesses the browser's menu and selects the "Add to Home Screen" option,
Then a shortcut to the app is added on the device's home screen.


## Feature 6: Display Charts Visualizing Event Details
## Scenarios 1: Show a chart with the number of upcoming events in each city
Given the user is viewing the event statistics section,
When the user accesses the chart for upcoming events by city,
Then a chart is displayed showing the number of events in each city.


