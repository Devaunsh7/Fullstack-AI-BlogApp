# Fullstack-AI-BlogApp

[How to Build a Full Stack AI Powered Blog App using MERN Stack, Google Gemini and ImageKit API]


---


# Fullstack AI-Powered Blog App

Build a modern **AI-driven blog platform** using the **MERN stack**, **Google Gemini**, and **ImageKit API**

##  Features

- **Full-Stack MERN Architecture**
  - **MongoDB** for backend data storage
  - **Express.js** for building RESTful APIs
  - **React.js** for a reactive and dynamic frontend
  - **Node.js** as the runtime environment

- **AI-Powered Content Creation**
  - Integrated with **Google Gemini** to generate blog post drafts, ideas, and enhancements.

- **Dynamic Image Handling**
  - Uses **ImageKit API** to upload, store, and serve blog images with ease and performance optimization.

- **Core Blog Operations**
  - CRUD functionality: create, read, update, and delete blog posts
  - Image upload support for enriching posts

- **Optional Deployment Guidance**
  - Suitable for platforms like **Render**, **Heroku**, or **Vercel** (tutorial-style)

---

##  Demo Walkthrough

Follow along with the video tutorial where the app is built from scratch:

1. Setting up the **backend**—API routes and MongoDB schema
2. Implementing **AI integration** with Google Gemini
3. Handling **image uploads** via ImageKit API
4. Building the **frontend UI** in React
5. Connecting frontend APIs and enhancing with AI features
6. (Optional) Deploying your app live

---

##  Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- MongoDB (local or cloud)
- API credentials for:
  - **Google Gemini**
  - **ImageKit**

---

### Installation

```bash
# Clone the repository
git clone https://github.com/Devaunsh7/Fullstack-AI-BlogApp.git
cd Fullstack-AI-BlogApp

# Install dependencies (backend & frontend)
npm install
````

---

### Configuration

Create a `.env` file in the root directory with the following environment variables:

```
MONGODB_URI=<your_mongodb_connection_string>
GOOGLE_GEMINI_API_KEY=<your_google_gemini_api_key>
IMAGEKIT_PUBLIC_KEY=<your_imagekit_public_key>
IMAGEKIT_PRIVATE_KEY=<your_imagekit_private_key>
IMAGEKIT_URL_ENDPOINT=<your_imagekit_url_endpoint>
```

---

### Running Locally

```bash
# Start backend server
npm run server

# Start frontend in another terminal
npm run client
```

Then visit `http://localhost:3000` in your browser.

---

## Usage Guide

* **Create** a new blog post
* **Request** auto-generated suggestions/content via Google Gemini
* **Upload** or embed images through ImageKit
* **Edit** or **delete** existing posts
* Enjoy a seamless blogging experience enhanced with AI and optimized media delivery

---

## Folder Structure

```
├── backend/           # Express API & MongoDB logic
├── frontend/          # React application
├── .env               # Environment variables
├── README.md          # This documentation
└── package.json
```

---

## Deployment

To deploy your application:

1. Choose your platform (e.g., Render, Vercel, Heroku)
2. Set the appropriate env vars on the platform
3. Deploy both backend and frontend
4. Enjoy your live AI-powered blog!

---

## Contributing

Contributions are very welcome! Simply:

1. Fork the repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Make your enhancements
4. Commit your changes (`git commit -m 'Add new feature'`)
5. Push (`git push origin feature-name`)
6. Open a Pull Request

---

## License

MIT License — feel free to use, modify, and share!

---

## Acknowledgements

* Thanks to **Google Gemini** (AI compliance) and **ImageKit API** (media optimization)

---

### Tips for Enhancing This README

* Add **screenshots** or **live demo links** to showcase the UI
* Include **API endpoint documentation**
* Add **badge banners** (e.g., build status, license)
* Visualize tech stack with icons or diagrams

---

