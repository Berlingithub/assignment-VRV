Admin Dashboard - Role-Based Access Control (RBAC) 


To evaluate your creativity, understanding, and technical skills in building a Role-Based Access Control (RBAC) User Interface.

Table of Contents
    Project Overview
    Features
    Technologies Used
    Project Structure
    State Management
    Routing & Permissions
    How to Run the Project

Project Overview
The Admin Dashboard enables the following functionalities:

Admin Features
    View and manage users and creators.
    Assign or toggle roles
    Add new roles
    Add new members to the system.
Creator Features
    Create new posts.
    View and manage past posts.
User Features
    View posts.
    Follow and unfollow creators.


Features
    Admin Features
        Role Management: Toggle user roles between "user" and "creator."
        User Management: Add or remove users from the system.
    Creator Features
        Post Creation: Write, edit, and manage posts using TinyMCE text editor.
        Post History: View previously published posts.
    User Features
        Post Viewing: Browse posts created by creators.
        Follow Creators: Follow or unfollow creators.
    

   Shared Features
            Protected Routes: Ensure users can only access authorized pages based on their roles.
            Optimized UI: Includes a shimmer loading effect and debounce for smooth input handling.
            Responsive Design: Features a mobile-friendly, toggleable sidebar 

Technologies Used
    React: For building UI components.
    React Context API: For managing global state (e.g., user roles, posts).
    React Router: For handling navigation and protected routes.
    Reducer: For centralized state management.
    Tailwind CSS: For styling components and ensuring a responsive layout.
    TinyMCE: A rich text editor for creating posts.
    Shimmer Effect: For skeleton loading during data fetching.
    Debounce: For efficient handling of input events like search or form submissions.           





State Management
    The project uses React Context API and Reducer for efficient state management:

    Context API: Manages global states such as user roles, posts, and login status, avoiding the need for prop drilling.
    Reducer: Centralizes state updates like adding or deleting users, toggling roles, and managing posts.

 
Here’s the rewritten version of your document, formatted and refined for easy readability and professionalism:


Admin Features
View and manage users and creators.
Assign or toggle roles between users and creators.
Add new members to the system.
Creator Features
Create new posts.
View and manage past posts.
User Features
View posts.
Follow and unfollow creators.
Features
Admin Features
Role Management: Toggle user roles between "user" and "creator."
User Management: Add or remove users from the system.
Creator Features
Post Creation: Write, edit, and manage posts using TinyMCE text editor.
Post History: View previously published posts.
User Features
Post Viewing: Browse posts created by creators.
Follow Creators: Follow or unfollow creators.
Shared Features
Protected Routes: Ensure users can only access authorized pages based on their roles.
Optimized UI: Includes a shimmer loading effect and debounce for smooth input handling.
Responsive Design: Features a mobile-friendly, toggleable sidebar.
Technologies Used
React: For building UI components.
React Context API: For managing global state (e.g., user roles, posts).
React Router: For handling navigation and protected routes.
Reducer: For centralized state management.
Tailwind CSS: For styling components and ensuring a responsive layout.
TinyMCE: A rich text editor for creating posts.
Shimmer Effect: For skeleton loading during data fetching.
Debounce: For efficient handling of input events like search or form submissions.

State Management
The project uses React Context API and Reducer for efficient state management:

Context API: Manages global states such as user roles, posts, and login status, avoiding the need for prop drilling.
Reducer: Centralizes state updates like adding or deleting users, toggling roles, and managing posts.
Routing & Permissions
Protected Routes:
Ensures users can only access pages they’re authorized for, based on roles. Unauthorized users are redirected to an "Unauthorized" page.

Role-Based Access Control (RBAC):

Admin: Manage users and their roles (user/creator).
Creators: Create and view posts.
Users: View posts and follow creators.   

How to Run the Project
Prerequisites
Ensure you have the following installed:

Node.js
npm or yarn
Installation
Clone the repository:
git clone https://github.com/Berlingithub/Assignment-VRV
cd VRV assignment 
Install dependencies:
npm install
# or
yarn install
Start the development server:
npm start
# or
yarn start

Open your browser:
Visit http://localhost:3000.


Ensure you have the following installed:

Node.js
npm or yarn
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Berlingithub/Assignment-VRV
cd VRV-security-assignment
Install dependencies:

bash
Copy code
npm install
# or
yarn install
Start the development server:

bash
Copy code
npm start
# or
yarn start
Open your browser:
Visit http://localhost:3000.




Conclusion
This application demonstrates Role-Based Access Control (RBAC) in React through features like user management, post creation, and efficient state management using Context API and Reducer. Designed for scalability and user-friendliness, it utilizes modern frontend practices to deliver an optimized and responsive experience.