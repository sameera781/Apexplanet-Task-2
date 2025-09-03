# Apexplanet-Task-2
Explanation of the Code
1. HTML Structure

<!DOCTYPE html> declares the document as HTML5.

<header> contains the site title "Apex Planet — Web Dev Practice".

<main> is divided into two sections:

To-Do List – lets users add, complete, and delete tasks.

Contact Form – a form with validation for name, email, message, and consent.

2. CSS Styling

General: A clean layout using sans-serif font, light background (#f5f5f5), and dark text (#333).

Header: Green background (#22c55e) with white text, centered.

Main Layout: Grid with two columns (grid-template-columns: 1fr 1fr).

Responsive Design: A media query (@media(max-width:768px)) makes the layout switch to single column on smaller screens.

To-Do Items: Styled with padding, border, and hover interactivity. Completed tasks have line-through and reduced opacity.

Form Inputs: Styled with padding, borders, and rounded corners. Errors are shown in red text.

3. JavaScript Functionality
A. To-Do List

Tasks are stored in an array (todos).

Functions:

addTodo() → Adds a new task from input.

render() → Updates the <ul> with the current task list.

toggle(i) → Marks a task as completed or uncompleted when clicked.

del(i) → Deletes a task from the list.

Uses DOM manipulation to update the list dynamically.

B. Contact Form Validation

Prevents form submission if required fields are empty.

Checks:

Name: Cannot be empty.

Email: Must match a valid email regex pattern.

Message: Cannot be empty.

Consent Checkbox: Must be checked.

Shows error messages below each field if invalid.

On success, displays "Form submitted successfully!" and resets the form.

Features Demonstrated

HTML:

Structure with <header>, <main>, <section>, forms, inputs, and lists.

CSS:

Layout with CSS Grid, media queries for responsiveness, hover styles, and error styling.

JavaScript:

Dynamic To-Do List (add, toggle, delete tasks).

Form Validation with error handling and success message.

Demonstrates arrays, event listeners, DOM manipulation, and regex validation.

Summary

This project combines two mini-applications in one webpage:

A To-Do List App for practicing JavaScript arrays and DOM updates.

A Contact Form with Validation for learning form handling and user input checks.

It demonstrates practical web development skills like:

Responsive design with media queries.

Interactive UI with JavaScript.

Real-world form validation.
<img width="1892" height="900" alt="Screenshot 2025-09-03 115844" src="https://github.com/user-attachments/assets/3e02d3a8-7117-409f-8d6e-591045223ae9" />
<img width="1897" height="934" alt="Screenshot 2025-09-03 115938" src="https://github.com/user-attachments/assets/1a3a115d-f88d-42f7-9611-656b87232538" />

