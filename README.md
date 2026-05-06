# MyProctor | Android-Based Examination Portal

MyProctor is a mobile application developed in Java for the Android ecosystem. It provides a structured environment for students to access exam materials, submit responses, and interface with academic databases, focusing on a mobile-first approach to digital testing.

## 🚀 Key Features

- **Student Dashboard:** Personalized interface for viewing registered exams and performance history.
- **Mobile Examination Interface:** Optimized UI for taking quizzes and objective tests on Android devices.
- **Backend Integration:** Connects to a central database for real-time question retrieval and answer submission.
- **Automated Grading:** Logic for instant evaluation of objective-type assessments.

## 🛠 Tech Stack

- **Language:** Java (Android)
- **IDE:** Android Studio
- **Database:** SQLite (local) / Firebase or MySQL (remote)
- **Min SDK:** [Specify e.g., API 21: Lollipop]

## 📂 Repository Structure
```text
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/        # Activities, Adapters, and Data Models
│   │   │   └── res/         # Layout XMLs and UI assets
├── build.gradle             # Build configuration
└── README.md
```

## ⚙️ Setup

1. Clone the repository.
2. Open the project in **Android Studio**.
3. Sync Gradle and build the APK.
4. Run on an Emulator or a physical Android device.

## Application Workflow

### 1. Students log into the digital proctoring system with their student ID and password

<img src="./Media/1.png" alt="drawing" width="45%"/>

### 2 . Students can glance their information and their proctor's information and can send messages to their proctors

<img src="./Media/2.png" alt="drawing" width="45%"/>

### 3. Proctors can login to the system using the faculty ID and password

<img src="./Media/3.png" alt="drawing" width="45%"/>

### 4. The proctor can view the list of queries posed by their student

<img src="./Media/4.png" alt="drawing" width="45%"/>
