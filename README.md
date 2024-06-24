## Introduction
This example showcases a contact form created with JavaScript, which includes client-side validation for each input field.
Error messages are displayed directly below the respective input fields when the user submits the form with invalid data.
## Usage
1. Open `index.html` in your web browser to view the form.
2. Fill in the form fields and submit to see the validation in action.
## Code Explanation
The JavaScript code performs the following steps to create and validate the form:
### Setting up the Environment
We use the `DOMContentLoaded` event listener to ensure the script runs after the DOM is fully loaded.
### Creating the Form Element 
Inside the DOMContentLoaded event listener, we create the form element, set its id to 'contactForm', and assign a validateForm function to run on form submission.
### Helper Function to Create Input Fields
We define a helper function createField that creates a form field (label, input, line break, and error message span) and returns it.
### Creating and Appending Form Fields
We use the createField helper function to create fields for full name, email, and phone number, and then append these fields to the form. 
For the message field, we create it manually since it uses a textarea instead of an input.
### Creating and Appending the Submit Button
We create a submit button and append it to the form.
