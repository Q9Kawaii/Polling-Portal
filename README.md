# Polling-Portal

Polling-Portal is a web-based application developed as a project at SRM Institute of Science and Technology. This platform enables administrators to create polls and allows students to participate in them seamlessly.

## Features

- **Administrator Access**: Secure login for administrators to manage polls.
- **Student Participation**: Students can view and vote on active polls.
- **Poll Creation**: Administrators can create new polls with multiple options.
- **Responsive Design**: User-friendly interface compatible with various devices.

## Installation

To set up the Polling-Portal locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Q9Kawaii/Polling-Portal.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd Polling-Portal
   ```
3. **Install Dependencies**:
   Ensure you have Node.js installed. Then, run:
   ```bash
   npm install
   ```
4. **Start the Application**:
   ```bash
   npm start
   ```
   The application should now be running on `http://localhost:3000`.

## Usage

- **Administrator**:
  - Navigate to `Admin.html` to access the admin login page.
  - After logging in, use the dashboard to create and manage polls.
- **Student**:
  - Access `Student.html` to view available polls.
  - Register via `StudentSignup.html` if you are a new user.
  - Participate in active polls by selecting options and submitting your vote.

## Project Structure

- `index.html`: Landing page.
- `Admin.html`: Administrator login and dashboard.
- `Student.html`: Student portal for viewing and participating in polls.
- `createnewpoll.html`: Interface for administrators to create polls.
- `styles.css`: Styling for the application.
- `script.js`: Client-side JavaScript functionalities.

## Contributing

Contributions are welcome. Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards.

## License

This project is licensed under the MIT License. For more details, refer to the `LICENSE` file in the repository.

## Acknowledgments

This project was developed as part of the curriculum at SRM Institute of Science and Technology. Special thanks to the faculty and peers for their support and guidance.

For a live demo, visit: [Polling-Portal Live](https://q9kawaii.github.io/Polling-Portal/)
