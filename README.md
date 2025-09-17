# Flutter Experiments 🚀

This repository contains a set of **Flutter experiments** created as part of my learning journey.  
Each experiment demonstrates a different **concept in Flutter app development**, ranging from UI basics to state management with Provider.

---

## 📂 Experiments Included

### 🟦 Exp2a – Basic Widgets
- Displays a styled **Text widget**.
- Loads an **Image from the network**.
- Shows a **Container** with padding, color, and border radius.

### 🟦 Exp2b – Layout Widgets
- Demonstrates **Row** with icons.
- Uses a **Column** to list multiple items.
- Implements a **Stack** with background, aligned containers, and icons.

### 🟦 Exp3 – Responsive Layout
- Uses **MediaQuery** to detect screen size.
- Displays different background colors and text for **small vs. large screens**.
- Helps understand **responsive UI design** in Flutter.

### 🟦 Exp4 – Navigation
- Demonstrates **Navigator** and **routing** in Flutter.
- First screen → button navigates to Second screen.
- Second screen → button returns back to First screen.

### 🟦 Exp5 – State Management
- Shows two approaches for handling state:
  1. **setState()** with a StatefulWidget.
  2. **Provider + ChangeNotifier** for scalable state management.
- Includes **counter increment** examples in both methods.

---

## 🛠️ Getting Started

### Prerequisites
- Install [Flutter SDK](https://docs.flutter.dev/get-started/install)  
- Install [Dart](https://dart.dev/get-dart) (comes with Flutter SDK)  
- Use **VS Code** or **Android Studio** with Flutter/Dart extensions.

### Run the project
```bash
# Clone the repository
git clone https://github.com/your-username/flutter-experiments.git

# Navigate into the project
cd flutter-experiments

# Install dependencies
flutter pub get

# Run the project
flutter run




Project Structure

lib/
 ├── exp2a_page.dart   # Basic Text, Image, Container
 ├── exp2b_page.dart   # Row, Column, Stack layouts
 ├── exp3_page.dart    # Responsive layout with MediaQuery
 ├── exp4_page.dart    # Navigation between screens
 ├── exp5_page.dart    # State management (setState + Provider)
 └── main.dart         # Entry point of the app
