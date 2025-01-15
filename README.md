# Directory Application: Add and Retrieve Person Information

This React application provides a simple and intuitive interface to manage personal information. It includes two main functionalities:
1. **Add New Person**: Input personal details and save them locally.
2. **Retrieve Information**: Search for a person's details using their Aadhar number.

---

## Features

### Add New Person
- Input fields for **Name**, **Date of Birth**, **Aadhar Number**, and **Mobile Number**.
- Automatically calculates and displays the **Age** based on the date of birth.
- Validates input fields for correct formats:
  - **Aadhar**: Must be 12 digits.
  - **Mobile Number**: Must be 10 digits.
- Stores the details in the browser's `localStorage` for persistent data management.
- Displays a table of all saved persons with the option to delete any record.

### Retrieve Information
- Allows searching for a person's details using their **Aadhar number**.
- Displays the retrieved information in a table format if found.
- Alerts the user if no matching record is found.

### Error Boundary
- Ensures the application remains stable by catching and displaying errors gracefully.

---

## Technologies Used
- **React**: Component-based library for building the user interface.
- **CSS**: For styling the application and enhancing user experience.
- **localStorage API**: For storing and retrieving data persistently in the browser.

---

## Getting Started

### Prerequisites
- Node.js and npm should be installed on your system.

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
