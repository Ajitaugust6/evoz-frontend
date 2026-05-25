---

### Frontend Repository (`evoz-frontend/README.md`)

```markdown
# ⚡ Evoz User Management - Frontend Client

A lightweight, responsive web client for the Evoz User Management system. This frontend communicates seamlessly with the Spring Boot backend via REST APIs.

## 🛠️ Tech Stack
* **Markup & Styling:** HTML5, CSS3
* **Logic:** Vanilla JavaScript (ES6+)
* **Network:** Fetch API

## ✨ Features
* **Tabbed Interface:** Clean, single-page application (SPA) feel utilizing a responsive tab system for navigation.
* **Dynamic Table:** Renders user data seamlessly with built-in pagination controls.
* **Live Search:** Allows administrators to filter the user database by keywords dynamically.
* **Configurable Base URL:** Features a UI input to easily switch the backend API URL (useful for moving between `localhost` and a production server).
* **Real-time Notifications:** Provides color-coded UI alerts (Success/Error) based on HTTP response statuses.

## 🚀 Getting Started

Because this is a vanilla HTML/JS project, there are no heavy node modules or build steps required.

### Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/evoz-frontend.git](https://github.com/YOUR_USERNAME/evoz-frontend.git)
Run the Application:

Option A: Simply double-click the index.html file to open it directly in your web browser.

Option B (Recommended for Development): Use an extension like "Live Server" in VS Code to run it on a local development port.

Connecting to the Backend
Ensure the Evoz Backend API is running locally on port 8080.

Open the frontend in your browser.

The Backend URL input box is set to http://localhost:8080 by default. If your backend is hosted elsewhere, update this field before making requests.

📸 Interface Sections
Register: Add a new user to the database.

Login: Verify credentials against the backend.

User List: View, search, and paginate through the database.

Update: Modify existing user information.

Delete: Remove users from the system permanently.


*(Note: Don't forget to replace `YOUR_USERNAME` in the clone links with your actual GitHub username!)*
