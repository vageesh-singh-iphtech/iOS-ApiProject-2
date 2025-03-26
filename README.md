# iOS CRUD via API- Movies App

<img src="https://github.com/user-attachments/assets/4dd43ec4-9e48-476e-a175-03453b908047" width="100" height="100" alt="Screenshot 1" style="margin-right: 10px;" /> 
<img src="https://github.com/user-attachments/assets/3615d89e-4499-4210-a283-d07380e2230a" width="150" height="100" alt="Screenshot 2" />

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
   git clone https://github.com/vageesh-singh-iphtech/ApiDemo-prj-2.git

# 🎮 Usage
- Signup/Login
- Register a new account or log in.
- User session is saved in UserDefaults.
- Profile
- View or edit your profile details.
- Update your profile picture with UIImagePickerController.
- Movies List
- Browse Marvel movies in a custom table view.
- See movie titles, release years, and posters.
- Logout
- End your session and return to the login screen.
# 📸 Screenshots
https://github.com/user-attachments/assets/c9dd5b45-3cdd-4083-bfd3-944a8f43df37


# 🛠️ Technologies Used
- Swift 5: Core programming language.
- UIKit: For crafting the UI.
- URLSession: For API communication.
- Codable: For JSON parsing simplicity.
- UserDefaults: For session persistence.
- UIImagePickerController: For image selection.
# ⚠️ Error Handling
- Graceful alerts for network failures or JSON issues.
- Custom loader to keep users informed during API calls.
# 🔮 Future Enhancements
- Expand API with movie details and favorites.
- Add caching for faster movie list loading.
- Spice up the UI with animations.

# 💫 About Me:
I'm currently working on swift iOS.<br>I'm in learning phase.<br>


# 💻 Tech Stack:
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Swift](https://img.shields.io/badge/swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=vageesh-singh-iphtech&theme=dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=vageesh-singh-iphtech&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=vageesh-singh-iphtech&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=vageesh-singh-iphtech&theme=shadow_green&no-frame=false&no-bg=true&margin-w=4)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=vageesh-singh-iphtech&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=vageesh-singh-iphtech&icon=0&color=0)](https://visitcount.itsvg.in)

  ## 💰 You can help me by Donating
  [![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/vageesh-singh-iphtech) 

  
<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
