# Task Manager App Using REST API In Flutter 

A comprehensive Task Management application built with Flutter that interacts with a RESTful backend. The app features a clean UI, secure authentication, and real-time task tracking.

## 🚀 Features
- **Full Authentication:** Login, Sign up, and Forgot Password (OTP-based) flows.
- **Task Management:** Create, Update, and Delete tasks across four categories: New, Progress, Completed, and Cancelled.
- **Dynamic Dashboard:** Real-time task count display on the dashboard for quick overview.
- **User Profile:** Dedicated profile section with the ability to update user information and profile pictures.
- **Clean UI/UX:** Custom background layouts, splash screen branding, and intuitive navigation.

## 🛠️ Tech Stack & Architecture
- **Framework:** Flutter
- **State Management:** (যেটা ব্যবহার করেছেন, যেমন: Provider/GetX/StatefulWidget)
- **API Handling:** REST API with `http` package.
- **Architecture:** Layered Architecture (Models, Services, Controllers, and UI).

## 📂 Project Structure
- `data/models`: Data structures for tasks and users.
- `data/services`: API calling logic (`api_caller.dart`).
- `ui/screens`: All feature screens (Auth, Task lists, Profile).
- `ui/widgets`: Reusable custom components (Task cards, App bars).


