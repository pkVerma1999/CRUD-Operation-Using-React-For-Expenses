# React + Vite

**CRUD Operation Using React for Expenses**
This project is a **React-based CRUD application** for managing expenses, built using Vite. It includes features like input validation, sorting, editing, and local storage persistence.

**Features**
**1. Expense Input Form**
    Fields: Title, Category (Dropdown), Amount
    **Validation:**
     All fields are required.
     Title must be at least 2 characters.
     Amount must be a numeric value.
     Error messages are displayed when validation fails.
**2. Expense Table**
  Displays all expenses with columns: Title, Category, Amount.
   **Sorting options:**
      By Amount (high to low / low to high).
      By Title (alphabetically).
      By Category.
Total Expense Calculation is displayed.
**3. Custom Context Menu**
     Right-click on an expense opens a menu with:
     Edit: Populates form fields for modification
     Delete: Removes the selected expense.
**4. Persistent Storage**
    Uses localStorage to save expenses, ensuring data is retained even after page refresh.
**5. React Hooks & Performance**
   Utilizes useState, useEffect, and custom hooks etc.
   Efficient state management and optimized rendering using Vite.
