# 1. Purpose of the project

Purpose of the project is creation of new social network with a focus of security and speed.

# 2. Description of the project

Project consists of desktop, mobile and browser versions. Each version includes next functionality:

1. Registration, authentication and authorization.
2. Creation of user profile and its description.
3. Sending massages.
4. Photos, music, videos and wall for each profile.
5. Creation of groups.

# 2.1 Registration

When user visits a web-page he can sign in or create an account.

Registration form includes: 1. Username (unique) 2. Email 3. Password

Sign in form includes:

1. Username / email (use choose comfortable option by radio input)
2. Password

Validations:

1. Username - may contain letter, digits, -, \_. All letters are transformed to lowercase.
2. Email - default.
3. Password - must contain letter, digit, at least 8 symbols.

# 3. Tech stack

Browser version:

- Backend:
  - NodeJS
  - PostgreSQL
- Frontend:
  - React
