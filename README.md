# 🕒 SmartClock

SmartClock is a smart clock web application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). It offers features such as real-time clock display, alarm management, notes, and more.

## 📂 Project Structure

```

SmartClock/
├── backend/            # Node.js + Express backend
│   ├── controllers/    # Logic for handling API requests
│   ├── models/         # Mongoose data models
│   ├── routes/         # Express routes
│   ├── config/         # Database and environment config
│   ├── server.js       # Main server file
│   └── ...
├── frontend/           # React frontend
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── pages/      # App pages (Home, Alarm, etc.)
│   │   ├── App.js
│   │   └── ...
│   ├── public/
│   ├── package.json
│   └── ...

````

## 🚀 Features

- Live clock display (digital and/or analog)
- Alarm setting and management
- Notes/reminders
- Responsive UI for both desktop and mobile
- RESTful API for alarm and note management

## 🧰 Technologies Used

- **Frontend**: React.js, Tailwind CSS (or any styling framework you use)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Others**: Axios, Dotenv, Cors, etc.

## 🔧 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/SmartClock.git
cd SmartClock
````

### 2. Backend Setup

```bash
cd backend
npm install
# Create a .env file and add your MongoDB URI
npm run dev
```

### 3. Frontend Setup

```bash
cd frontend
npm install
npm start
```

The frontend will run on `http://localhost:3000` and the backend on `http://localhost:5000` by default.

## 📌 Environment Variables

In the `backend/.env` file, include:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

## 📷 Screenshots

*(Insert screenshots of your app here if available)*

## ✨ Future Improvements

* User authentication
* Dark/light mode
* Notification support
* Sync with cloud services
* Progressive Web App (PWA) support

## 👤 Author

* Kien Duong Trung
* GitHub: [@kientech](https://github.com/kientech)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```

