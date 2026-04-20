# 📚 Lorie’s Library

Lorie’s Library is a cross-platform mobile app built with .NET MAUI that allows users to manage and track their personal book collections.

## 🚀 Features

* 🔐 User authentication (login & registration)
* 📖 Book collection management

  * Add books via ISBN lookup or manual entry
  * Edit book details (rating, notes, read status)
* 🔍 Search and filter your library
* 📊 Pagination and performance-optimized loading
* 🛠️ Admin tools

  * User management
  * Password reset
  * Data export (CSV)
* ⚙️ Settings

  * API base URL configuration
  * Cache management
  * Logout

## 📱 Platforms

* iOS (in progress for App Store submission)
* Android
* Windows

## 🧰 Tech Stack

### Mobile App

* .NET MAUI (.NET 10)
* MVVM (CommunityToolkit.MVVM)
* HttpClientFactory
* SecureStorage for tokens

### Backend API

* ASP.NET Core Web API (.NET 9)
* Entity Framework Core
* MariaDB
* JWT Authentication
* OpenTelemetry + Prometheus metrics

## 🔗 Related Resources

* Privacy Policy:
  https://yourusername.github.io/lories-library-site/privacy.html

* Support:
  https://yourusername.github.io/lories-library-site/support.html

## 🧪 Development Notes

* iOS builds require Xcode and a configured Apple Developer account
* API must be accessible over the network (not `localhost`) when testing on iOS devices/simulator
* HTTPS redirection may need to be disabled for local iOS testing

## 📌 Status

Actively under development and currently being prepared for iOS App Store submission.

## 📬 Contact

For support or questions, please use the Support link above.

---

Built with ❤️ using .NET MAUI
