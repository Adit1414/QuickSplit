# 🚀 Quick Split - The Ultimate Private Expense Splitter

> A powerful, single-page web application for splitting expenses among different groups of friends. No accounts, no invites, no hassle. All data is saved securely in your browser.

### [View the Live Demo](https://adit1414.github.io/QuickSplit)

## ✨ Key Features

* **No Accounts Needed:** Just open the page and start splitting.
* **Permanent Friends List:** Save your friends once and use them for any expense in the future.
* **Multi-Group Support:** Log different expenses with different groups of friends without conflict.
* **Flexible Splitting:**
    * Split expenses **equally** among participants.
    * Split expenses **unequally** by specifying exact shares.
* **Detailed Breakdowns:** Click any logged expense to see a detailed breakdown of who owes whom for that specific transaction.
* **Simplified Final Summary:** The app automatically calculates the simplest way for everyone to settle up across *all* logged expenses.
* **Completely Private:** All your data (friends and expenses) is stored exclusively in your browser's `localStorage`. Nothing is ever sent to a server.
* **Mobile-First Design:** A clean, responsive interface that works beautifully on your phone, tablet, and desktop.
* **Zero Dependencies:** Runs entirely on vanilla HTML, CSS, and JavaScript. It's fast, lightweight, and incredibly portable.

## 💻 How to Use

1.  **Save Your Friends:** In the "My Friends List" section, add the names of people you frequently share expenses with. This list is saved permanently.
2.  **Log an Expense:** Fill out the "Add Expense" form with the description, total amount, and who paid.
3.  **Select Participants:** Check the boxes next to the friends who were involved in *that specific expense*.
4.  **Choose Split Method:** Select whether to split the bill "Equally" or "Unequally". If you choose unequally, input boxes will appear for the selected participants.
5.  **View the Log:** The new expense will appear in the "Expenses Log". Click on it anytime to expand and view its specific breakdown.
6.  **Check the Final Summary:** The "Final Summary" card always shows the most efficient way for everyone to settle all outstanding debts.
7.  **Clear When Done:** When your trip or event is over, click "Clear All Expenses" in the Settings. This resets the expenses but keeps your master friends list safe for next time.

## 🛠️ How It Works

This project is built as a single, self-contained `index.html` file for ultimate simplicity.

* **HTML:** Structures the application layout.
* **CSS:** Provides the clean, responsive, and mobile-friendly design.
* **Vanilla JavaScript:** Powers all the application logic, including calculations, data management, and DOM manipulation.
* **`localStorage`:** The browser's local storage is used for all data persistence.
    * `quickSplitFriends`: Stores your permanent list of friends.
    * `quickSplitExpenses`: Stores the list of all logged expenses.

---

Built with privacy and simplicity in mind. Feel free to fork, modify, and use it however you like!