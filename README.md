[README.md](https://github.com/user-attachments/files/26559898/README.md)
# 🛍️ E-Shop (Flutter REST API App)

## 📌 Project Overview

E-Shop is a modern Flutter-based mobile application developed as part of an academic assignment. The application integrates a public REST API to fetch real-time product data, parse JSON responses, and display the information using both GridView and ListView layouts.

This project demonstrates practical implementation of API integration, UI design, and dynamic data rendering in Flutter.

---

## 🚀 Features

* 🌐 REST API Integration (Fake Store API)
* 📦 Dynamic product fetching from the internet
* 🧾 GridView layout for product browsing
* 📋 ListView layout with toggle option
* 🔄 Switch between Grid & List view (UI toggle button)
* 📄 Product detail screen with full information
* 🖼️ Image loading from network
* ⚡ Clean and responsive UI design

---

## 🛠️ Technologies Used

* Flutter (Dart)
* REST API Integration
* HTTP Package
* JSON Parsing
* Material UI Components

---

## 🌐 API Used

This project uses a public REST API:

Fake Store API
https://fakestoreapi.com/products

The API provides product data such as:

* Title
* Price
* Description
* Category
* Image

---

## 📱 Application Screens

### 🏠 Home Screen

* Displays all products
* Supports both GridView and ListView
* Toggle button to switch layouts

### 📄 Product Detail Screen

* Shows product image
* Displays full description
* Shows price and title

---

## 🧠 Key Concepts Implemented

* REST API calling using HTTP package
* JSON data parsing into Dart model classes
* Asynchronous programming using FutureBuilder
* State management using setState()
* Navigation between screens
* Responsive UI with GridView & ListView

---

## 📸 Screenshots

(Add your app screenshots here)

<img width="1917" height="1079" alt="Screenshot 2026-04-07 162704" src="https://github.com/user-attachments/assets/0c2eae94-7a51-4ea7-b21b-ed08c5cff05f" />
<img width="1918" height="1079" alt="Screenshot 2026-04-07 162652" src="https://github.com/user-attachments/assets/c3cafd95-3e4b-49e0-95ee-bcb44e935aef" />
<img width="1915" height="1079" alt="Screenshot 2026-04-07 162713" src="https://github.com/user-attachments/assets/4fbc4a40-878e-406f-b16a-6cc2e9704754" />
<img width="1918" height="1079" alt="Screenshot 2026-04-07 162734" src="https://github.com/user-attachments/assets/43276ad1-3c27-4e1a-959e-c1d2f9eba2ce" />



---

## 📂 Project Structure

lib/
├── models/
│   └── product.dart
├── services/
│   └── api_service.dart
├── screens/
│   ├── home_screen.dart
│   └── product_detail_screen.dart
├── widgets/
│   ├── product_card.dart
│   └── product_list_tile.dart
└── main.dart

---

## ▶️ How to Run the Project

1. Clone the repository
2. Open in Android Studio / VS Code
3. Run the following command:

flutter pub get

4. Run the app:

flutter run

---

## 🎯 Assignment Objectives Covered

✔ Integrated a public REST API
✔ Parsed JSON data into Flutter models
✔ Displayed data using GridView and ListView
✔ Implemented navigation between screens
✔ Uploaded project on GitHub with documentation

---

## 💡 Future Enhancements

* 🔍 Search functionality
* 🏷️ Category filtering
* 🌙 Dark mode
* 🛒 Add to cart feature
* ❤️ Wishlist system

---

## 👨‍💻 Author

Developed by: Nirmit

---

## 📌 Conclusion

This project helped in understanding real-world Flutter development concepts such as API integration, UI/UX design, and dynamic data handling. It serves as a strong foundation for building scalable mobile applications.

---
