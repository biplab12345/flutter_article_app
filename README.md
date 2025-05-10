# Flutter Article App

A Flutter app that fetches and displays a list of articles from a public API.

## Features
- List of articles
- Search functionality
- Detail view
- Responsive UI
- Pull-to-refresh
- Add/remove favorites
- Persist favorites with shared_preferences

## Setup Instructions
1. Clone the repo or unzip the folder
2. Run `flutter pub get`
3. Run the app with `flutter run`

## Tech Stack
- Flutter SDK
- GetX for state management
- HTTP for API calls
- shared_preferences for local storage

## State Management Explanation
GetX is used for dependency injection, state updates, and navigation. The ArticleController manages the article list, loading states, search filter, and favorites.

## Known Issues / Limitations
- No pagination implemented
