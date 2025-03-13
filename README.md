# BookStoreApp 📚

Welcome to **BookStoreApp**, a full-stack application that provides a seamless platform for managing and purchasing books online. This project integrates a **Node.js** backend with a **React** frontend, utilizing modern technologies like **Tailwind CSS** for styling and **Vite** for building the frontend.

## ✨ Key Features

- **User Authentication**: Sign up and log in to manage your account and purchases.
- **Book Management**: Browse and search books with real-time updates.
- **Responsive Design**: The app is fully responsive and optimized for both desktop and mobile.
- **Modern UI**: Built using **React** and styled with **Tailwind CSS** for a clean and user-friendly interface.
- **REST API**: The backend exposes a RESTful API for seamless interaction with the frontend.

## 🛠 Technologies Used

### Backend
- **Node.js**: The runtime environment for the backend.
- **Express.js**: Web framework for building the REST API.
- **MongoDB**: Database for storing user and book data.
- **dotenv**: For managing environment variables.

### Frontend
- **React**: JavaScript library for building the user interface.
- **Vite**: Next-generation frontend build tool for fast and optimized builds.
- **Tailwind CSS**: Utility-first CSS framework for responsive design.

## 🚀 Getting Started

Follow the steps below to get up and running with **BookStoreApp** locally:

### Prerequisites

- **Node.js** (v14+ recommended)
- **npm** or **yarn**

### Installation

#### 1. Clone the repository

```bash
git clone https://github.com/Mohammed-Saqhib/BookStoreApp.git
cd BookStoreApp
```

#### 2. Set up the backend

Navigate to the `Backend` folder and install dependencies:

```bash
cd Backend
npm install
```

Create a `.env` file in the `Backend` folder and add your environment variables (e.g., database URL, JWT secret).

#### 3. Set up the frontend

Navigate to the `Frontend` folder and install dependencies:

```bash
cd Frontend
npm install
```

#### 4. Run the application

Start the backend server:

```bash
cd Backend
npm start
```

Start the frontend server:

```bash
cd Frontend
npm run dev
```

Visit `http://localhost:3000` in your browser to start using **BookStoreApp**.

## 📂 Project Structure

Here’s a brief overview of the project files and directories:

### Backend
- **`index.js`**: Main entry point for the backend.
- **`controller/`**: Handles business logic for API routes.
- **`model/`**: Contains the MongoDB schemas for books and users.
- **`route/`**: Defines API routes.
- **`.env`**: Stores sensitive environment variables (not shared).
  
### Frontend
- **`index.html`**: The main HTML file that loads the React app.
- **`src/`**: Contains the React components, pages, and logic.
- **`tailwind.config.js`**: Configures Tailwind CSS for the project.
- **`vite.config.js`**: Configures the Vite build tool.
  
## 📑 License

This project is licensed under the [MIT License](LICENSE).

## 💡 Acknowledgements

Special thanks to:
- **React** and **Node.js** for providing the foundation for this app.
- **Tailwind CSS** for simplifying responsive design.
- Everyone who contributed to the development of this app.

## 📬 Contact

For questions, feedback, or contributions, feel free to open an issue or contact the project owner at [Mohammed-Saqhib](https://github.com/Mohammed-Saqhib).

---

⭐ **If you found this project useful, please consider starring the repository!** ⭐
