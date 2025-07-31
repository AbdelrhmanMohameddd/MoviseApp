# 🎬 Movies App - Flutter Application

**Movies App** is a sleek and responsive Flutter application that allows users to browse, search, and view details about the latest and most popular movies.  
Built with modern UI components and clean architecture, this project is a great example of integrating APIs and managing app state in Flutter.

---

## 🔥 Key Features

- 🔍 Browse Trending, Upcoming & Top-Rated Movies
- 🎞 Detailed Movie Pages (Overview, Rating, Release Date, Genres)
- 🧠 Smart Search by Title
- ❤️ Add to Favorites
- 📡 Real-Time API Integration (TMDb or similar)
- 🌓 Light & Dark Theme Support
- 📱 Responsive Layout for All Devices

---

## 🧰 Technologies Used

- **Flutter** – Frontend framework
- **Dart** – Programming language
- **REST API** – (e.g. TMDb API)
- **State Management** – Bloc / Cubit / Provider (as per implementation)
- **Local Storage** – (Hive or SharedPreferences for favorites)

---

## 📂 Folder Structure

```bash
lib/
├── core/             # Theme, constants, utilities
├── features/
│   ├── home/         # Movie lists, sections
│   ├── details/      # Movie detail page
│   ├── search/       # Search functionality
│   ├── favorites/    # Saved favorite movies
├── models/           # Movie model, response model
├── services/         # API service and network helpers
└── main.dart
