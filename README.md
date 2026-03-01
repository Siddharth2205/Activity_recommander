# 🎯 Activity Recommender

> Discover activities tailored to your mood and interests — a Flutter web app deployed on Vercel.

![Live](https://img.shields.io/badge/Live-activity--recommander.vercel.app-brightgreen?style=flat-square)
![Framework](https://img.shields.io/badge/Framework-Flutter-blue?style=flat-square)
![Language](https://img.shields.io/badge/Language-Dart-teal?style=flat-square)
![Deployed](https://img.shields.io/badge/Deployed-Vercel%20%2F%20GitHub%20Pages-black?style=flat-square)

🌐 **Live Demo:** [activity-recommander.vercel.app](https://activity-recommander.vercel.app)

---

## 📖 About

**Activity Recommender** is a Flutter web application that suggests personalized activities based on user preferences. Whether you're bored, looking for something to do outdoors, or want a creative indoor activity, the app curates relevant recommendations for you. Built with Flutter for web and deployed on both Vercel and GitHub Pages.

---

## ✨ Features

- 🎲 **Personalized Suggestions** — Get activity recommendations tailored to your input
- 🌐 **Web-Based** — Runs entirely in the browser, no installation needed
- 📱 **Responsive UI** — Flutter's cross-platform rendering ensures a smooth experience on any screen size
- ⚡ **Fast Loading** — Optimized Flutter web build with service worker caching
- 🎨 **Clean Design** — Minimal, modern interface powered by Flutter's Material Design

---

## 🚀 Try It Out

Visit the live app: **[activity-recommander.vercel.app](https://activity-recommander.vercel.app)**

1. Open the app in your browser
2. Select or enter your preferences/mood
3. Browse the recommended activities
4. Pick one and get going!

---

## 🗂️ Project Structure

```
Activity_recommander/
├── assets/                     # App assets (fonts, images)
├── canvaskit/                  # Flutter CanvasKit renderer
├── icons/                      # App icons
├── index.html                  # Flutter web entry point
├── main.dart.js                # Compiled Dart/Flutter app
├── flutter.js                  # Flutter web loader
├── flutter_bootstrap.js        # Bootstrap script
├── flutter_service_worker.js   # PWA service worker
├── manifest.json               # Web app manifest (PWA support)
└── version.json                # Build version info
```

---

## 🛠️ Built With

| Technology | Purpose |
|-----------|---------|
| Flutter | Cross-platform UI framework |
| Dart | Application logic |
| CanvasKit | High-fidelity Flutter web rendering |
| Vercel | Primary hosting & CDN |
| GitHub Pages | Secondary deployment (gh-pages branch) |

---

## 💻 Local Development

### Prerequisites

- Flutter SDK (3.x+)
- Dart SDK
- A web browser

### Setup & Run

```bash
# Clone the repository
git clone https://github.com/Siddharth2205/Activity_recommander.git
cd Activity_recommander

# Get Flutter dependencies
flutter pub get

# Run in web browser
flutter run -d chrome
```

### Build for Web

```bash
flutter build web
```

The output will be in the `build/web/` directory, ready to deploy to any static host.

---

## ☁️ Deployment

This app is deployed on **Vercel** from the `gh-pages` branch. To deploy your own:

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

Or connect your GitHub repository to Vercel for automatic deployments on every push.

---

## 🤝 Contributing

Have a feature idea or found a bug? Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Open a Pull Request

---

## 📧 Contact

**Siddharth Modi**
📬 [sidinregina@gmail.com](mailto:sidinregina@gmail.com)
🐙 [github.com/Siddharth2205](https://github.com/Siddharth2205)

---

⭐ Enjoying the app? Give this repo a star!
