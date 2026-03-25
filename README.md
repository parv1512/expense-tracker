# Expense Tracker (Firebase + Tailwind)

A simple and modern expense tracker web application that allows users to manage daily expenses, filter by month, and import/export data using CSV. The application uses Firebase Firestore for real-time data storage and anonymous authentication.

---

## Features

- Add and manage daily expenses (description, amount, date, payment method)
- Filter expenses by month
- Automatic calculation of:
  - Total expenses
  - Current month expenses
- Export expenses to CSV
- Import expenses from CSV
- Real-time updates using Firebase Firestore
- Anonymous authentication (no user login required)
- Clean and responsive UI using Tailwind CSS

---

## Tech Stack

- Frontend: HTML, Tailwind CSS, JavaScript
- Backend: Firebase
  - Firestore Database
  - Firebase Authentication (Anonymous)

---

## CSV Format for Import

Ensure your CSV file follows this format:

```
Date,Description,Amount,Payment Method
2026-03-20,Groceries,50,UPI
2026-03-21,Snacks,10,Cash
```

---

## Future Improvements

- Add authentication with Google Sign-In
- Add charts and analytics (e.g., Chart.js)
- Introduce expense categories
- Improve mobile responsiveness
- Add dark mode

---


## License

This project is open-source and available under the MIT License.
