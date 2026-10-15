# Daily Expense Tracker

A simple multi-page web application built using HTML, CSS, and JavaScript to record, organise, and manage daily expenses.

## About the Project

The Daily Expense Tracker helps users keep track of their everyday spending in one place. Users can add expenses, view their transaction history, calculate total spending, and generate monthly expense reports.

This project was developed as a practical application of front-end web development concepts.

## Features

- **Dashboard:** Displays total spending, number of transactions, highest expense, and recent expenses.
- **Add Expense:** Add expenses with a name, amount, category, date, payment method, and optional description.
- **Expense History:** View all expenses in a table.
- **Search and Filter:** Find expenses by name and filter them by category.
- **Sorting:** Arrange expenses by date or amount.
- **Edit and Delete:** Modify expense names and amounts or remove unwanted records.
- **Monthly Reports:** View monthly spending, transaction counts, average expense, and category-wise totals.
- **Responsive Design:** The layout adjusts for smaller screens.
- **Indian Currency:** All expense amounts are displayed in Indian Rupees (₹).

## Technologies Used

- **HTML5:** Structures the website and its pages.
- **CSS3:** Styles the layout, forms, tables, navigation, and report bars.
- **JavaScript:** Handles expense management, calculations, validation, search, filtering, sorting, and reports.
- **sessionStorage:** Temporarily stores expense records in the browser and shares them between pages within the same tab session.

## Project Structure

```text
DailyExpenseTracker/
│
├── index.html
├── add-expense.html
├── history.html
├── reports.html
├── style.css
├── script.js
└── README.md
```

## How to Run the Project

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` using the Live Server extension, or open it directly in a web browser.
4. Use the navigation bar to move between Dashboard, Add Expense, Expense History, and Reports.
5. Add a few expenses to explore the available features.

Using Live Server is recommended to keep the pages on a consistent local origin.

## How It Works

1. The user enters expense details through the Add Expense form.
2. JavaScript validates the entered information.
3. Valid expenses are added to a JavaScript array.
4. The expense data is stored in `sessionStorage`.
5. Other pages read the stored data to display transaction history, dashboard statistics, and monthly reports.
6. Users can search, filter, sort, edit, and delete expense records.

## Storage and Limitations

This project uses browser `sessionStorage` rather than a database.

- Expense records are temporary and are not stored permanently.
- Records can remain available while navigating between pages and refreshing within the same browser tab session.
- Data is generally cleared when the tab's session ends.
- The project does not include a backend server or user authentication.

## Future Improvements

- Add a database for permanent expense storage.
- Introduce user registration and login.
- Add monthly budgets and spending alerts.
- Allow users to export expense reports.
- Add more detailed spending comparisons.

## Learning Outcomes

Through this project, I practised:

- Creating and linking multiple HTML pages.
- Styling web pages using CSS.
- Using JavaScript variables, arrays, functions, loops, and conditions.
- Handling form submissions and browser events.
- Manipulating HTML elements using the DOM.
- Storing and retrieving temporary browser data.
- Implementing search, filtering, sorting, and calculations.
