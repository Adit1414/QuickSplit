Here’s a clean **README.md** you can directly copy–paste:

---

# 🚀 Quick Split — The Ultimate Private Expense Splitter

**Quick Split** is a powerful, single-page web application for splitting expenses among different groups of friends.
No accounts. No invites. No hassle.
All data is saved securely in your browser.

👉 **View the Live Demo**
*[QuickSplit](https://adit1414.github.io/QuickSplit)*

---

## ✨ Key Features

* **No Accounts Needed**
  Just open the page and start splitting.

* **Permanent Friends List**
  Save your friends once and use them for any expense in the future.

* **Flexible Splitting**

  * Split expenses equally among participants
  * Split expenses unequally by specifying exact shares

* **Detailed Breakdowns**
  Click any logged expense to see a detailed breakdown of who owes whom for that specific transaction.

* **Simplified Final Summary**
  Automatically calculates the simplest way for everyone to settle up across all active expenses.

* **Completely Private**
  All your data is stored exclusively in your browser’s `localStorage`.
  Nothing is ever sent to a server.

* **Mobile-First Design**
  A clean, responsive interface that works beautifully on phones, tablets, and desktops.

* **Dark Mode Support**
  Automatically detects your system preference or toggle manually.

* **Date & Time Tracking**
  Log exactly when an expense happened. Backdate expenses or use the current time automatically.

* **Expense Filtering**
  Filter your expense log by date range to view costs for specific trips, months, or events.

* **Smart Paybacks**
  Record payments directly from the summary screen with a single click (“Payback” button).

* **Archive System**
  Move settled expenses to an archive instead of deleting them permanently. Restore anytime if needed.

---

## 💻 How to Use

### 1. Save Your Friends

In the **My Friends List** section, add the names of people you frequently share expenses with.

### 2. Log an Expense

* Enter the description and amount
* Set the date (defaults to now, but can be changed)
* Select payers (supports multiple payers)

  * Payers are automatically selected as participants
* Select participants
* Choose a split method:

  * **Equally**
  * **Unequally**

### 3. Manage Expenses

* **Filter**
  Use the date inputs in the **Expenses Log** header to view specific timeframes.
* **Archive**
  Click the **Archive** button on old expenses to hide them from calculations.

### 4. Settle Up

* Check the **Final Summary** to see who owes whom
* Click **Payback** next to a debt to instantly record a payment and reduce the balance

### 5. Settings

* Use **Clear All Expenses** to wipe the slate clean
  *(Your friends list stays intact)*

---

## 🛠️ How It Works

This project is built as a single, self-contained `index.html` file for ultimate simplicity.

### Tech Stack

* **HTML**
  Structures the application layout.

* **CSS**
  Provides the clean, responsive design with CSS Variables for seamless Dark Mode switching.

* **Vanilla JavaScript**
  Powers all logic, including:

  * Debt simplification algorithm
  * Date handling
  * Expense calculations

* **localStorage**
  Used for all data persistence:

  | Key                  | Purpose                              |
  | -------------------- | ------------------------------------ |
  | `quickSplitFriends`  | Stores your permanent friends list   |
  | `quickSplitExpenses` | Stores active expenses               |
  | `quickSplitArchived` | Stores archived expenses             |
  | `quickSplitTheme`    | Remembers Light/Dark mode preference |

---

## 🔒 Privacy First

* No accounts
* No backend
* No tracking
* No external APIs

Everything stays in your browser.

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/quick-split.git
   ```

2. Open `index.html` in your browser:

   ```bash
   open index.html
   ```

   *(or double-click the file)*

That’s it. No build tools, no dependencies.

---

Built with ❤️ for privacy, simplicity, and real-world usability.
Feel free to fork, modify, and use it however you like!
