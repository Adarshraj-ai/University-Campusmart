# 📱 University Campus Mart

> A cross-platform mobile marketplace built for university students — buy, sell, and exchange books, stationery, electronics, and more.

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

</div>

---

## 📌 Overview

University Campus Mart solves a real problem — students buy expensive textbooks, use them for one semester, and have nowhere to sell them. This app creates a trusted peer-to-peer marketplace within the campus community, making it easy to list, discover, and trade resources.

---

## ✨ Features

- 🔐 **User Authentication** — Secure sign up / login via Supabase Auth
- 🛒 **Product Listings** — Post items with photos, price, and description
- 🔍 **Search & Filter** — Category-based filtering (Books, Electronics, Stationery, etc.)
- 💬 **In-App Chat** — Real-time messaging between buyers and sellers
- 📱 **Responsive UI** — Clean Material Design layout that works on all screen sizes
- 🔄 **Real-time Updates** — Live product feed powered by Supabase Realtime
- 👤 **User Profiles** — Manage listings and view seller history

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Flutter (Dart) |
| State Management | Provider |
| Backend-as-a-Service | Supabase (Auth, Realtime DB, Storage) |
| Database | MySQL (via REST API — order management & profiles) |
| UI Design | Material Design 3 |
| Platform | Android & iOS |

---

## 📁 Project Structure

```
university_campus_mart/
├── lib/
│   ├── main.dart
│   ├── models/          # Data models (Product, User, Message)
│   ├── screens/         # UI screens (Home, Listing, Chat, Profile)
│   ├── widgets/         # Reusable UI components
│   ├── services/        # Supabase & API service classes
│   └── providers/       # State management (Provider)
├── assets/
│   └── images/
├── pubspec.yaml
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK `>=3.0.0`
- Dart `>=3.0.0`
- A [Supabase](https://supabase.com) account (free tier works)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Adarshraj-ai/university-campus-mart.git

# 2. Navigate into the project
cd university-campus-mart

# 3. Install dependencies
flutter pub get

# 4. Set up environment variables
# Create a .env file or update lib/services/supabase_config.dart:
# SUPABASE_URL=your_supabase_project_url
# SUPABASE_ANON_KEY=your_supabase_anon_key

# 5. Run the app
flutter run
```

---

## 📦 Key Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  supabase_flutter: ^2.0.0
  provider: ^6.0.0
  cached_network_image: ^3.0.0
  image_picker: ^1.0.0
```

---

## 🔑 Key Learnings

- Integrating **Supabase Realtime** for live chat and product feed updates
- Managing app-wide state with **Provider** pattern
- Designing **responsive Flutter layouts** that adapt across screen sizes and OS
- Connecting a **MySQL REST API** alongside Supabase for structured relational data

---

## 👨‍💻 Author

**Adarsh Singh**
📧 adarshmass111b@gmail.com
🔗 [github.com/Adarshraj-ai](https://github.com/Adarshraj-ai)

---

> ⭐ If you found this useful, consider giving the repo a star!
