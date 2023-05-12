## The Odin Project Sign up form

![The Odin Project Sign up form screen](https://raw.githubusercontent.com/TomekLeszczynski/Odin-Project-Sign-up-form/1a917f995fafff8487269a872438caa85cef2fbb/img/APP%20SCREEN.jpg)

## General Info

Sign up form focused on client-side validation: Input pattern and regex usage, Input behaviors, automatic validation and UX in forms.

## Features

Validation:

- For this project all fields are required and have "pattern" so the validation is done automatically.
- "Create Account" button is disabled till the User sets an identical "Password" and "Confirm Password". However, even then, the form will not be submitted if the remaining fields are not green.
- JS simultaneously checks the correctness of the "Password" and "Confirm Password", displaying an error message until the passwords match.
- The form is not real, it does not retrieve or store the entered data - it only focuses on validation.

UX:

- Each field has a "placeholder".
- Every active input field that is not filled in or the input does not match the "pattern" has a red background.
- Every active and inactive field that is correctly filled in has a green background.
- The user is constantly informed about the match between "Password" and "Confirm Password".
- The user is informed with a constant message that all fields must remain "green" in order to proceed.
- Autocompletion is off

## Technologies

Built with:

- HTML,
- CSS (Sass),
- Vanilla Javascript.

## Inspiration & resources

The Odin Project project assignment:
https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-sign-up-form
Source info:
https://www.sitepoint.com/html-forms-constraint-validation-complete-guide/
https://www.silocreativo.com/en/css-rescue-improving-ux-forms/
https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/pattern
https://www.sitepoint.com/html-forms-constraint-validation-complete-guide/

## Status

Completed.

## Conclusion & Issues
* Built-in form validation is not as customizable as JS validation.
* Got some issues with displaying images by GithubPages.
* autocomplete="off" is not working properly on Chrome
* Since the form is not submitting data, page may get damage after clicking the button.
* More options of client-side validation to check later.

