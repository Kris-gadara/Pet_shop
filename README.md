# 🐾 Pet Shop - Flutter Application

A modern, frontend-only Flutter pet shop application featuring product browsing, shopping cart, pet services, and team showcase. Built with clean UI/UX and Material Design 3.

## ✨ Features

- 🛍️ **Product Browsing** - Browse pet products with filtering by category (Dogs, Cats, Birds, Small Animals)
- 🛒 **Shopping Cart** - Add products to cart, manage quantities, and view totals
- 💇 **Pet Services** - Explore grooming, bathing, dental care, and other pet services
- 👥 **Team Showcase** - Meet the pet care experts and staff
- 🔍 **Search** - Search for products and brands
- 📱 **Responsive Design** - Works on web, Android, iOS, Windows, macOS, and Linux
- 🎨 **Modern UI** - Clean, intuitive interface with Material Design 3

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (^3.10.3)
- Dart SDK (comes with Flutter)
- Your preferred IDE (VS Code, Android Studio, IntelliJ)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Kris-gadara/demo_app.git
   cd demo_app/my_flutter_app
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Run the app**

   For web:

   ```bash
   flutter run -d chrome
   ```

   For mobile (with device/emulator connected):

   ```bash
   flutter run
   ```

   For specific platform:

   ```bash
   flutter run -d [device_name]
   # Use 'flutter devices' to see available devices
   ```

## 📱 Supported Platforms

- ✅ Web
- ✅ Android
- ✅ iOS
- ✅ Windows
- ✅ macOS
- ✅ Linux

## 🏗️ Project Structure

```
lib/
├── main.dart                 # App entry point
├── models/                   # Data models
│   ├── cart_item.dart       # Shopping cart item model
│   ├── pet_category.dart    # Pet category types
│   ├── product.dart         # Product model with sample data
│   ├── service.dart         # Pet service model
│   └── team_member.dart     # Team member model
└── pages/                    # UI screens
    ├── pet_shop_home_page.dart    # Main home page (shop & explore)
    ├── product_detail_page.dart   # Product details view
    ├── cart_page.dart            # Shopping cart
    ├── services_page.dart        # Pet services showcase
    ├── team_page.dart            # Team members display
    └── demo_home_page.dart       # Demo task manager (bonus)
```

## 🛠️ Built With

- **Flutter** - UI framework
- **Dart** - Programming language
- **Material Design 3** - Design system
- **Google Fonts** - Typography

## 📦 Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8
  google_fonts: ^6.1.0

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^5.0.0
```

## 🎨 App Screens

1. **Shop** - Browse trending products and pet type categories
2. **Explore** - Filter products by pet type with grid view
3. **Services** - View available pet care services (grooming, bathing, etc.)
4. **Cart** - Manage shopping cart and checkout
5. **Team** - Meet the pet care professionals

## 🔧 Development

### Running Tests

```bash
flutter test
```

### Code Analysis

```bash
flutter analyze
```

### Build for Production

Web:

```bash
flutter build web
```

Android APK:

```bash
flutter build apk
```

iOS:

```bash
flutter build ios
```

## 📝 Notes

- This is a **frontend-only** application
- Product data is stored locally using sample data
- All images use emoji for lightweight rendering
- No backend or database integration
- Shopping cart data is session-based (cleared on restart)

## 👨‍💻 Author

**Krish Gadara**

- GitHub: [@Kris-gadara](https://github.com/Kris-gadara)

## 📄 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- Material Design for the design system
- Google Fonts for beautiful typography

---

**Made with ❤️ using Flutter**
