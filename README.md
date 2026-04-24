# Firebase Studio

This is a NextJS starter in Firebase Studio.

To get started, take a look at src/app/page.tsx.
Since your project includes the `.env` file directly and doesn't use Firebase Auth, I have customized this `README.md` to be "plug-and-play."

Copy the text below and save it as a file named **`README.md`** in your project's main folder.

---

```markdown
# Firebase Studio Project

This software is a Firebase-integrated application. It is pre-configured to connect to the backend using the included environment variables.

## 🛠️ Prerequisites

Before running the software, ensure you have the following installed:

1. **Node.js (LTS Version):** [Download here](https://nodejs.org/)
   * *To check if installed, type `node -v` and `npm -v` in your terminal.*
2. **Code Editor:** [VS Code](https://code.visualstudio.com/) is recommended.

## 🚀 How to Run (Local Environment)

Follow these steps exactly to get the project running on your local machine:

### 1. Extract the Project
If you received this as a zip file, extract it to a folder on your Desktop or Documents.

### 2. Environment Configuration
The project already includes a `.env` file containing the necessary API keys. 
* **Note:** If you cannot see the file, it might be hidden by your OS. Ensure your folder settings are set to "Show Hidden Files."
* This project uses Firestore/Realtime Database but **does not** require Firebase Authentication.

### 3. Install Dependencies
Open your terminal (Command Prompt, PowerShell, or VS Code Terminal) inside the project folder and run:
```bash
npm install

```

*This will create the `node_modules` folder and download all required libraries. This may take a minute.*

### 4. Launch the App

Once the installation is complete, run:

```bash
npm start

```

The application will automatically open in your default browser at: **http://localhost:3000**

---

## 📁 Key Files in this Repository

* `.env` - Contains the Firebase Project API keys and Database URL.
* `src/` - Contains the main logic and UI components of the software.
* `package.json` - Lists the dependencies and scripts for the project.
* `firebase.json` - Firebase hosting and emulator configuration.

## ⚠️ Troubleshooting

* **'npm' is not recognized:** This means Node.js is not installed or your terminal needs to be restarted.
* **Permission Denied:** If the app loads but shows no data, ensure the Firebase Database rules are set to "Test Mode" or allow public read/write.
