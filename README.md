# ⚽ Premier League Notifier

An Android app built using **Kotlin**, **Jetpack Compose**, and the **football-data.org API** that keeps you updated on upcoming Premier League matches and results for your favorite team.

---

## 📱 Features

- View upcoming matches in the next 30 days
- Select your favorite team and view recent results
- Smooth screen navigation with Jetpack Navigation
- Fetches real-time match data using Retrofit
- Clean, modern UI using Jetpack Compose

---

## 🛠 Built With

- **Kotlin**
- **Jetpack Compose**
- **Jetpack Navigation**
- **Retrofit2**
- **MVVM Architecture**
- **Football-Data.org API**

---

## 📂 Folder Structure

```
com.example.premierleague_notifier/
├── MainActivity.kt
├── navigation/
│   └── AppNavigation.kt
├── data/
│   ├── model/
│   │   └── Match.kt
│   └── network/
│       ├── ApiService.kt
│       └── RetrofitInstance.kt
├── viewmodel/
│   └── MatchViewModel.kt
├── ui/
│   ├── screen/
│   │   ├── MatchListScreen.kt
│   │   └── FavoriteTeamScreen.kt
│   └── theme/
│       ├── Color.kt
│       ├── Theme.kt
│       └── Type.kt
```

---

## 🧰 Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/Alex250801/Premier-League-Notifier-App.git
   cd Premier-League-Notifier-App
   ```

2. **Open the project in Android Studio**

3. **Insert your API key**

   - Sign up at [football-data.org](https://www.football-data.org)
   - Copy your API key
   - Paste it into `ApiService.kt`:

     ```kotlin
     @Headers("X-Auth-Token: YOUR_API_KEY")  // Replace with your key
     ```

4. **Sync Gradle and Run**

   - File → Sync Project with Gradle Files
   - Press ▶️ to build & run

---

