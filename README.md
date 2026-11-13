# Meetami
[![Netlify Status](https://api.netlify.com/api/v1/badges/9d2636cf-2f1e-4c12-91cb-15cb2206c714/deploy-status)](https://app.netlify.com/projects/meetami/deploys)

**Meetami** is a lightweight, zero-login multi-team meeting scheduler designed to effortlessly coordinate schedules across different teams using unique private links and interactive time grids.

Live deployment: [https://meetami.netlify.app/](https://meetami.netlify.app/)

## 🚀 Key Features

* **No Login Required:** Create a private room instantly and share the unique URL with your team.
* **Interactive Grid Scheduling:** A clean 7-day × 16-hour grid (08:00 — 24:00) optimized for both desktop and mobile. Drag across time slots to mark your availability.
* **Smart Overlap Detection:** Instantly spot optimal meeting times highlighted with highest overlap and top-slot markers.
* **Participant Management:** Track who has joined, view individual availability, and tap cells to inspect who is free at specific times.
* **Zero-Config Deployment:** Ready for instant static hosting and continuous deployment via Netlify.

## 📂 Project Structure

```
Meetami/
├── index.html      # Complete single-page application (HTML, CSS, and Client Logic)
├── netlify.toml    # Netlify hosting & routing configuration
└── README.md       # Project documentation
```

## 🛠️ Getting Started Locally

Since Meetami is built as a lightning-fast static web app, running it locally requires no complex backend or package manager installations.

### Prerequisites
* Any modern web browser (Chrome, Firefox, Safari, Edge)
* *(Optional)* A local server like VS Code Live Server or Python's HTTP server.

### Running the App
1. Clone or download the repository:
   ```bash
   git clone https://github.com/your-username/meetami.git
   cd meetami
   ```
2. Open `index.html` directly in your browser, or spin up a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   ```
3. Navigate to `http://localhost:8000` to start scheduling!

## 🌐 Deployment

This project is configured out-of-the-box for [Netlify](https://www.netlify.com/).

### Deploy via Netlify CLI
If you have the Netlify CLI installed:
```bash
netlify deploy --prod
```

### Deploy via Git
1. Push your repository to GitHub, GitLab, or Bitbucket.
2. Link the repository in your Netlify dashboard. Netlify will automatically detect the static build settings and publish your live app.

## 🤝 Contributing
Contributions, bug reports, and feature suggestions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License
Distributed under the MIT License. See `LICENSE` for more details.
