
# React MST Coding Questions

This document contains three simple React coding tasks based on the topics covered in class such as React Hooks, API calls, and Routing.

Students will complete **two types of submissions**:

1. **Hard Copy Submission (Written Explanation)**
2. **GitHub Repository Submission (Code Implementation)**

Please read the instructions carefully before starting.

---

# Submission Instructions

## 1️⃣ Hard Copy Submission (Written)

Students must submit a **handwritten or printed explanation** of the code for the tasks given below.

You **DO NOT need to write full code** in the hard copy.

Instead, you must explain:

• The **folder structure** of the React application  
• **How the code works internally**  
• **Which React hooks are used** and why  
• The **logic behind the implementation**  
• **What problems could arise** if the code is written poorly or structured incorrectly  
• **How the code can be improved** to follow better React practices

Example points students can discuss:

- Separation of components
- Proper state management
- Avoiding unnecessary re-renders
- Handling API errors
- Code modularity and reusability

This submission checks your **conceptual understanding of React**.

---

## 2️⃣ GitHub Code Submission

Students must implement the solution and upload the **working React project to GitHub**.

Steps:

1. Create the React project using **Vite**
2. Implement the required functionality
3. Push the project to **GitHub**
4. Submit the **GitHub repository link in the Google Form** provided

The Google Form will contain **two submission fields**:

• GitHub Repository Link  
• Confirmation of Hard Copy Submission

This submission checks your **practical coding ability**.

---

# Question 1 – Counter Application using useState

## Task

Create a simple React Counter Application that:

- Displays a number on the screen
- Has two buttons: Increment and Decrement
- Updates the number when buttons are clicked

## Example Folder Structure

src/
 ├── components/
 │    └── Counter.jsx
 ├── App.jsx
 └── main.jsx

## Concepts Covered

- React Functional Components
- useState Hook
- Event Handling

## Logic Explanation

- The useState hook stores the counter value.
- When the button is clicked, the state is updated.
- React automatically re-renders the component when the state changes.

## Functionalities

- Increment the value
- Decrement the value
- UI updates dynamically

## Possible Improvements

- Add a Reset button
- Add validation for minimum/maximum values
- Separate logic into reusable components

---

# Question 2 – Fetch Data from API using useEffect

## Task

Create a React component that fetches user data from an API and displays it in a list.

API:

https://jsonplaceholder.typicode.com/users

Display:

- Name
- Email

## Example Folder Structure

src/
 ├── components/
 │    └── Users.jsx
 ├── App.jsx
 └── main.jsx

## Concepts Covered

- useEffect Hook
- API Calls (fetch or axios)
- useState for storing API data

## Logic Explanation

- When the component loads, useEffect runs.
- An API request is sent to fetch user data.
- The received data is stored in state.
- The data is displayed using the map() function.

## Functionalities

- Fetch external data
- Dynamically render list of users

## Possible Improvements

- Add loading state
- Add error handling
- Move API logic to a separate service file

---

# Question 3 – React Routing Example

## Task

Create a React application with two pages:

- Home Page
- About Page

Use React Router to navigate between them.

Add navigation links.

## Example Folder Structure

src/
 ├── pages/
 │    ├── Home.jsx
 │    └── About.jsx
 ├── App.jsx
 └── main.jsx

## Concepts Covered

- React Router
- Routes
- Route
- Link

## Logic Explanation

- React Router manages navigation between pages.
- Link component changes the route without reloading the page.
- Based on the route path, the corresponding component is rendered.

## Functionalities

- Navigation between pages
- Single Page Application behavior (no full reload)

## Possible Improvements

- Add a 404 Not Found page
- Implement lazy loading for routes
- Add protected routes

---

# Evaluation Criteria

Students will be evaluated based on:

• Understanding of React concepts  
• Explanation of folder structure  
• Logic explanation  
• Code quality in GitHub submission  
• Suggested improvements and problem analysis
