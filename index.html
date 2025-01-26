<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Expense Tracker</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      background-color: #f3f4f6;
    }

    header {
      background-color: #3b82f6;
      color: white;
      text-align: center;
      padding: 1rem;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    header h1 {
      font-size: 2rem;
    }

    .welcome-section {
      text-align: center;
      background-color: #dbeafe;
      padding: 2rem;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    .welcome-section h2 {
      font-size: 1.5rem;
      margin-bottom: 0.5rem;
    }

    .welcome-section p {
      font-size: 1rem;
      color: #374151;
    }

    .container {
      flex-grow: 1;
      max-width: 600px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .expense-form {
      margin-bottom: 2rem;
    }

    .expense-form select,
    .expense-form input {
      width: calc(100% - 2rem);
      padding: 0.5rem;
      margin-bottom: 1rem;
      border: 1px solid #d1d5db;
      border-radius: 4px;
    }

    .expense-form button {
      width: 100%;
      padding: 0.5rem;
      background-color: #3b82f6;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1rem;
    }

    .expense-form button:hover {
      background-color: #2563eb;
    }

    .expense-list ul {
      list-style: none;
      padding: 0;
    }

    .expense-list li {
      display: flex;
      justify-content: space-between;
      border-bottom: 1px solid #e5e7eb;
      padding: 0.5rem 0;
    }

    .expense-list li:last-child {
      border-bottom: none;
    }

    .total {
      text-align: right;
      font-weight: bold;
      font-size: 1.2rem;
      color: #3b82f6;
    }

    .disclaimer {
      text-align: center;
      color: red;
      font-weight: bold;
      margin-top: 1rem;
    }

    footer {
      background-color: #1f2937;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Student Expense Tracker</h1>
  </header>

  <section class="welcome-section">
    <h2>Welcome!</h2>
    <p>Track your daily expenses easily and stay on top of your budget.</p>
  </section>

  <div class="container">
    <div class="expense-form">
      <select id="category">
        <option value="">Select Category</option>
        <option value="Water">Water</option>
        <option value="Electricity">Electricity</option>
        <option value="Food">Food</option>
        <option value="Transport">Transport</option>
        <option value="Other">Other</option>
      </select>
      <input id="description" type="text" placeholder="Expense Description">
      <input id="amount" type="number" placeholder="Amount">
      <button onclick="addExpense()">Add Expense</button>
    </div>

    <div class="expense-list">
      <h3>Your Expenses:</h3>
      <ul id="expenses"></ul>
      <p class="total">Total: ₹<span id="total">0.00</span></p>
      <p id="disclaimer" class="disclaimer" style="display: none;">Over the budget limit!</p>
    </div>
  </div>

  <footer>
    <p>&copy; <span id="year"></span> Student Expense Tracker. All rights reserved.</p>
  </footer>

  <script>
    const expenses = [];

    function addExpense() {
      const categoryInput = document.getElementById('category');
      const descriptionInput = document.getElementById('description');
      const amountInput = document.getElementById('amount');

      const category = categoryInput.value;
      const description = descriptionInput.value;
      const amount = parseFloat(amountInput.value);

      if (category && description && amount) {
        expenses.push({ category, description, amount });
        categoryInput.value = '';
        descriptionInput.value = '';
        amountInput.value = '';
        updateExpenseList();
      } else {
        alert('Please fill in all fields.');
      }
    }

    function updateExpenseList() {
      const expensesList = document.getElementById('expenses');
      const totalElement = document.getElementById('total');
      const disclaimerElement = document.getElementById('disclaimer');

      expensesList.innerHTML = '';
      let total = 0;

      expenses.forEach((expense) => {
        const li = document.createElement('li');
        li.innerHTML = `<span>${expense.category} - ${expense.description}</span><span>₹${expense.amount.toFixed(2)}</span>`;
        expensesList.appendChild(li);
        total += expense.amount;
      });

      totalElement.textContent = total.toFixed(2);

      if (total > 1000) {
        disclaimerElement.style.display = 'block';
      } else {
        disclaimerElement.style.display = 'none';
      }
    }

    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
