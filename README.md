## Overview of the portfolio website and its purpose
 A portfolio website is used to present a person’s work, skills, and experience in an organised and professional way. Its purpose is to allow others, such as employers or clients, to view the individual’s abilities and get in contact with them.

This particular portfolio website includes four pages: a Home page with an introduction, an About page with background information and a skills table, a Projects page showcasing completed work, and a Contact page with a form for communication. Each section was included to provide a clear overview of the developer’s skills, experience, and projects, while also making it easy for users to navigate the site and reach out.

## Issues found

Missing semantic HTML elements (header, main, section, footer)
Overuse of <div> elements
No navigation menu across pages
Missing table in the About page
Incomplete form (missing labels, input types, validation)
Images missing alt attributes
Email not clickable (mailto: missing)
Missing third project on Projects page
No responsive meta tag
Poor structure and inconsistent formatting

## Fixes Implemented

Replacing <div> elements with semantic tags like <header>, <main>, <section>, and <footer>
Adding a consistent navigation menu to all pages
Creating a proper table with <thead> and <tbody> in the About page
Completing the form with labels, multiple input types, and validation attributes
Adding alt text to all images
Converting email text into clickable links
Adding missing content such as the third project
Improving code structure and indentation

## HTML Structure

Each page follows a clear structure:
<header> for the title and navigation
<main> for the main content
<section> to group related content
<article> for individual projects
<footer> for contact details
This improves readability and follows semantic HTML practices.

## Explanation 0f CSS styling approach

The CSS was kept simple and consistent across all pages. Margin, padding, and borders were used to create spacing and organise the layout. Colours were chosen to ensure good contrast and readability.

Different selectors were used, including element selectors (e.g., body, header), descendant selectors (e.g., nav ul li a), and an ID selector (#message). Pseudo-classes such as :hover and :focus were used to improve interaction, especially for navigation links and form inputs.

The navigation, table, and form were styled to improve structure, spacing, and usability.

## Accessibility improvements made
Added descriptive alt text to all images to help screen readers describe images to visually impaired users.
Used a clear and logical heading structure to make it easier to navigate the page.
Provided labels for all form inputs so users understand what information to enter.
Used semantic HTML elements to improve structure and support for assistive technologies.
Ensured good colour contrast to make text easier to read for all users.

## Instructions on how to view website locally

1. Download or extract the project folder
2. Open the portfolio-website folder
3. Double-click index.html
4. Use the navigation menu to move between pages

## Screenshots

![Home](screenshots/home.png)  
![About](screenshots/about.png)  
![Projects](screenshots/projects.png)  
![Contact](screenshots/contact.png)
![HTML](screenshots/HTML-form.png)
![StyledTable](screenshots/styled-table.png)
![Navigation](screenshots/navigation.png)

## Reflection

This project was challenging because the starter code had many missing elements and errors that were not always easy to spot. I found it difficult at first to understand how to structure the pages correctly using semantic HTML instead of relying on <div> elements. Over time, I improved by reviewing examples and applying a simpler, more organised structure.

Another challenge was building the contact form with the correct inputs, labels, and validation. I managed this by working step by step and checking each part as I went.

Overall, this project helped me become more confident in writing HTML and CSS, and improved my ability to identify and fix errors in code.