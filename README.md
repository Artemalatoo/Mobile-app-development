# Product Store App

## Overview

Product Store App is a mobile application developed using **Flutter** and **Dart**.
The project demonstrates how to connect a Flutter application to a backend API, display a list of products, and open a detailed product page.

The application uses data from the mock API:

**https://dummyjson.com/products**

## Features

* Fetch product data from backend API
* Display products in a scrollable list
* Show product image, title, and price
* Open detailed product page
* Clean and simple user interface
* Navigation between pages

## Technologies Used

* **Language:** Dart
* **Framework:** Flutter
* **HTTP Requests:** http package
* **Backend Source:** DummyJSON API

## Project Structure

```text
lib/
 └── main.dart
```

## How It Works

1. The app sends a GET request to the DummyJSON API.
2. Product data is received in JSON format.
3. The JSON data is converted into Product objects.
4. Products are displayed in a list view.
5. When the user taps a product, a detail page opens.

## Installation

1. Open the project in Flutter or FlutLab.
2. Add dependencies in `pubspec.yaml`
3. Run:

```bash
flutter pub get
flutter run
```

## Example Pages

* Product List Page
* Product Detail Page

## Purpose of the Project

This project was created for the **Mobile Application Development Course** to practice:

* Flutter UI development
* API integration
* Navigation between screens
* Working with JSON data
* Mobile app architecture

## Author

Brian
# Mobile-app-development
