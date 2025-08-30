# SocialSync

A modern language exchange and chat platform built with React, Vite, Node.js, Express, and MongoDB. SocialSync helps users connect with language partners, chat in real-time, and make friends worldwide.

---

## Features

-  **Language Exchange:** Find and connect with users learning or speaking your target language.
-  **Real-Time Chat:** 1:1 messaging powered by [Stream Chat](https://getstream.io/chat/).
-  **Video Calls:** Start instant video calls with your friends using [Stream Video](https://getstream.io/video/).
-  **Authentication:** Secure signup, login, and onboarding flow.
-  **Friend Requests:** Send, accept, and manage friend requests.
-  **Profile Customization:** Set your bio, languages, location, and avatar.
-  **Themes:** 30+ beautiful themes with [daisyUI](https://daisyui.com/) and Tailwind CSS.
-  **Notifications:** Get notified about friend requests and new connections.
-  **Fast & Responsive:** Built with Vite, React 19, and Tailwind CSS for a snappy UX.

---

## Demo

![Screenshot](./public/screenshot-for-readme.png)

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- [Stream API Keys](https://getstream.io/)

### 1. Clone the Repository

```sh
git clone https://github.com/Adnan8101/Social_Sync.git
cd Social_Sync-main
```

### 2. Setup Environment Variables

Create a `.env` file in the `backend/` directory with the following:

```env
PORT=5001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET_KEY=your_jwt_secret
STEAM_API_KEY=your_stream_api_key
STEAM_API_SECRET=your_stream_api_secret
NODE_ENV=development
```

> **Note:** Get your Stream API keys from [Stream Dashboard](https://getstream.io/dashboard/).

### 3. Install Dependencies

```sh
# Install root, backend, and frontend dependencies
npm run build
```

### 4. Run the App

#### Start Backend

```sh
cd backend
npm run dev
```

#### Start Frontend

Open a new terminal:

```sh
cd frontend
npm run dev
```

- Frontend: [http://localhost:5173](http://localhost:5173)
- Backend: [http://localhost:5001](http://localhost:5001)

---

## Project Structure

```
SocialSync-main/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── lib/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── constants/
│   │   ├── hooks/
│   │   ├── lib/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   ├── tailwind.config.js
│   └── package.json
│
├── package.json
└── .gitignore
```

---

## Tech Stack

- **Frontend:** React 19, Vite, Tailwind CSS, daisyUI, Zustand, React Query, Stream Chat/Video
- **Backend:** Node.js, Express, MongoDB, Mongoose, JWT, Stream Chat SDK
- **Other:** ESLint, PostCSS, Hot Toast, Lucide Icons

---

## Author

- **Adnan8101**  
  [GitHub Profile](https://github.com/Adnan8101)

---

## License

This project is licensed under the ISC License.

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## Acknowledgements

- [Stream](https://getstream.io/)
- [Vite](https://vitejs.dev/)
-
