# BORG AL ARAB TECHNOLOGICAL UNIVERSITY Website

This repository contains the source code for the BORG AL ARAB TECHNOLOGICAL UNIVERSITY website. Below, you'll find information on the project structure and how to interact with the different pages.

## Project Structure

The project is organized into several HTML files, each representing a different section of the website. Here's a brief overview:

1. **index.html:** This is the main landing page of the website. It includes a navigation bar, a header section, and cards representing different colleges.

2. **health-sciences.html:** This page displays information about the Health Sciences college, including different programs and departments.

3. **industry-and-energy.html:** This page provides details about the Industry and Energy college, showcasing various programs and divisions.

4. **division.html:** This page is used to display information about different divisions within a program. It includes links to the first and second divisions.

5. **login.html:** This page contains a login form and registration conditions.

6. **script.js:** The JavaScript file initializes the AOS (Animate On Scroll) library and includes a function to show an alert when a specific button is clicked.

## Interacting with the Website

### 1. Navigation

- The website has a navigation bar with links to different sections. You can navigate to different colleges and programs by clicking on the corresponding links.

### 2. Division Details

- On pages like `industry-and-energy.html` and `health-sciences.html`, there are cards representing different programs or departments. Clicking on these cards will lead you to more detailed information about each.

### 3. Passing Data via Links

- The website utilizes links with parameters to pass data between pages. For example:
<a href="division.html?img=textile.png&url_1=https://itclub-batu.github.io/batu-google-drive/division_1.html&url_2=https://itclub-batu.github.io/batu-google-drive/division_2.html" class="p-2 text-center">
  ```
  In this link, parameters like `img` and `url_1` are used to dynamically update elements on the `division.html` page.
4. AOS Library
The website incorporates the AOS library for smooth scroll animations. The animations are triggered on scroll and have a duration of 1000 milliseconds.
5. Login and Registration
The login.html page includes a form for user registration. Fill in the required information, and click the "Submit" button to interact with the form.
6. JavaScript Functionality
The script.js file includes a function showAlert() that displays a notification when buttons with the class btn-incomplete are clicked. The notification is removed after 3 seconds.
Feel free to explore the different pages and interact with the content. If you have any questions or encounter issues, refer to the source code for additional details.

This README provides a high-level overview of the project structure and instructions for interacting with the website. Adjust the content based on the specific details and functionality of your website.
