# Snooze Space v2

A hostel-style rental service where students can book rooms for naps, overnight stays, and study sessions. Users can also order food, receive wake-up calls, and manage bookings through the website. We are mainly encouraged by the idea that most students of BRACU have a long gap in between their classes. Many of them need a resting place for that time being. SnoozeSpace is our small solution to that problem. The name SnoozeSpace combines Snooze, which represents short naps and relaxation, and Space, which signifies a designated area. Together, it conveys the idea of a restful and comfortable environment tailored for students who need a break between classes.

## Overview

Snooze Space v2 is a modern, full-stack application built with React and Node.js that aims to develop a comprehensive web application that addresses the accommodation needs of BRAC University students. By offering flexible booking options, additional services, and secure user management, the project seeks to enhance student well-being and productivity. The proposed solution is feasible within the given timeframe and resources, and it promises significant benefits for students, the university, and the development team.

## **Features**

- User authentication with Firebase
- Real-time sleep tracking and logging
- Sleep schedule management
- Reminder notifications
- Sleep analytics and insights
- Responsive design with mobile support
- Clean and intuitive user interface
- Data persistence with MongoDB

## Tech Stack

### Frontend
- React 18.3.1
- Vite 5.4.10 (build tool)
- React Router DOM 6.28.0
- Tailwind CSS 3.4.15
- DaisyUI 4.12.14
- Firebase 11.0.2 (Authentication)
- Axios 1.7.9 (HTTP client)
- React Burger Menu 3.0.9 (Navigation)
- React SweetAlert2 0.6.0 (Alerts)

### Backend
- Node.js
- Express 4.21.2 (Web framework)
- MongoDB 6.12.0 (Database)
- CORS 2.8.5 (Cross-origin support)
- Dotenv 16.4.7 (Environment management)

### Development Tools
- ESLint (Code linting)
- PostCSS (CSS processing)
- Autoprefixer (Browser compatibility)


## Getting Started with Snooze Space 

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or Atlas cloud)
- Firebase account

### Installation

1. Clone the repository
```bash
git clone https://github.com/MoontasirM/Snooze-Space-v2.git
cd Snooze-Space-v2
```
**Install client dependencies**
```bash
cd Snooze_Space-Client
npm install
```
**Install server dependencies**
```bash
cd ../Snooze_Space-Server
npm install
```

### Configuration

1. Create a .env file in the Snooze_Space-Server directory
```
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```
2. Configure Firebase in your client application with your Firebase credentials
3. Install Firebase CLI tools globally (optional)

Configure Firebase in your client application with your Firebase credentials
```bash
npm install -g firebase-tools
```
### Available Scripts

## Client Scripts (Snooze_Space-Client)
```
-npm run dev - Start development server with hot reload
```
```
-npm run build - Build for production
```
```
-npm run preview - Preview production build
```
```
-npm run lint - Run ESLint to check code quality
```
## Server Scripts (Snooze_Space-Server)
```
-npm start - Start the production server
```
```
-npm run dev - Start development server with auto-restart (nodemon)
```
```
-npm test - Run tests (currently not configured)
```
### Development
To contribute to this project, please follow these guidelines:

1. Fork the repository
2. Create a feature branch (git checkout -b feature/your-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin feature/your-feature)
5. Open a Pull Request

### Support
For issues, feature requests, or questions, please open an issue on the GitHub repository.

### Author
Created by MoontasirM

### Repository
GitHub: https://github.com/MoontasirM/Snooze-Space-v2





