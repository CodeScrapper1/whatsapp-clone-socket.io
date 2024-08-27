## 🚨 Tutorial

This repository contains the corresponding tutorial available on our YouTube channel, <a href="https://www.youtube.com/@CodeScrapperOfficial/videos" target="_blank"><b>Code Scrapper</b></a>.

## <a name="introduction">🤖 Introduction</a>

In this comprehensive tutorial, you’ll learn how to build a fully functional WhatsApp clone using React.js, Node.js, Socket.io, Tailwind css and Cloudinary. This step-by-step guide will walk you through the entire process, from setting up the frontend with React.js to implementing real-time messaging with Socket.io, managing media uploads with Cloudinary, and building a robust backend with Node.js.

## <a name="tech-stack">Tech Stack</a>

- React.js
- MongoDB
- Node js
- mantine UI
- Socket.io
- Mongoose ODM
- Tailwind Css

## <a name="quick-start">Integration and Installation Process</a>

Follow these steps to set up the project locally on your device.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)

**Clone backend**

```bash
git clone -b backend git@github.com:CodeScrapper1/whatsapp-clone-socket.io.git
cd backend
```

**Set Up backend Environment Variables**

Create a new file named `.env` in the backend of your project and add the following content:

```env
PORT=
FRONTEND_URL=http://localhost:3000
MONGODB_URL=
JWT_SECRET_KEY=
JWT_EXPIRE=
COOKIE_EXPIRE=
```

**Clone frontend**

```bash
git clone -b frontend git@github.com:CodeScrapper1/whatsapp-clone-socket.io.git
cd frontend
```

**Set Up frontend Environment Variables**

Create a new file named `.env` in the frontend of your project and add the following content:

```env
REACT_APP_BACKEND_URL="http://localhost:5000"
REACT_APP_CLOUDINARY_NAME=
```

**Installation**

Install dependencies using yarn:

```bash
yarn
```

**Running the Project using yarn**

```bash
yarn run dev
```
