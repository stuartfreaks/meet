This app helps users find meet ups in their city or area.

This application will utilise AWS | Google Calendar API | Google OAuth and AWS Lambda Access Keys

It was created using:

- React.js

A User Can Do The Following:

Feature 2: Show / Hide Event Details

- As a User I should be able to Show | Hide and events details

• Scenario 1: An event element is collapsed by default
▪ Given: The app is loaded.
▪ When: A list of events has been served to the user.
▪ Then: The event details are not visible to the user.

• Scenario 2: User can expand an event to see its details
▪ Given: The list of events is loaded
▪ When: The user clicks on the “Show details” button of the event.
▪ Then: The event is expanded to show details

• Scenario 3: User can collapse an event to hide its details
▪ Given: An event has been expanded to show details.
▪ When: The user clicks on the “Hide details” button of the event.
▪ Then: The details of the event are hidden.

Feature 3 Specify Number of Events

- As a User I should be able to specify the number of events I would like to see So that he can delivery less search results

• Scenario 1: When user hasn’t specified a number, 32 is the default number
▪ Given: The app is loaded. ▪ When: The user hasn’t specified the number of events.
▪ Then: A list of 32 events is served to the user. • Scenario 2: User can change the number of events they want to see ▪ Given: A list of events has been served to the user.  
▪ When: The user specifies the number of events to be loaded.
▪ Then: A list with the specified number of events is served to the user.

Feature 4 Use App Offline

- As a User I should be able to use the app offline So that I can use it in train tunnels and on any airline

• Scenario 1: Show cached data when there’s no internet connection
▪ Given: There is no internet connection.
▪ When: The user browses through the data.
▪ Then: The user is served cached data of previously loaded events.  
 • Scenario 2: Show error when user changes the settings (city, time range)
▪ Given: There is no internet connection.
▪ When: The user changes settings.  
 ▪ Then: The app returns an error to the user.

Feature 5 Data Visualization

- As a user I should be able to chart upcoming events in the city So that they can plan their Schedule

• Scenario 1: Show a chart with the number of upcoming events in each city
▪ Given: The app is loaded.
▪ When: When the user clicks on a city.
▪ Then: A chart with the number of events in a city is served to the user
