# React Expenses Tracker App

A React-based web application for tracking and managing personal expenses. The app allows users to add, filter, and visualize their expenses by date and category.

## Features

- Add new expenses with title, amount, and date
- Filter expenses by year
- Visual representation of expenses with chart
- Responsive design for all devices
- Interactive UI components

## Getting Started

### Prerequisites

- Node.js (v16 or later)
- npm (Node Package Manager)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd expenses-react-app-main
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The app will open in your default browser at `http://localhost:3000`

## Usage

1. **Adding Expenses**
   - Click on "Add New Expense" button
   - Fill in the expense details (title, amount, date)
   - Click "Add Expense" to save

2. **Filtering Expenses**
   - Use the year dropdown to filter expenses by year
   - The chart will automatically update to show monthly distribution

3. **Viewing Expenses**
   - Expenses are displayed as cards with details
   - Chart shows monthly expense distribution
   - Total amount for selected year is calculated automatically

## Project Structure

```
src/
├── components/
│   ├── Chart/          # Chart visualization components
│   ├── Expenses/       # Expense related components
│   ├── NewExpense/     # New expense form components
│   └── UI/             # Reusable UI components
├── App.js              # Main application component
└── index.js           # Application entry point
```

## Tech Stack

- React.js
- CSS Modules for styling
- JavaScript ES6+

## Running in Development Mode

The application has been configured to run with all Node.js versions, including the latest versions (17+).

```bash
# Start the development server
npm start

# Build for production
npm run build

# Run tests
npm test
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Acknowledgments

- Built with Create React App
- Uses React Hooks for state management
- Chart visualization for expense tracking