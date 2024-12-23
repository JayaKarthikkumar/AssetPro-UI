# AssetPro

AssetPro is a front-end web application designed to manage assets and resources effectively. It features a clean and interactive user interface for navigating various sections such as dashboards, employee management, asset tracking, and department details.

---

## Features

- **Dashboard**: Overview of key metrics and data insights.
- **Employee Management**: Manage employee details and assignments.
- **Asset Tracking**: View and manage the inventory of assets.
- **Department Management**: Handle department information.
- **Asset History**: View logs and historical data for assets.
- **Sidebar Navigation**: Easy navigation between application sections.

---

## Prerequisites

Before running the project, ensure you have the following installed:

- **Node.js** (v14 or later)
- **npm** (v6 or later)

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd AssetPro
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

---

## Usage

1. Start the development server:
   ```bash
   npm start
   ```

2. Open the application in your browser:
   ```
   http://localhost:3000
   ```

---

## File Structure

```
AssetPro/
├── public/                # Static assets
├── src/                   # Application source code
│   ├── Api/               # API
│   ├── Components/        # Reusable UI components
│   ├── Pages/             # Page components for routes
│   ├── ContextApi/        # Context API for state management
│   ├── Data/              # Asset/Employee Data 
│   ├── App.js             # Main application component
│   ├── index.js           # Application entry point
│   ├── index.css          # Global styles
├── package.json           # Project metadata and dependencies
```

---

## Key Files

### `App.js`
Defines the main structure and routing of the application, including:
- Sidebar navigation.
- Routes for Dashboard, Employee, Assets, Departments, and Asset History.

### `index.js`
The entry point of the application, which:
- Initializes React with `ReactDOM`.
- Wraps the app in a `BrowserRouter` for routing and a `Provider` for state management.

### `index.css`
Contains global styles including the layout for the sidebar and main content area.

---

## Technologies Used

- **React.js**: Front-end library for building user interfaces.
- **React Router**: For routing and navigation.
- **Context API**: For state management.
- **CSS**: For styling and layout.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add a new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## Acknowledgments

Special thanks to the contributors and open-source libraries that made this project possible.

