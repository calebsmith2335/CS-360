# CS-360
Caleb Smith 
8/19/2026

***Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal of this project was to develop a functional Android application that allows users to organize and manage upcoming events. The app was designed for users who need a convenient way to create, view, update, and delete event information from a mobile device. It also includes user account functionality and optional SMS notifications so users can receive reminders about important events.

***What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The application required login and account-creation screens, a home screen displaying saved events, an add-event screen, an event-details screen, and a settings screen for notification preferences. Users can enter an event’s title, date, time, location, and description, then return later to review or modify that information.

I kept users in mind by using consistent colors, readable text, clearly labeled buttons, and predictable navigation throughout the application. Related information and actions were grouped together so users would not have to search for important features. The designs were successful because each screen had a specific purpose and allowed users to complete common tasks without unnecessary steps.

***How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached coding by dividing the application into smaller components instead of attempting to develop every feature at once. I first created the screen layouts and navigation, then added account management, database operations, event controls, and SMS permission handling. Developing one feature at a time made it easier to locate errors and understand how the different components worked together.

I also used reusable methods, consistent naming conventions, and separate classes for different responsibilities. In future projects, I can apply the same incremental strategy by planning the application structure, completing one feature at a time, and testing each component before moving forward.

***How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the application by running it in the Android Emulator and manually completing its primary user tasks. This included creating an account, logging in, adding events, viewing saved information, editing or deleting events, navigating between screens, and testing notification-permission behavior. I also entered incomplete or incorrect information to confirm that the app responded appropriately.

Testing is important because code can compile successfully while the application still contains navigation, data-storage, or usability problems. This process revealed issues that were not always obvious from reviewing the code alone. It also helped me distinguish between problems in my code and performance issues involving Android Studio or the emulator.

***Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of my biggest challenges was getting the Android Emulator to function consistently. At times, emulator performance made it difficult to determine whether an issue came from the application or the development environment. I overcame this by testing smaller sections individually, reviewing error messages, rebuilding the project, and verifying changes one at a time. This required me to adjust my troubleshooting process and avoid assuming that every unexpected result was caused by a coding error.

I also had to determine how to connect several separate screens and features into one complete user experience. Rather than treating each screen as an isolated design, I considered the path a user would follow from logging in to creating and managing an event.

***In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was particularly successful in implementing the app’s event-management functionality and connecting it to the user interface. This component demonstrates my ability to collect user input, store and retrieve event data, display that information, and allow users to update or delete existing records. Bringing the layouts, navigation, database, permissions, and validation together into a functional application demonstrated the mobile development knowledge and experience I gained throughout CS 360.
