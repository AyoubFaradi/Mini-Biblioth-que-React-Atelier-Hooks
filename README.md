# Mini Bibliothèque React -- Atelier Hooks

## 1. Project Overview

This project was developed as part of the **Advanced Web Development**
module.\
The purpose of this workshop is to learn how to use **React Hooks**,
particularly `useState` and `useEffect`, in order to create dynamic and
interactive user interfaces.

The application represents a **mini digital library** where users can:

-   select a book
-   add likes to a book
-   reset the number of likes
-   automatically update the browser tab title according to the selected
    book

This project introduces the fundamental concepts of **state management
in React** and the use of effects after rendering.

------------------------------------------------------------------------

## 2. Learning Objectives

The main objectives of this project are:

-   Understand the concept of **React Hooks**
-   Use **useState** to manage component state
-   Use **useEffect** to execute code after rendering
-   Build **reusable React components**
-   Structure a React application properly

------------------------------------------------------------------------

## 3. Technologies Used

The following technologies were used in this project:

-   React
-   Vite
-   JavaScript
-   CSS
-   Node.js

------------------------------------------------------------------------

## 4. Project Structure

The project follows the structure below:
<img width="313" height="510" alt="image" src="https://github.com/user-attachments/assets/c8553af0-80ce-4705-89a9-dd6e8ccb3745" />


ATELIER-REACT-HOOKS │ ├── node_modules ├── public │ ├── src │ ├── assets
│ ├── components │ │ └── BookLike.jsx │ │ │ ├── App.jsx │ ├── App.css │
├── index.css │ └── main.jsx │ ├── index.html ├── package.json ├──
package-lock.json ├── README.md └── vite.config.js

Description of the main files:

  File           Description
  -------------- -----------------------------------------------------------
  App.jsx        Main component responsible for managing the selected book
  BookLike.jsx   Component that displays the book and manages likes
  main.jsx       Entry point of the React application
  index.css      Global styles for the application

------------------------------------------------------------------------

## 5. Installation

### 1. Clone the repository

git clone
https://github.com/AyoubFaradi/Mini-Biblioth-que-React-Atelier-Hooks.git

### 2. Navigate to the project folder

cd Mini-Biblioth-que-React-Atelier-Hooks

### 3. Install dependencies

npm install

### 4. Run the development server

npm run dev

Then open the application in your browser:

http://localhost:5173

------------------------------------------------------------------------

## 6. Application Features

### 6.1 Book Selection

In `App.jsx`, the user can select a book using multiple buttons.

Each button updates the **state variable** that stores the selected
book.\
When the state changes:

-   the interface updates automatically
-   the new selected book is displayed

This demonstrates how **React automatically re-renders components when
state changes**.

------------------------------------------------------------------------

### 6.2 Like Counter

The `BookLike.jsx` component contains a **like counter**.

The counter is managed using the `useState` hook.

Available actions:

-   **Like button**: increases the number of likes
-   **Reset button**: resets the counter to zero

React updates the interface automatically when the state changes.

------------------------------------------------------------------------

### 6.3 Dynamic Page Title

The `useEffect` hook is used to update the browser tab title whenever
the selected book changes.

Example:

Livre : Clean Code

This demonstrates how **React effects run after component rendering**.

------------------------------------------------------------------------

## 7. Screenshots

### BookLike Component Code

src/components/BookLike.jsx

Image:

<img width="1190" height="722" alt="image" src="https://github.com/user-attachments/assets/8ced2cd3-435b-4bd3-981d-868fc91d6723" />

------------------------------------------------------------------------

### App Component Code

src/App.jsx

Image:

<img width="1181" height="822" alt="image" src="https://github.com/user-attachments/assets/331f351f-cfc8-4614-a2bf-2c27ed3f6af1" />

------------------------------------------------------------------------

### Global CSS Styles

src/index.css

Image:

<img width="1172" height="761" alt="image" src="https://github.com/user-attachments/assets/75d7de1d-7774-4306-bc53-3dfcfaffc865" />

## Resultat

Image:

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/5ecc58e5-825d-45d8-a72d-9b1670b35b6d" />

<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/bce51bf5-35ec-4fae-9363-d996bbff29d7" />

<img width="1918" height="1008" alt="image" src="https://github.com/user-attachments/assets/289172b2-a046-483c-9d9a-70be2b3b16aa" />

<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/87dab401-a2f2-49c9-a624-a3e2fd099c30" />

------------------------------------------------------------------------

## 8. Final Result

The application allows users to:

-   select a book dynamically
-   display the selected book
-   increase the number of likes
-   reset likes
-   automatically update the browser tab title

This project demonstrates how **React Hooks enable dynamic and
interactive user interfaces**.

------------------------------------------------------------------------

## 9. Possible Improvements

Several improvements could be implemented in the future:

-   display a cover image for each book
-   load books from an API
-   store likes in localStorage
-   add a comment system
-   improve the UI with a CSS framework

------------------------------------------------------------------------

## 10. Author

Developed by:

Ayoub Faradi
