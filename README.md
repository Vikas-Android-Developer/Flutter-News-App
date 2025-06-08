# News App (Flutter)

A Flutter-based mobile news application that fetches and displays news articles from various categories. It uses Firebase Authentication for user login, supports location-based content, and provides a smooth, interactive UI.

---

## Features

- **User Authentication**
  - Firebase Authentication with Google Sign-In.
  - Secure login and logout functionality.

- **News Categories**
  - Browse news by categories such as General, Business, Technology, Sports, Health, Entertainment, and Science.
  - Easy tab navigation between categories.

- **Search Functionality**
  - Search for news articles by keywords.

- **Location-based News**
  - Uses device location to fetch relevant news (country-specific).

- **Smooth UI & UX**
  - Pull to refresh news articles.
  - Infinite scrolling with lazy loading of news.
  - Loading shimmer effect while fetching data.

- **Detailed News View**
  - Tap on any news card to view full article details.

- **Dark & Light Theme Support**
  - Tap the app title to toggle between dark and light themes.

---

## Screenshots

| Home Screen               | Article Detail           |
|--------------------------|-------------------------|


---

## How to Use

- Open the app and log in with Google.
- Browse news by selecting categories from the tabs.
- Use the search bar to find specific news.
- Tap on an article to read full details.
- Pull down to refresh the news feed.
- Tap the app title to toggle between dark and light theme.

---

## Known Issues

- Location permission is required for country-specific news.
- Some news images may fail to load depending on source availability.
- Offline support is not yet implemented.

---

## Planned Features

- Offline caching of news articles.
- Push notifications for breaking news.
- Additional authentication options (Facebook, Twitter).

---

## API

This app uses the [NewsAPI]

---

## Getting Started

### Prerequisites

- Flutter SDK installed ([Flutter installation guide](https://flutter.dev/docs/get-started/install))
- Firebase project setup with Authentication enabled
- An API key from NewsAPI


