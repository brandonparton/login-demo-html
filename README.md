# Login Demo

A simple front-end login and registration demo built with HTML, CSS, and JavaScript.  
This project simulates a basic authentication flow using both a static `credentials.json` file and browser-based `localStorage` for newly registered users.

## Features

- **Login Validation**: Authenticates against `data/credentials.json` or locally saved users.  
- **Registration Page**: Allows creation of new accounts stored in the browser’s local storage.  
- **Session Handling**: Maintains login state with `localStorage` until logout.  
- **Redirect Protection**: Prevents access to the dashboard without a valid login.  

## Installation

Clone the repository:

```bash
git clone https://github.com/brandonparton/login-demo-html.git
cd login-demo-html
```

## Usage

To view in your browser:

```bash
python -m http.server
```

Then visit:

```bash
http://localhost:8000/
```

## Demo Login

| Username | Password |
|-----------|-----------|
| user      | pass123   |

## Example

![Login Demo](images/login_example.png)