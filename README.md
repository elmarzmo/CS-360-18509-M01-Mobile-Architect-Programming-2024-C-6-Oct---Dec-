# CS-360-18509-M01-Mobile-Architect-Programming-2024-C-6-Oct---Dec-


Requirements and Goals of the App:
The app was designed to track items in a warehouse, ensuring efficient inventory management. The application needed to include the following features:

A database with at least two tables: one for storing inventory items and another for user logins and passwords.
A login screen that also supports user registration for first-time users.
A screen with a grid displaying all items in the inventory.
Mechanisms for users to add and remove items from the inventory.
Functionality to increase or decrease the quantity of specific items.
Notifications to alert users when any item's inventory count reaches zero.
These features were intended to address user needs for a streamlined, user-friendly interface to manage warehouse inventory effectively.

Screens and Features Supporting User Needs:
To support user needs, the app included a login screen that securely managed user information. The inventory screen displayed data in a grid format, making it easy to view, edit, and manage items. The database design ensured accurate data storage and retrieval, while notifications provided critical updates to prevent stockouts. The design emphasized simplicity and clarity, keeping the user’s workflow in mind. The success of these designs lay in their ability to provide essential functionality in an intuitive and visually accessible manner.

Approach to Coding the App:
The coding process emphasized simplicity and clarity, with detailed comments to explain the purpose and functionality of each section. Modular programming techniques were used to ensure each feature was implemented as a self-contained unit, making the codebase more manageable and adaptable for future updates. These strategies can be applied to future projects to enhance code readability, maintainability, and scalability.

Testing for Functionality:
To ensure functionality, I developed multiple test cases simulating user actions, such as logging in, adding items, and receiving notifications. 
This iterative testing process was crucial to identifying bugs and verifying that the app worked as intended. It revealed opportunities to optimize database interactions and refine the notification system for better responsiveness.

Innovations to Overcome Challenges:
One significant challenge was working in Android Studio to implement SMS notifications. Specifically, locating and configuring the appropriate file to grant permissions for SMS notifications required careful research and experimentation. To address this, I explored Android's permission system and adjusted the AndroidManifest.xml file to include the necessary permissions. 
