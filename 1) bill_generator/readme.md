# 🧾 Bill Generator

This is a simple **Python-based bill/invoice generator** that takes input for three items (name, cost, and quantity), calculates the total, applies 18% GST, and prints a well-formatted bill with the current date and time.

---

## 📌 Features

- User input for:
  - 3 item names
  - Cost and quantity of each item
- Calculation of:
  - Item-wise total
  - Overall subtotal
  - GST @ 18%
  - Final total including tax
- Timestamping with:
  - Current date
  - Current time (Indian Standard Time)

---

## 📷 Sample Output

<img width="795" height="625" alt="image" src="https://github.com/user-attachments/assets/f3555d37-2040-4295-a700-70b13488672c" />

---

## 🛠 How to Run

### 🖥 Requirements:
- Python 3.x
- `pytz` library (for timezone support)

### ▶️ Run the script:
```bash
pip install pytz
python bill_generator.py
```

## ✏️ Note:
- Try to limit the item name as per the screenshot (8 characters max)

---

Let me know if you'd like this README to include:
- Link to try it online (e.g. on Replit or Colab)
- Option to read inputs from a file or GUI version
