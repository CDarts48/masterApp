# masterApp
A web application designed to manage and display team information and match data, built with Node.js and Express.js.

---

## ✨ Features

- Display team details and match schedules
- Update match results and team standings
- Responsive design for various devices

---

## ✅ Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Docker](https://www.docker.com/) (optional, for containerized deployment)

---

## 🛠️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/CDarts48/masterApp.git
   cd masterApp
Install dependencies
npm install
▶️ Running the Application
🔹 Using Node.js
Start the application:

npm start
By default, the app runs at:
http://localhost:3000

🐳 Using Docker
Build the Docker image

docker build -t masterapp .
Run the Docker container


docker run -p 3000:3000 masterapp
Open in your browser at:
http://localhost:3000

📁 Project Structure

masterApp/
├── App.js                # Main Express app
├── Dockerfile            # Docker configuration
├── fly.toml              # Fly.io deployment config
├── package.json          # Project metadata and scripts
├── views/                # EJS templates
├── Team.js               # Handles team-related routes
├── matches.js            # Match data and routes
├── mainPage.js           # Main page rendering
└── updateSheet.js        # Sheet updates logic

🚀 Deployment 


📜 License
This project is licensed under the Apache 2.0 License.

🙌 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📬 Contact
Maintained by CDarts48
Feel free to reach out for feedback or questions.
