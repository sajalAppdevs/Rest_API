# REST API Basic - Flutter Demo App

A Flutter application demonstrating REST API integration using the JSONPlaceholder API. This project serves as a practical example of how to fetch and display data from a REST API in a Flutter application.

## Features

- Fetches post data from JSONPlaceholder API
- Displays posts in a scrollable list view
- Clean and responsive UI with Material Design
- Proper error handling for API requests

## Getting Started

### Prerequisites

- Flutter SDK (Beta Channel)
- Dart SDK
- Android Studio / VS Code with Flutter plugins

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Run the app:
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── models/
│   └── models_class.dart    # Data models for API responses
├── views/
│   └── home_screen.dart     # Main screen with API integration
└── main.dart               # App entry point
```

## API Integration

The app integrates with the JSONPlaceholder API to fetch post data. The implementation includes:

- HTTP GET request to fetch posts
- JSON parsing and data modeling
- Async/await pattern for handling API calls
- FutureBuilder for managing async state

## Dependencies

- http: ^1.1.0 - For making HTTP requests
- flutter_sdk: ">=3.0.0 <4.0.0"

## Flutter Resources

For help getting started with Flutter development:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Online documentation](https://docs.flutter.dev/)

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
