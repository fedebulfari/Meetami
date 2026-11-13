# Meetami
[![Netlify Status](https://api.netlify.com/api/v1/badges/9d2636cf-2f1e-4c12-91cb-15cb2206c714/deploy-status)](https://app.netlify.com/projects/meetami/deploys)

Welcome to **Meetami**! This repository contains the source code and configuration for the Meetami web application. It is built as a lightweight, fast-loading static web project ready for seamless deployment on Netlify.

## 1. 🚀 Features

* **Single-Page Architecture:** Everything runs smoothly out of a streamlined `index.html` entry point.
* **Zero-Config Deployment:** Pre-configured with `netlify.toml` for continuous deployment, custom headers, or redirect rules on Netlify.
* **Fast & Responsive:** Designed to work cleanly across desktop and mobile browsers without heavy build-step overhead.

*(Note: Feel free to update this section with specific features of Meetami once you unpack the `index.html` file!)*

---

## 2. 📂 Project Structure

```text
Meetami/
├── index.html      # Main application entry point (HTML, styles, and scripts)
├── netlify.toml    # Netlify deployment configuration
└── README.md       # Project documentation
```

---

## 3. 🛠️ Getting Started

Because this project is a static web application, you do not need to install complex dependencies to run it locally.

### 3.1. Prerequisites

* A modern web browser (Chrome, Firefox, Safari, Edge)
* *(Optional)* A local development server (like the VS Code **Live Server** extension, Python's `http.server`, or `npx serve`)

### 3.2. Running Locally

1. **Clone or extract the repository:**
   ```bash
   git clone https://github.com/your-username/Meetami.git
   cd Meetami
   ```

2. **Open the project:**
   * **Direct method:** Simply double-click `index.html` to open it in your default browser.
   * **Local server method (Recommended):**
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # OR using Node.js
     npx serve .
     ```
     Then navigate to `http://localhost:8000` (or the port shown in your terminal).

---

## 4. 🌐 Deployment (Netlify)

This project includes a `netlify.toml` file for automated configuration on [Netlify](https://www.netlify.com/).

### 4.1. Deploy via Git
1. Push this repository to GitHub, GitLab, or Bitbucket.
2. Log in to your Netlify account and click **"Add new site" > "Import an existing project"**.
3. Select your repository. Netlify will automatically detect the settings from `netlify.toml` and deploy your site.

### 4.2. Deploy via Netlify CLI
If you have the [Netlify CLI](https://docs.netlify.com/cli/get-started/) installed, you can deploy directly from your terminal:
```bash
netlify deploy --prod
```

---

## 5. 🤝 Contributing

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 6. 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
