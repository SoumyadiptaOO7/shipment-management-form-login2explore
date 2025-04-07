# 🚚 Shipment Management Form

This project is a Shipment Management Form developed as part of a mini project during my internship at **Login2Explore**. It is a web application that allows users to manage shipment data (create and update records) using a simple form-based interface.

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3 / Bootstrap 4**
- **JavaScript / jQuery**
- **[JPDB API](https://login2explore.com/jpdb/)** for database interactions

---

## 📦 Features

- Input and manage shipment details like:
  - Shipment Number
  - Description
  - Source & Destination
  - Shipping Date
  - Expected Delivery Date
- Check for existing shipment entries and:
  - Add new shipments if not found
  - Auto-fill and update if shipment already exists
- Dynamic form control (enable/disable fields based on conditions)
- Alerts and validations for smoother user experience

---

## 🔧 How It Works

1. Enter a **Shipment No** and move focus.
2. If the shipment already exists:
   - Details will be populated automatically.
   - User can update the existing data.
3. If the shipment doesn't exist:
   - The form will be enabled for a new entry.
   - User can save the new shipment.

The app communicates with the **Login2Explore JPDB API** using token-based requests (`PUT`, `GET`, and `UPDATE` operations).

---
## Outputs:-
[![image](https://github.com/user-attachments/assets/fba5776f-879a-4247-9cc2-d1fb61d9f299)
[![image](https://github.com/user-attachments/assets/818ff75f-67eb-42ce-b86c-416442ca6db1)


## 🧪 Sample Credentials (For Demo)

> Replace with actual credentials if available and permitted, or describe how users can obtain their own token from [JPDB](https://login2explore.com/jpdb/).

```javascript
const connToken = "90934287|-31949208255731529|90957646";
const dbName = "DELIVERY-DB";
const relName = "SHIPMENT-TABLE";
