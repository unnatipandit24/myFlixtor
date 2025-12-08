
# myFlixtor – Mobile Movie App

myFlixtor is a modern **React Native mobile application** designed to explore trending movies, search titles, and view detailed information through a clean and intuitive interface.
The app is powered by **BaaS (Backend-as-a-Service)** using **Appwrite**, enabling smooth authentication, database management, and cloud operations without maintaining your own backend.

---

##  Features

a. Browse trending & popular movies

b. Powerful search system

c. Detailed movie information

d. API-based real-time updates

e. Clean & modern UI with Tailwind (NativeWind)

f. Cross-platform support (Android & iOS)

g.  BaaS integration using Appwrite

---

##  Tech Stack

### **Frontend**

* **React Native (Expo)**
* **TypeScript**
* **NativeWind (Tailwind CSS)**
* **Expo Router**

### **Backend (BaaS)**

* **Appwrite** — used as a **Backend-as-a-Service** for:

  * Database
  * Collections (Tables)
  * Document management
  * API endpoints
  * Cloud functionality
  * Secure data storage

### **External APIs**

* **TMDB API** — for all movie data

---

##  Project Structure

```
myFlixtor/
│
├── app/               // Navigation & screens
├── components/        // Reusable UI components
├── services/          // API logic & BaaS (Appwrite) integration
├── constants/         // Icons & images
├── interfaces/        // TypeScript models
├── assets/            // Images & fonts
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/unnatipandit24/myFlixtor.git
cd myFlixtor
```

---

### 2️. Install Dependencies

```bash
npm install
```

---

### 3️. Create Environment Variables

Create a `.env` file:

```env
EXPO_PUBLIC_APPWRITE_ENDPOINT=your_endpoint_here
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_project_id_here
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_database_id_here
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_collection_id_here
EXPO_PUBLIC_TMDB_API_KEY=your_tmdb_api_key_here
```

> ⚠️ Ensure `.env` is added to `.gitignore` because it contains private keys.

---

### 4. Start the Project

```bash
npx expo start
```

Open on Expo Go or emulator.

---

## 📱 Screens & Flow

* **Home Screen** → Trending & Popular Movies
* **Search Screen** → Live search with API
* **Details Screen** → Overview, ratings, posters

---

## 💡 What I Learned

This project strengthened my skills in:

* Mobile-first UI development
* TypeScript in React Native
* API integration
* Building scalable frontend architecture
* Using **Appwrite (BaaS)** for real backend features without writing server code
* Designing reusable components & hooks

---

## 👩‍💻 Author

**Unnati Pandit**
React Native Developer • Android Developer 
