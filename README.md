# HTML Student Information Form

## Overview

This is a simple HTML project that demonstrates the creation of a web-based form. The form collects basic user information such as name, year of study, ID, password, programming languages known, and feedback.

The form is submitted using **Web3Forms API** for handling form submissions.

## Features

* User input fields (text, password)
* Radio buttons for selecting year of study
* Checkboxes for selecting known programming languages
* Feedback section (Yes/No option)
* Form submission using external API (Web3Forms)
* Simple and clean HTML structure

## Technologies Used

* HTML5
* Web3Forms API (for form submission)

## Form Fields Included

* Name
* Year of Study (1st / 2nd / 3rd year)
* Student ID
* Password
* Known Programming Languages (C, C++, Python, HTML, Java)
* Feedback (Liked / Not Liked)

## How It Works

1. The user fills in the form fields.
2. The form data is submitted using a POST request.
3. Web3Forms processes the submission using the provided access key.
4. The data is sent to the configured destination (email or dashboard).

## How to Run

1. Download or clone the repository.
2. Open the `index.html` file in any web browser.
3. Fill out the form and click **Submit**.

No additional setup is required.

## Project Structure

```
html-form-project/
│
├── index.html
└── README.md
```

## Future Improvements

* Add CSS styling for better UI/UX
* Add JavaScript form validation
* Display success/failure message after submission
* Make the form responsive for mobile devices
* Add backend integration for custom data handling

## Learning Outcomes

This project helped in understanding:

* HTML form structure
* Input elements and attributes
* Radio buttons and checkboxes
* Basic form submission using APIs
* Structuring a simple web page
