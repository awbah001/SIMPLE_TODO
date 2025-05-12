## Flutter To-Do App

A simple and clean To-Do app built with Flutter. This application allows users to manage their tasks efficiently with an intuitive UI.

## Features

* Add, edit, and delete tasks
* Mark tasks as complete or incomplete
* Persistent storage using local database (SQFLite)
* Responsive and adaptive UI

## Getting Started

### Prerequisites

* Flutter SDK installed ([Flutter installation guide](https://docs.flutter.dev/get-started/install))
* Android Studio or VS Code

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-todo-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flutter-todo-app
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

## Folder Structure

```
lib/
├── main.dart
├── models/
│   └── task_model.dart
├── screens/
│   ├── home_screen.dart
│   └── task_screen.dart
├── widgets/
│   ├── task_tile.dart
│   └── task_list.dart
└── services/
    └── database_helper.dart
```

## Contributing

Contributions are welcome! Feel free to open a PR or report an issue.

## License

This project is licensed under the MIT License.
