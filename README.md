# Form Creation and Validation

A user registration form with client-side validation using vanilla JavaScript.

## Project Description

This project implements a user registration form with real-time validation to ensure users provide the correct type of data before submission. The form validates username, email, and password fields according to specific criteria.

## Features

- **Username Validation**: Must be at least 3 characters long
- **Email Validation**: Must contain both '@' and '.' characters
- **Password Validation**: Must be at least 8 characters long
- **Real-time Feedback**: Displays success or error messages dynamically
- **Responsive Design**: Clean and modern UI with centered form layout

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## Files Structure
```
Form-Creation-Validation/
│
├── index.html      # Main HTML structure
├── style.css       # Styling and layout
├── script.js       # Form validation logic
└── README.md       # Project documentation
```

## Validation Rules

1. **Username**: Minimum 3 characters
2. **Email**: Must include '@' and '.' symbols
3. **Password**: Minimum 8 characters

## How to Use

1. Clone this repository:
```bash
   git clone https://github.com/YOUR_USERNAME/Form-Creation-Validation.git
```

2. Open `index.html` in your web browser

3. Test the form with different inputs:
   - Try a username with less than 3 characters
   - Enter an invalid email format
   - Use a password shorter than 8 characters
   - Submit valid data to see success message

## Demo

Fill out the registration form and click "Register". The form will display:
- ✅ Green success message if all validations pass
- ❌ Red error messages for any failed validations

## Learning Objectives

This project demonstrates:
- DOM manipulation with JavaScript
- Event handling (form submission)
- Input validation techniques
- Dynamic content updates
- CSS styling and flexbox layout

## Author

Created as part of a web development learning project.

## License

This project is open source and available for educational purposes.
EOF