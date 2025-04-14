# SmartGeoAttendance

A smart and secure location-based attendance system designed to eliminate proxy attendance by verifying both the geographical location and device identity of students.

## 🚀 Features

- 📍 **Geo-location Verification** – Ensures the student is within the predefined college boundary before marking attendance.
- 📱 **Device Binding** – Only the registered device can mark attendance to prevent misuse.
- 📊 **Real-time Validation** – Combines GPS location and device ID checks.
- 🔐 **Secure & Efficient** – Simple yet powerful SQLite database to store device data and logs.
- 🏫 **Working System** – Currently implemented and functional in:

> **Department of Computer Science and Applications, Panjab University, Chandigarh**

## 🛠️ Tech Stack

- **Python**
- **SQLite**
- **Geopy** for distance calculation
- **Tkinter** for GUI (if applicable)
- **OS-level Device ID Tracking**

## 🎥 Demo Video

Watch the full system in action here:  
👉 [https://drive.google.com/file/d/1D1k-6eY1ix1bMeK9ycbU7rtI8PfnSTz8/view?usp=drive_link](#) *(Replace this with your actual video link)*

## 🏁 How It Works

1. The student opens the attendance portal.
2. The system fetches the **device ID** and **GPS coordinates**.
3. The distance from the pre-set location is calculated.
4. Attendance is allowed **only** if the student is:
   - Within the valid radius
   - Using the registered device

## 📍 Institution Info

> This system is actively in use at  
> 🎓 **Department of Computer Science and Applications**  
> 🏛️ **Panjab University, Chandigarh**

## 📌 Future Improvements

- Admin dashboard for attendance analytics
- OTP verification for additional security
- Face recognition integration
- Cloud backup and sync

## 🤝 Author

**Sayak Biswas**  
MCA Student, DCSA, Panjab University  
Email: _your_email_here_  
LinkedIn: [your-linkedin](https://www.linkedin.com/in/sayak-biswas-a87282177/)  
GitHub: [sayakbiswas](https://github.com/sayakbiswas31)
