
# MiniChatApp 🗨️

A minimal real-time chat application built with **Node.js**, **Express**, and **EJS**. This app allows users to send and receive messages instantly in a simple chat interface.([GitHub][1])

## 🚀 Features

* Real-time messaging with Socket.IO
* User-friendly interface using EJS templates
* Modular code structure for scalability
* Static assets served from the `public` directory

## 🛠️ Tech Stack

* **Backend**: Node.js, Express.js
* **Templating Engine**: EJS
* **Frontend**: HTML, CSS, JavaScript

## 📁 Project Structure

```
backend-minichatapp/
├── models/             # Data models (if any)
├── public/             # Static assets (CSS, JS, images)
├── views/              # EJS templates
├── index.js            # Main server file
├── init.js             # Initialization scripts
├── package.json        # Project metadata and dependencies
└── package-lock.json   # Exact dependency versions
```



## 🔧 Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/shivasky10/backend-minichatapp.git
   cd backend-minichatapp
   ```



2. **Install dependencies**:

   ```bash
   npm install
   ```



3. **Start the server**:

   ```bash
   node index.js
   ```



The server will start on `http://localhost:3000` by default.

## 💡 Usage

* Open your browser and navigate to `http://localhost:3000`.
* Enter your name to join the chat.
* Start sending and receiving messages in real-time!
