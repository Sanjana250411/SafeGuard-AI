# 🚀 Run Locally

Follow these steps to run **SafeGuard AI** on your local machine.

## 📋 Prerequisites

Make sure you have the following installed:

- Node.js (v18 or later)
- npm
- Git
- MongoDB (if using a local database)
- Python 3.10+ (required for AI modules)

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/SafeGuard-AI.git
cd SafeGuard-AI
```

---

## 2️⃣ Install Dependencies

Install the required packages.

```bash
npm install
```

If your project has separate frontend and backend folders:

```bash
cd client
npm install

cd ../server
npm install
```

---

## 3️⃣ Configure Environment Variables

Create a **`.env`** (or **`.env.local`**) file and add the required environment variables.

```env
GEMINI_API_KEY=your_gemini_api_key
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

---

## 4️⃣ Start the Application

Run the development server:

```bash
npm run dev
```

If your frontend and backend run separately:

```bash
# Backend
cd server
npm run dev

# Frontend
cd client
npm run dev
```

If your project includes Python AI services:

```bash
cd ai
python app.py
```

---

## 🌐 Local Development

Once the application starts, open your browser and visit:

```
Frontend : http://localhost:5173
Backend  : http://localhost:5000
AI Server: http://localhost:8000
```

The application will automatically reload whenever you make changes during development.
