# MedTrack - Hospital Management System

MedTrack is a modern web-based Hospital Management System developed using **Flask** and integrated with **Amazon Web Services (AWS)**. It provides a seamless experience for both doctors and patients, allowing secure signup, appointment scheduling, and real-time notifications via AWS SNS.

## 🚀 Features

- 👨‍⚕️ Unified Signup for Patients and Doctors
- 🗓️ Appointment Booking System
- 🔐 Secure Login/Logout using Flask sessions
- ☁️ AWS DynamoDB for storing user and appointment data
- 📩 AWS SNS for real-time notifications
- 🧾 Flash messages for validation and feedback
- 🎨 Clean and intuitive UI with medical-themed design

---

## 🧑‍💻 Tech Stack

| Component     | Technology                     |
|---------------|--------------------------------|
| Backend       | Python, Flask                  |
| Frontend      | HTML, CSS (Bootstrap/Custom)   |
| Database      | AWS DynamoDB                   |
| Notifications | AWS SNS                        |
| Hosting       | (Optional: AWS EC2 / PythonAnywhere) |
| Others        | Boto3 (AWS SDK for Python), Flask-WTF, Jinja2 |

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/medtrack.git
cd medtrack
