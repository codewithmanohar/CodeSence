# CodeSence 🚀

CodeSence is an **AI-driven code review tool** that analyzes user-submitted source code and provides **refined, optimized, and corrected suggestions**. It helps developers improve code quality, readability, and performance using generative AI.

---

## ✨ Features

* 🧠 AI-powered code analysis and review
* 🛠 Suggests optimized and corrected code
* 🧹 Improves readability, structure, and best practices
* 🎨 Syntax-highlighted code editor
* 📄 Markdown-rendered AI responses
* 🔔 User-friendly notifications and error handling

---

## 📸 Screenshots

### 🏠 Home Page

![Home Page](https://raw.githubusercontent.com/codewithmanohar/CodeSence/main/Frontend/public/home.webp)

### ⏳ Loading State

![Loading](https://raw.githubusercontent.com/codewithmanohar/CodeSence/main/Frontend/public/loading.webp)

### 🤖 AI Code Review Result

![Result](https://raw.githubusercontent.com/codewithmanohar/CodeSence/main/Frontend/public/result.webp)

---


## 🧑‍💻 Tech Stack

### Frontend

* **React 19**
* **Vite**
* **Tailwind CSS + DaisyUI**
* **Zustand** (state management)
* **PrismJS / rehype-highlight** (syntax highlighting)
* **react-simple-code-editor**
* **react-markdown**
* **Axios**

### AI Integration

* **@google/generative-ai** (Gemini API for code analysis)

### Backend

* **Node.js**
* **Express.js**
* **MongoDB + Mongoose**
* **JWT** (Authentication)
* **bcrypt** (Password hashing)
* **dotenv** (Environment variables)
* **CORS**

---

## 📂 Project Structure

```
CodeSence/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── store/
│   │   ├── services/
│   │   ├── pages/
│   │   └── main.jsx
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   ├── package.json
│   └── .env
└── README.md
```

## ⚙️ Installation & Setup
````


### Prerequisites
- Node.js (v18 or later recommended)
- npm or yarn
- MongoDB (local or cloud – Atlas)

### Clone Repository

```bash
git clone https://github.com/codewithmanohar/CodeSence.git
cd CodeSence
````

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` folder:

```env
PORT=8000
GEMINI_KEY=your_google_gemini_api_key
MONGODB_URI=your_mongodb_connection_string
NODE_ENV=development
```

Start backend server:

```bash
npm run dev
```

### Frontend Setup

````bash
cd ../frontend
npm install
npm run dev
```bash
# Clone the repository
git clone https://github.com/codewithmanohar/CodeSence.git

# Navigate to frontend
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
````

---

## 🔐 Environment Variables

### Backend (.env)

```env
PORT=8000
GEMINI_KEY=your_google_gemini_api_key
MONGODB_URI=your_mongodb_connection_string
NODE_ENV=development
```

### Frontend (.env)

```env
VITE_API_BASE_URL=http://localhost:8000
```

> ⚠️ Keep environment variables secure. Do not expose secrets in client-side code.

---

## 🧠 How It Works

1. User writes or pastes code in the frontend editor
2. Frontend sends code to the backend API
3. Backend securely communicates with the Gemini AI API
4. AI analyzes the code for:

   * Bugs and errors
   * Optimization opportunities
   * Best practices and readability
5. Backend returns refined suggestions
6. Frontend displays results with syntax highlighting


## 🚀 Future Enhancements

* Diff view (original vs optimized code)

* Support for multiple programming languages

* User authentication & review history

* Role-based access (admin / user)

* Export reviewed code as file

* Rate limiting & API usage tracking

* Docker support

* Diff view (original vs optimized code)

* Support for multiple programming languages

* Authentication & user history

* Export reviewed code

* Backend-based secure AI requests

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request



## 👨‍🎓 Author

**Manohar Kumar**
B.Tech CSE | Full Stack Dev | AI Enthusiast

---

If you like this project, don’t forget to ⭐ the repository!
