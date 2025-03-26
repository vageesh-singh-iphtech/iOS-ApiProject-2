# iOS CRUD via API- Movies App

A sleek, Swift-based iOS app that connects to a custom API for user authentication and displays a stylish list of Marvel movies. Built with modern Swift practices, it features Codable for JSON parsing, custom UI components, and a polished user experience.

---

## ✨ Features

- **User Authentication**  
  - Secure signup, login, profile updates, and logout.  
  - Persistent sessions with `UserDefaults`.

- **API Integration**  
  - Custom API for user management and movie data.  
  - Effortless JSON handling with `Codable`.

- **UI Components**  
  - Custom table view cells showcasing movie title, year, and poster.  
  - Profile image picker via `UIImagePickerController`.  
  - Smooth navigation across login, signup, profile, and movie screens.

- **Utilities**  
  - Custom loader for network activity feedback.  
  - User-friendly error alerts for network or parsing issues.

---

## 📂 Project Structure

- **Networking Layer**: API calls powered by `URLSession` and a reusable `APIService`.  
- **Models**: Clean `Codable` structs for User and Movie data.  
- **UI**: View controllers for authentication, profile, and movie list with custom cells.  
- **Utilities**: Loader and session management with `UserDefaults`.

---

## 🌐 API Endpoints

| Action          | Method | Endpoint            |
|-----------------|--------|---------------------|
| Signup          | POST   | `/api/signup`       |
| Login           | POST   | `/api/login`        |
| Update Profile  | PUT    | `/api/user/update`  |
| Logout          | POST   | `/api/logout`       |
| Movies List     | GET    | `/api/movies`       |

*Note: Replace the base URL with your API’s actual base URL.*

---

## 🚀 Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/marvel-movies-app.git
