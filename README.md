As a user,
I should be able to able to expand the event upon clicking on it
So that I can see all the details of that event
Feature 2- Ability to expand and collapse event details Scenario 
1. event element is collapsed by default 
•	Given user has not searched for events 
•	When the user has not clicked on any event 
•	Then the event details are collapsed 
2. User can expand an event to see its details 
•	Given user wants to see more info about a specific event 
•	When the user clicks on the specific event 
•	Then the event expands for more information 
3. User can collapse an event to hide its details 
•	Given user no longer wants to see an event detail 
•	When a user clicks on the expanded event details 
•	Then the event details collapse

As a user,
I should be able to able to set the number of events shown as a list
So that I can see just that many event info by default
FEATURE 3: SPECIFY NUMBER OF EVENTS
1.	Scenario 1: When user hasn’t specified a number, 32 is the default number
•	Given user has not specified the number of events they want to see 
•	When a user start searching by a location 
•	32 events are listed by default
2.	Scenario 2: User can change the number of events they want to see
•	Given user wants to specify the number of events they want to see 
•	When the user clicks to change the quantity 
•	Then the app generates the quantity they have selected

As a user,
I should be able to able to use the app if internet is unavailable 
So that I can see the event info
FEATURE 4: USE THE APP WHEN OFFLINE
Scenario 1: Show cached data when there’s no internet connection
•	Given: The user does not have internet connection 
•	When: The user tries to use the app 
•	Then: the app uses cached data to populate events
Scenario 2: Show error when user changes the settings (city, time range)
•	Given: The user tries to change settings
•	When: The user attempts to make the change 
•	Then: An error message is displayed informing that the internet is not available

As a user,	
I should be able to able to see a list view of upcoming events sorted by date time
So that I can have an organized view of the event which makes it easy to make plans ahead
FEATURE 5: DATA VISUALIZATION
Scenario 1: Show a chart with the number of upcoming events in each city
•	Given: The user wants to see upcoming events 
•	When: The user clicks to view the chart of upcoming events 
•	Then: A chart of upcoming events is displayed with the number of events for each city


