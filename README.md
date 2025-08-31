# 🎶 React Module Federation - Music MFE Assignment

This project demonstrates **Micro Frontend (MFE)** architecture using **React + Webpack Module Federation**.  
It consists of two separate applications:

1. **Main App (Host)** → Loads the remote micro frontend.  
2. **Music MFE (Remote)** → Provides a Music Library component exposed to the host.  

---

## 📂 Project Structure
```bash
FinacPlus/
│── main-app/          # Host application (container)
│   ├── src/
│   │   └── App.js
│   ├── webpack.config.js
│   └── package.json
│
│── music-lib/      # Remote micro-frontend
│   ├── src/
│   │   └── MusicLibrary.js
│   ├── webpack.config.js
│   └── package.json
```
## 🚀 Getting Started
### 1️⃣ Clone the repo & install dependencies
 ```bash
git clone <repo-url>
```
Install dependencies for both apps:
```bash
cd main-app
npm install
cd ../music-lib
npm install
```
### 2️⃣ Run the apps
```bash
First, start the musicLibrary (remote):
cd music-lib
npm run dev
```
```bash
Then, start the main-app (host) in another terminal:
cd main-app
npm start
```



