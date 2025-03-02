# Financial Tracker Application

The Financial Tracker is a Python-based desktop application designed to help users manage and track their financial transactions. Built using the `tkinter` library for the graphical user interface (GUI) and `pandas` for data management, this application allows users to record transactions, categorize them, and visualize their spending patterns through interactive charts.

## Features

### 1. **Transaction Management**
   - **Add Transactions**: Users can add new transactions by specifying the amount, category, description, and date.
   - **Keypad Input**: A built-in keypad allows for easy input of transaction amounts.
   - **Category Selection**: Transactions can be categorized into predefined categories such as Food, Transportation, Utilities, etc.
   - **Date Picker**: A calendar widget allows users to select the transaction date.

### 2. **Data Visualization**
   - **Spending by Category**: A bar chart that shows the total spending for each category.
   - **Monthly Trends**: A line chart that displays the monthly spending trend over time.
   - **Category Breakdown**: A stacked bar chart that provides a detailed breakdown of spending by category for each month.

### 3. **Data Export**
   - **Export Transactions**: Users can export all recorded transactions to a CSV file for further analysis or backup.
   - **Export Charts**: Charts can be exported as PNG images for reporting or sharing.

### 4. **User-Friendly Interface**
   - **Modern Design**: The application features a clean, modern design with a mobile-friendly layout.
   - **Placeholder Text**: Input fields include placeholder text to guide users on what information to enter.
   - **Error Handling**: The application includes robust error handling to ensure data integrity and provide helpful feedback to users.

### 5. **Data Persistence**
   - **CSV Storage**: All transactions are stored in a CSV file (`transactions.csv`), making it easy to manage and backup data.
   - **Automatic Loading**: Transactions are automatically loaded from the CSV file when the application starts.

## How It Works

### Installation

1. **Prerequisites**:
   - Python 3.x
   - Required Python packages: `pandas`, `matplotlib`, `tkinter`, `tkcalendar`

2. **Install Dependencies**:
   ```bash
   pip install pandas matplotlib tkcalendar
3. **Run the Application**:
  - Clone the repository or download the source code.
  - Navigate to the project directory and run the following command:
  ```bash
python financial_tracker.py
```
### Using the Application
1. **Adding a Transaction**:
- Enter the transaction amount using the keypad or manually.
- Select a category from the dropdown menu.
- Optionally, add a description and select a date.
- Click the "Add Transaction" button to save the transaction.

3. **Viewing Reports**:
- Click the "View Report" button to see a bar chart of spending by category.
- Click the "Monthly Trends" button to view a line chart of monthly spending trends and a stacked bar chart of category breakdowns.

4. **Exporting Data**:
- Click the "Export CSV" button to export all transactions to a CSV file.
- In the chart view, click the "Export Chart" button to save the chart as a PNG image.
