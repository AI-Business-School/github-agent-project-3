# Simple Contact Form

A clean, responsive contact form built with HTML and CSS.

## Project Overview

This project provides a simple yet elegant contact form that can be integrated into any website. The form includes fields for name, email, subject, and message. It's styled with a modern, minimalist design.

## Features

- Responsive design - works on desktop and mobile
- Form validation for required fields
- Clean and modern UI
- Simple JavaScript for form submission handling

## Running the Project

This project is configured to run in GitHub Codespaces. To get started:

1. Create a codespace from this repository
2. Wait for the devcontainer to finish building
3. Use the VS Code Live Server extension to serve the project:
   - Click on "Go Live" in the status bar or right-click on `index.html` and select "Open with Live Server"

## Project Structure

```
.
├── .devcontainer/
│   └── devcontainer.json   # Configuration for GitHub Codespaces
├── index.html              # Contact form HTML
├── styles.css              # CSS styling for the form
└── README.md               # This file
```

## Customization

You can easily customize this form by:

- Changing colors in the CSS file
- Adding or removing form fields in the HTML
- Modifying the form submission logic in the JavaScript section

## Next Steps

In a production environment, you would want to:
1. Add a backend to process form submissions
2. Implement CSRF protection
3. Add more robust form validation
4. Consider adding a CAPTCHA to prevent spam
