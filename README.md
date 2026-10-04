# ☁️ Cloud-Based Attendance System

A cloud-based student attendance management system developed using Python and Google Colab. The system stores student and attendance records in Google Drive and provides a simple web interface using Gradio.

## 🚀 Features

- Add and manage student records
- Mark students as Present or Absent
- Prevent duplicate attendance for the same day
- Store attendance data in Google Drive
- Calculate attendance percentage
- Generate attendance reports
- Simple Gradio web interface

## 🛠️ Technologies Used

- Python
- Google Colab
- Google Drive
- Pandas
- Gradio

## ☁️ Cloud Computing Concept

Google Colab is used as the cloud-based execution environment, while Google Drive provides persistent cloud storage for student and attendance data.

The system allows attendance data to be processed remotely and stored in cloud infrastructure without requiring a local server.

## 🏗️ System Architecture

```text
             User / Teacher
                   │
                   ▼
             Gradio Interface
                   │
                   ▼
             Google Colab
                   │
             ┌─────┴─────┐
             ▼           ▼
        Student Data   Attendance
             │           │
             └─────┬─────┘
                   ▼
             Google Drive
              ☁️ Cloud Storage
```

## 📂 Project Structure

```text
cloud-based-attendance-system/
│
├── Cloud_Based_Attendance_System.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Run the installation cells.
3. Connect your Google Drive.
4. Run the student database and attendance cells.
5. Launch the Gradio interface.
6. Use the interface to mark and analyze attendance.

## 📊 Attendance Calculation

The system calculates attendance using:

```text
Attendance Percentage =
(Present Days / Total Attendance Days) × 100
```

## 🔮 Future Enhancements

- Teacher authentication
- Student login
- Attendance dashboard
- Email/SMS notifications
- Face-recognition attendance
- Database integration
- Cloud deployment
- Attendance analytics

## 👩‍💻 Author

**Rania**

Cloud Computing Project
