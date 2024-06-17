# React Form with Validation

This is a React application that demonstrates form validation using the `react-hook-form` library and includes a country selection field using the `react-select` component. The app includes fields for email, password, and country selection. The form validates the input based on various rules and displays error messages if the validation fails.

## Features

- Email validation (required, must end with `@harvard.edu`)
- Password validation (required, minimum 10 characters, at least one lowercase letter, one uppercase letter, and one number)
- Country selection using `react-select` (required)
- Form submission handling
- Clearing form fields after successful submission

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/react-form-validation.git
```
2. Navigate to the project directory:
```bash
cd react-form-validation
```
3. Install dependencies:
```bash
npm install
```

## Usage

1. Start the development server:
```bash
npm start
```
2. Open your web browser and navigate to `http://localhost:3000`.

3. Fill in the email, password, and country fields.

4. If any validation fails, error messages will be displayed.

5. Click the "Submit" button to submit the form.

6. After successful submission, the form fields will be cleared.

## Dependencies

This project uses the following dependencies:

- `react`: The React library for building user interfaces.
- `react-hook-form`: A library for managing form state and validation in React.
- `react-select`: A versatile Select component for React.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
