# Ojaswi's Summer 2025 Dashboard

A comprehensive personal dashboard for tracking learning progress (Web Development & AI/ML), fitness goals with calorie tracking, and vacation planning. Built with React.js and deployed on Vercel.

## 🚀 Features

- **Learning Hub**: Track Web Development and AI/ML learning progress with interactive checklists
- **Fitness Tracker**: Complete fitness management with calorie tracking, macro monitoring, workout logging, and progress visualization
- **Vacation Planner**: Comprehensive vacation planning with checklists, budget tracking, and itinerary management
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices
- **Real-time Updates**: Interactive progress bars and dynamic data visualization

## 🛠️ Tech Stack

- **Frontend**: React.js 19.1.0
- **Routing**: React Router DOM
- **Styling**: CSS3 with responsive design
- **Deployment**: Vercel
- **Version Control**: Git & GitHub

## 📋 Prerequisites

Before running this project locally, ensure you have the following installed:

- **Node.js** (version 14 or higher)
- **npm** (comes with Node.js)
- **Git** (for cloning the repository)
- **Code Editor** (VS Code recommended)

### Check Your Installation

```bash
node --version
npm --version
git --version
```

## 🔧 Installation & Setup

### For All Operating Systems (Windows, Linux, Mac)

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AyanKhanCSE/ojaswi-dashboard.git
   cd ojaswi-dashboard
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Install React Router DOM**
   ```bash
   npm install react-router-dom
   ```

4. **Start the Development Server**
   ```bash
   npm start
   ```

5. **Open in Browser**
   - The application will automatically open at `http://localhost:3000`
   - If it doesn't open automatically, manually navigate to the URL

## 🖥️ Platform-Specific Instructions

### Windows
- Use Command Prompt, PowerShell, or Git Bash
- Navigate using `cd` commands
- Example: `cd Desktop\ojaswi-dashboard`

### Linux/Ubuntu
- Use Terminal
- Navigate using `cd` commands
- Example: `cd ~/Desktop/ojaswi-dashboard`

### macOS
- Use Terminal
- Navigate using `cd` commands
- Example: `cd ~/Desktop/ojaswi-dashboard`

## 📁 Project Structure

```
ojaswi-dashboard/
├── public/
│   └── index.html
├── src/
│   ├── App.js                 # Main application component
│   ├── App.css               # Global styles
│   ├── index.js              # Application entry point
│   ├── LearningDashboard.js  # Learning progress tracking
│   ├── FitnessDashboard.js   # Fitness and health tracking
│   └── VacationDashboard.js  # Vacation planning tools
├── package.json              # Dependencies and scripts
├── vercel.json              # Vercel deployment configuration
└── README.md                # This file
```

## 🚨 Common Issues & Solutions

### Issue 1: "npm start" shows "Missing script: start"
**Solution**: You're not in the correct directory. Navigate to the project root where `package.json` exists.

### Issue 2: Blank white page after running npm start
**Solution**: Check browser console (F12) for errors. Usually caused by missing dependencies or syntax errors.

### Issue 3: "Invalid hook call" error
**Solution**: Version mismatch between React packages. Run:
```bash
rm -rf node_modules
rm package-lock.json
npm install
npm install react-router-dom
```

### Issue 4: Cannot find module 'react-router-dom'
**Solution**: Install the missing dependency:
```bash
npm install react-router-dom
```

### Issue 5: Port 3000 already in use
**Solution**: Either stop the existing process or use a different port:
```bash
npm start -- --port 3001
```

## 🌐 Live Demo

The dashboard is deployed and available at: [https://ojaswi-dashboard.vercel.app/](https://ojaswi-dashboard.vercel.app/)

## 📱 Usage

1. **Learning Hub**: 
   - Track your Web Development and AI/ML learning progress
   - Check off completed tasks
   - Monitor weekly study hours

2. **Fitness Tracker**:
   - Log daily calories and macronutrients
   - Track workouts and water intake
   - Monitor progress with visual indicators

3. **Vacation Planner**:
   - Manage pre-travel checklists
   - Track budget and expenses
   - Plan daily itineraries

## 🔄 Available Scripts

- `npm start` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm run eject` - Ejects from Create React App (irreversible)

## 🚀 Deployment

This project is configured for easy deployment on Vercel:

1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Deploy automatically with the included `vercel.json` configuration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Ojaswi Prashant**
- GitHub: [@AyanKhanCSE](https://github.com/AyanKhanCSE)

## 🙏 Acknowledgments

- Built with [Create React App](https://create-react-app.dev/)
- Deployed on [Vercel](https://vercel.com/)
- Icons and styling inspiration from modern dashboard designs

---

**Note**: This dashboard uses browser state management. Data will reset on page refresh. For persistent data storage, consider implementing localStorage or a backend database.

Citations:
[1] https://create-react-app.dev/docs/getting-started/
[2] https://www.noobsplanet.com/threads/get-react-running-on-your-mac-a-step-by-step-guide.12/
[3] https://stackoverflow.com/questions/46506332/run-simple-react-js-in-browser-locally
[4] https://www.uxpin.com/studio/blog/how-to-run-react-app-loacally/
[5] https://code.visualstudio.com/docs/nodejs/reactjs-tutorial
[6] https://www.digitalocean.com/community/tutorials/deploy-react-application-with-nginx-on-ubuntu
[7] https://learn.microsoft.com/en-us/windows/dev-environment/javascript/react-beginners-tutorial
[8] https://www.youtube.com/watch?v=yOAZDymGWVw
[9] https://stackoverflow.com/questions/72647395/why-is-my-react-app-not-loading-on-localhost
[10] https://learn.microsoft.com/en-us/windows/dev-environment/javascript/react-on-windows

---
Answer from Perplexity: pplx.ai/share
