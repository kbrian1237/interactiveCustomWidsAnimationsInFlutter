# Interactive Custom Widgets Animations in Flutter

A comprehensive Flutter application demonstrating interactive widgets, custom components, and smooth animations for a money transfer app.

## Features

### Part 1: Interactive Widgets - Send Money Page
- **UI Elements:**
  - TextField for recipient's name with validation
  - TextField for amount with number validation
  - DropdownButton for payment method selection
  - Switch for marking transactions as favorite
  - Visually appealing and properly aligned layout

- **Form Validation:**
  - Recipient name validation (required, minimum 2 characters)
  - Amount validation (positive number, maximum $10,000)
  - Payment method selection validation
  - Real-time visual feedback with error messages

### Part 2: Custom Widgets
- **Reusable Custom Button:**
  - `CustomSendButton` widget with gradient design
  - Loading state with animated spinner
  - Scale animation on press
  - Consistent styling across the app
  - Reusable across different screens

- **UI Consistency:**
  - Consistent color scheme (blue theme)
  - Unified typography and spacing
  - Cohesive design language throughout the app

### Part 3: Animations
- **UI Animations:**
  - `AnimatedContainer` for smooth transitions
  - `AnimatedOpacity` for success messages
  - Elastic animations for success feedback
  - Fade and slide transitions for page elements

- **Page Transitions:**
  - Custom slide transitions between login and dashboard
  - Smooth navigation animations
  - Enhanced visual flow throughout the app

## Screens

1. **Login Screen** (`lib/screens/login_screen.dart`)
   - Animated form with validation
   - Demo credentials provided
   - Custom page transition to dashboard

2. **Dashboard Screen** (`lib/screens/dashboard_screen.dart`)
   - Balance display with gradient design
   - Quick action cards with animations
   - Navigation to send money screen

3. **Send Money Screen** (`lib/screens/send_money_screen.dart`)
   - Complete form with all required widgets
   - Form validation with error messages
   - Success animation after transaction
   - Custom send button implementation

## Custom Widgets

- **CustomSendButton** (`lib/widgets/custom_send_button.dart`)
  - Gradient background with shadow
  - Loading state with spinner
  - Scale animation on interaction
  - Consistent styling and reusability

## Getting Started

### Prerequisites
- Flutter SDK (>=3.0.0)
- Dart SDK (>=3.0.0)
- Android Studio / VS Code

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kbrian1237/interactiveCustomWidsAnimationsInFlutter.git
cd interactiveCustomWidsAnimationsInFlutter
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

### Demo Credentials
- **Email:** demo@example.com
- **Password:** 123456

## Project Structure

```
lib/
├── main.dart                 # App entry point and theme configuration
├── screens/
│   ├── login_screen.dart     # Login screen with animations
│   ├── dashboard_screen.dart # Dashboard with quick actions
│   └── send_money_screen.dart # Send money form with validation
└── widgets/
    └── custom_send_button.dart # Reusable custom button widget
```

## Key Features Implemented

### Interactive Widgets
- ✅ TextField for recipient name
- ✅ TextField for amount
- ✅ DropdownButton for payment method
- ✅ Switch for favorite marking
- ✅ Visual appeal and proper alignment

### Form Validation
- ✅ Recipient name validation (not empty)
- ✅ Amount validation (positive number)
- ✅ Visual feedback for validation errors
- ✅ Real-time validation

### Custom Widgets
- ✅ Reusable custom button for sending money
- ✅ Consistent UI styling
- ✅ Colors, fonts, and spacing consistency

### Animations
- ✅ AnimatedContainer for UI transitions
- ✅ AnimatedOpacity for success messages
- ✅ Custom page transitions
- ✅ Smooth visual flow

## Technologies Used

- **Flutter:** UI framework
- **Dart:** Programming language
- **Material Design:** Design system
- **Custom Animations:** AnimationController, Tween, CurvedAnimation

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License.

## Author

Created by [Your Name] - A comprehensive Flutter app demonstrating interactive widgets, custom components, and animations. 
