# 🧾 Bill Generator

This is a simple **Python-based bill/invoice generator** that takes input for three items (name, cost, and quantity), calculates the total, applies 18% GST, and prints a well-formatted bill with the current date and time.


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


## 📷 Sample Output

<img width="784" height="623" alt="image" src="https://github.com/user-attachments/assets/ea724a20-d2da-4372-a03d-fec6947dac06" />


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
- Try to limit the item names as per the screenshot (8 characters max)

## 💫 Remarks:
Let me know if you'd like this project to include:
- Link to try it online (e.g. on Replit or Colab)
- Option to read inputs from a file or GUI version
- Add more amount of item names
