# Radial Floating Action Button

A customizable Flutter widget that expands a single Floating Action Button (FAB) into six hidden action buttons arranged in a radial layout. The widget uses smooth animations to provide quick access to multiple actions while keeping the interface clean and uncluttered.

## Features

* Expandable radial Floating Action Button
* Six hidden action buttons
* Smooth open and close animations
* Fully customizable icons, colors, and actions
* Configurable animation duration
* Adjustable expansion radius
* Lightweight and reusable widget
* Responsive across different screen sizes
* Easy integration into existing Flutter projects

---

## Requirements

* Flutter 3.0 or later
* Dart 3.0 or later

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/radial-fab.git
```

Navigate to the project directory:

```bash
cd radial-fab
```

Install dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

---

## Usage

Import the widget into your project:

```dart
import 'package:your_project/widgets/radial_fab.dart';
```

Add the widget to the `floatingActionButton` property of your `Scaffold`:

```dart
Scaffold(
  floatingActionButton: RadialFAB(),
);
```

---

## How It Works

1. Tap the main Floating Action Button.
2. The button expands with a smooth animation.
3. Six hidden action buttons appear around the main button.
4. Tap any action button to trigger its assigned callback.
5. Tap the main Floating Action Button again to collapse all action buttons.

---

## Customization

### Change the Expansion Radius

```dart
radius: 120,
```

Increase or decrease the radius to control the distance between the center button and the action buttons.

### Change Animation Duration

```dart
duration: const Duration(milliseconds: 300),
```

Adjust the duration to make the animation faster or slower.

### Change Icons

```dart
Icon(Icons.share)
```

Replace the icons with any Flutter Material icons or custom widgets.

### Change Colors

```dart
backgroundColor: Colors.blue,
```

Customize the colors of both the main Floating Action Button and the action buttons.

### Update Actions

Assign a callback to each button:

```dart
onPressed: () {
  // Your action
},
```

---

## Project Structure

```text
lib/
├── main.dart
├── radial_fab.dart
├── widgets/
├── models/
└── animations/
```

---

## Use Cases

* Quick navigation
* Social media actions
* Dashboard shortcuts
* Productivity tools
* Contact actions
* Settings menu
* Editing tools
* Frequently used application features

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. 

## INSTAGRAM PAGE 
Check out @storymint.studio for more ui content 

