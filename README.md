# Salon Booking Manager  

**An intuitive Flutter application designed for seamless salon booking management with real-time updates and responsive design.**  

---

## **Overview**  
Salon Booking Manager is a cross-platform mobile application built using Flutter, designed to simplify salon service bookings for users and streamline booking management for administrators. With robust state management via GetX and Firebase integration, the app ensures real-time data handling and a smooth user experience.  

---

## **Features**  

### **For Users:**  
- **Authentication:** Secure sign-up, login, and profile management.  
- **Booking Management:**  
  - Browse and book salon services.  
  - View booking history.  
  - Cancel bookings when necessary.  
- **Interactive User Experience:**  
  - Responsive design optimized for Android and iOS.  
  - Smooth animations and transitions for an engaging UI.  

### **For Administrators:**  
- **Dashboard Management:**  
  - View all user bookings in real-time.  
  - Approve or cancel bookings efficiently.  
  - Manage salon services with ease.  
- **Real-Time Updates:**  
  - Automatic synchronization of data using Firebase Firestore.  

---

## **Technologies Used**  

### **Frontend:**  
- **Flutter**: A powerful framework for building responsive and feature-rich mobile applications.  
- **GetX**: Simplifies state management, routing, and dependency injection.  

### **Backend:**  
- **Firebase Authentication**: Provides secure user login and registration functionality.  
- **Firebase Firestore**: Enables real-time data handling and updates for bookings and services.  

---

## **Setup and Installation**  

1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/yourusername/salon-booking-manager.git  
   cd salon-booking-manager  

2. **Install dependencies:**  
   ```bash
   flutter pub get


3. **Configure Firebase:**  
   ```bash
   Create a Firebase project in the Firebase Console.
   Add your Android and iOS apps to the Firebase project.
   Download the google-services.json (for Android) and GoogleService-Info.plist (for iOS) files and place them in the respective android/app and ios/Runner directories.


4. **Run the app:**  
   ```bash
   flutter run


