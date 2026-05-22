# cse24-027-Not-A-Barn-App
Finally, rentals that feel like home — not a barn.

# Not-A-Barn 🏠

**Student Accommodation Finder App**  
*Helping broke students in Gaborone find decent places to rent — definitely not a barn.*

![App Logo](app/src/main/res/drawable/logo.png)

---

## 📖 About the Project

Not-A-Barn is an Android mobile application designed to help University of Botswana and other tertiary students easily discover affordable rental accommodations in Gaborone. The app connects students with landlords through a clean, user-friendly interface with smart filtering, reservation system, and in-app messaging.

**Tagline:**  
*"Not a barn. Just better places for broke students."*

---

## ✨ Key Features

### **Core Features**
- ✅ User Registration & Login (Student / Landlord / Admin)
- ✅ Browse 50+ rental listings with images
- ✅ Advanced Filtering (Price, Location, Availability)
- ✅ Simulated Deposit Payment + Receipt Generation
- ✅ Reservation System (Prevents double booking)
- ✅ Role-based dashboards

### **Extension Feature**
- ✅ In-app Chat (Student ↔ Landlord)

### **Additional Features**
- Local push notifications for new matching listings
- Input validation & error handling
- Clean, modern dark UI (witchy/enchanted theme)

---

## 🛠️ Technologies Used

- **Language:** Kotlin
- **IDE:** Android Studio
- **Database:** Room Database (SQLite)
- **Architecture:** MVVM + Repository Pattern
- **UI Components:** RecyclerView, Navigation Component, Material Design
- **Image Loading:** Glide
- **Notifications:** Android Notification Manager
- **Async Programming:** Kotlin Coroutines

---

## 📱 Screenshots



**Login Screen** | **Browse Listings** | **Listing Detail**
--- | --- | ---
![Login](screenshots/login.png) | ![Browse](screenshots/browse.png) | ![Detail](screenshots/detail.png)

**Payment Flow** | **Chat Screen** | **Landlord Dashboard**
--- | --- | ---
![Payment](screenshots/payment.png) | ![Chat](screenshots/chat.png) | ![Landlord](screenshots/landlord.png)

---

## 🚀 How to Run the Project

### Prerequisites
- Android Studio (latest version recommended)
- Android Device or Emulator (API 24+)

### Setup Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Not-A-Barn.git
