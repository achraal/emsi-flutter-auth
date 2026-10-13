# 📱 Flutter Authentication & Navigation App

A clean, modern mobile application built with **Flutter** and **Material Design 3**, showcasing an authentication workflow (Sign In, Sign Up) and a responsive dashboard with a custom navigation drawer.

---

## ✨ Features

- **🔐 Login Screen (`LoginPage`)**:
  - Username and password input fields with clean icons.
  - Quick navigation to the Registration screen.
  - Route navigation into the Home dashboard.
- **📝 Sign Up Screen (`RegisterPage`)**:
  - Full registration form (Name, Phone, Login, and Password).
  - Validation-ready input layout.
- **🏠 Home Dashboard (`HomePage`)**:
  - Dynamic `UserAccountsDrawerHeader` displaying user profile & avatar.
  - Side navigation drawer with Home, Settings, and Logout triggers.
  - Floating Action Button (FAB) and Material 3 theming.
- **🎨 Modern UI**:
  - Built with Material 3 styling (`useMaterial3: true`).
  - Cohesive color palette based on primary blue accents.
  - Responsive layout structured around Flutter widgets.

---

## 📂 Project Structure

```text
lib/
├── main.dart                  # Application entry point & theme setup
└── screens/
    ├── login_page.dart        # Login interface
    ├── register_page.dart     # Registration interface
    └── home_page.dart         # Main screen with navigation drawer
assets/
└── images/
    └── emsi.png               # Brand & school assets
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have installed:
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (3.13+ recommended)
- [Dart SDK](https://dart.dev/get-dart)
- Android Studio / VS Code with Flutter extension
- An emulator or connected physical device

### Installation & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/aitlahcen_app.git
   cd aitlahcen_app
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the app:**
   ```bash
   flutter run
   ```

---

## 🛠️ Built With

- **[Flutter](https://flutter.dev/)** - UI toolkit for cross-platform apps
- **[Dart](https://dart.dev/)** - Client-optimized language
- **Material 3** - Modern Google UI design system

---

## 👤 Author

- **Achraf Ait Lahcen** ([@achraf](https://github.com/your-username))

