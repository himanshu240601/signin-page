# Sign In Page

A simple responsive **login and signup interface** built using HTML, CSS, JavaScript, and Bootstrap.

This was an early frontend practice project focused on recreating a clean authentication UI from a design reference and implementing basic client-side interactions.

> **Project Note**
>
> This is an older learning project and is preserved as part of my development journey.  
> It does not include a backend or real authentication system.

## Preview

The project includes:

- Login page
- Signup page
- Password visibility toggle
- Basic form validation
- Success and error messages
- Social login UI buttons
- Responsive layout

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Bootstrap Icons
- Google Fonts

## Functionality

### Login

The login screen validates that the email/phone and password fields are not empty.

On successful validation, it displays a success message.

### Signup

The signup screen checks:

- Required fields
- Password confirmation
- Matching passwords

### Password Visibility

Users can toggle password visibility using the eye icon.

## Project Structure

```text
signin-page/
│
├── css/
│   └── style.css
│
├── js/
│   └── app.js
│
├── signup_page/
│   └── index.html
│
├── index.html
└── README.md
```

## Running Locally

Clone the repository:

```bash
git clone https://github.com/himanshu240601/signin-page.git
```

Open the project:

```bash
cd signin-page
```

Then open:

```text
index.html
```

in any modern web browser.

No build step or additional dependencies are required.

## Limitations

This project is UI-focused only.

The following features are not implemented:

- Real authentication
- Backend integration
- Database storage
- Functional Google login
- Functional Facebook login
- Functional Twitter login
- Password recovery

The login and signup actions are simulated using basic JavaScript validation.

## Design Inspiration

The UI was inspired by a Dribbble login design:

[Login UI – Dribbble](https://dribbble.com/shots/18063206-Login-UI)

## What I Learned

This project helped me practice:

- Converting a design reference into a working webpage
- CSS layout and styling
- Bootstrap utilities and components
- Basic DOM manipulation
- Form validation with JavaScript
- Password visibility interactions
- Creating login and signup flows

## Author

**Himanshu Goyal**

GitHub: [@himanshu240601](https://github.com/himanshu240601)

## License

No open-source license is currently specified for this repository.
