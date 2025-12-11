# Payment_receipt_portal
A front-end web-based payment receipt generator for Lourdes Mata Central School with secure login, preview, edit, and A4 print-ready receipt system and This project was designed and developed as a client-based freelance solution for Lourdes Mata Central School, focusing on usability, modern UI, and efficient receipt management.

# Lourdes Mata Central School – Payment Receipt Generator Portal

A modern, user-friendly web-based **Payment Receipt Generator System** developed for **Lourdes Mata Central School**. This project enables school staff to securely log in, create, preview, edit, and print professional fee receipts with a consistent premium design and smooth user experience.

---

## 📌 Project Overview

The Payment Receipt Generator Portal is a front-end web application that allows school staff to:

* Securely log in to the system
* Enter student fee details
* Preview the receipt before final submission
* Edit data if required
* Generate a print-ready A4 receipt
* Download or print the final receipt

The system follows a structured multi-step workflow for accuracy and transparency in fee collection.

---

## 🏫 Client Details

**Institution:** Lourdes Mata Central School,Chavara

---

## 🎯 Key Features

* ✅ Premium animated login interface
* ✅ Secure client-side authentication
* ✅ Multi-step receipt creation process
* ✅ Real-time preview of receipts
* ✅ Edit before final submission
* ✅ Print-ready A4 layout
* ✅ Local storage-based data persistence
* ✅ Amount in words conversion
* ✅ Responsive design (Desktop + Mobile)
* ✅ Elegant UI using modern CSS

---

## 🧩 Technology Stack

This project is currently **Front-End Only**.

* HTML5
* CSS3 (Custom premium theme)
* Vanilla JavaScript
* LocalStorage for session handling

⚡ Desktop Application Framework
Electron.js

* Converts the web project into a desktop application
* Provides IPC communication between frontend & backend
* Handles secure login, window creation, and DB access

🗂️ Database
SQLite (sql.js version)

* Lightweight embedded database
* Stores all generated receipts locally as school.db
* No server required

🔌 Electron Preload / IPC
Secure communication layer (preload.js)

* Exposes safe APIs:
* window.api.login()
* window.api.saveReceipt()
* window.api.getReceipts()

⚙️ Backend (Inside Electron)
Node.js

* Database operations
* IPC handlers
* Main window controller

📦 Build & Package Tools (Optional for future)
* Electron Builder / Forge (Recommended for EXE creation)
* Node Package Manager (NPM)
---


---

## 🔄 System Workflow

1. User logs in using secure credentials
2. Redirected to receipt form page
3. Enters student & payment details
4. Clicks "Preview" to see formatted receipt
5. Can go back to edit if needed
6. Submit & proceed to print page
7. Final option to print receipt on A4

---

## 🖨 Output Format

* Optimized for A4 size printing
* School branded header
* Structured receipt layout
* Professional appearance

---
## 📈 Future Enhancements

* OTP-based login
* Role-based access control
* PDF auto-download feature
* Email receipt delivery

---
## 👩‍💻 Developer

* Developed by: Reshma R S
* Role: Freelance Front-End Developer
* Project Type: Independent Freelance Work

This project was designed and developed as a client-based freelance solution for Lourdes Mata Central School, focusing on usability, modern UI, and efficient receipt management.
---
## 🔗 SceenShots
* login.html.page
  <img width="1327" height="897" alt="Screenshot 2025-12-11 115625" src="https://github.com/user-attachments/assets/249a8949-644f-41ee-ad57-4892c01b15b4" />


* Enter password Animation
<img width="1329" height="893" alt="image" src="https://github.com/user-attachments/assets/3c731b2c-5acc-4b5b-b3d5-23338940112d" />

* Form Page
  <img width="1319" height="855" alt="image" src="https://github.com/user-attachments/assets/8b95a72e-0374-4c3f-a84e-0289b9248ef5" />

* Preview Page
  <img width="1325" height="884" alt="image" src="https://github.com/user-attachments/assets/81dbbdff-a071-45d0-ab9a-015338feb2e5" />

* Print preview page
  <img width="1323" height="888" alt="image" src="https://github.com/user-attachments/assets/cb50052f-dca1-40fa-bbca-33bd9606cba7" />
