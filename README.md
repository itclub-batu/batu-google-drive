# BORG AL ARAB TECHNOLOGICAL UNIVERSITY Website

This repository contains the source code for the BORG AL ARAB TECHNOLOGICAL UNIVERSITY website. Below is a guide on how to use the website and how data is transferred using links.

## Table of Contents

1. [Introduction](#introduction)
2. [Website Structure](#website-structure)
3. [Handling Data Transfer](#handling-data-transfer)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

This website is designed for BORG AL ARAB TECHNOLOGICAL UNIVERSITY, providing information about different colleges and programs offered. The site is structured with HTML, styled with Bootstrap, and enhanced with JavaScript.

## Website Structure

The website is organized into several HTML files, each representing a different section of the site:

- `index.html`: The main landing page containing information about colleges.
- `health-sciences.html`: Details about the Health Sciences college and its programs.
- `industry-and-energy.html`: Information about the Industry and Energy college and its programs.
- `division.html`: A generic template for division pages, displaying information about different academic divisions.
- `login.html`: The login and registration page for users.
- `script.js`: JavaScript code for page animations and handling button clicks.

## Handling Data Transfer

Data transfer between pages is facilitated using URL parameters. For example, in the link below:

```html
<a href="image.html?img=textile.png&url_1=https://example1.com&url_2=https://example1.com" class="p-2 text-center">
```

- `img`: Specifies the image path for the division.
- `url_1`: Represents the link for the first-year students.
- `url_2`: Represents the link for the second-year students.

These parameters are then retrieved in the destination page (`division.html`) using JavaScript, and the page elements are updated accordingly.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/borg-al-arab-technological-university.git
   ```

2. Open the desired HTML file in a web browser to view the corresponding page.

3. Explore different colleges, programs, and division pages using the navigation links.

4. Check the login page (`login.html`) for registration and sign-in functionalities.

## Contributing

If you'd like to contribute to the development of this website, please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

---
