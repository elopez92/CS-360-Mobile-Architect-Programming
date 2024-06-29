# CS-360-Mobile-Architect-Programming

## Event-Tracking App Summary

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The Event-Tracking App helps users manage and keep track of their events. The main goals were to:

- Let users log in and create an account.
- Provide a simple way to add, edit, and delete events.
- Save event details in a database that doesn't lose data when the app is closed.
- Notify users about their events on the event day.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

- Make it easy to manage events.
- Ensure event data is always saved.
- Remind users about their events on time.

  
## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
### Login and Signup Screen
- Purpose: Let users log in or create an account.
- Features: Fields for username and password, buttons for login and signup.
- User-Centered Design: Simple layout for easy use.

Event List Screen
- Purpose: Show a list of all upcoming events.
- Features: Buttons to add, edit, and delete events, persistent event storage.
- User-Centered Design: Clear layout with easy-to-find buttons.

Event Details Screen
- Purpose: Let users enter details of a new event or edit an existing one.
- Features: Fields for event name, date, and time, save button.
- User-Centered Design: Straightforward form with clear labels.

Notifications
- Purpose: Notify users on the day of the event.
- Features: Background service to check dates and send notifications.
- User-Centered Design: Ensures users are reminded without opening the app.

UI Design Considerations
The UI design focused on being simple and clear:
- Consistency: Same color schemes and button styles across screens.
- Accessibility: Large buttons and readable fonts.
- Feedback: Visual feedback for button presses and form submissions.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
The coding process was planned and done step by step:
- Planning: Outlined features and UI design before coding.
- Modularity: Wrote code in small parts to make it easier to manage.
- Reusability: Created reusable components for UI and database.
- Testing: Regularly tested each part and the whole app.

Techniques and Strategies
- Version Control: Used Git to track changes and collaborate.
- Debugging: Systematically found and fixed issues.
- Code Reviews: Checked code to ensure quality.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
Testing was done using:
- Integration Tests: Made sure different parts worked together.

Testing is important because it:
- Finds Bugs: Identifies and fixes bugs.
- Ensures Quality: Keeps the app high quality.
- Enhances Reliability: Makes sure the app works well under various conditions.

## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
Some challenges were:

- Database Integration: Made sure data was saved correctly.
- Real-Time Notifications: Implemented a reliable notification system.

## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The Event Notification System was particularly successful:

- Complexity: Managed background tasks and notifications.
- Impact: Made sure users were reminded of their events.
