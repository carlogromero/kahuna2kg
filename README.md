# Full Stack Application

A full-stack application with React frontend and Python FastAPI backend.

## Project Structure

```
├── ui/                # React application
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── api/               # Python FastAPI application
│   ├── src/
│   │   ├── routes/
│   │   └── main.py
│   ├── tests/
│   └── requirements.txt
├── .env.example       # Environment variables template
└── README.md
```

## Getting Started

### Setup Environment

1. Copy the environment template:
   ```bash
   cp .env.example .env
   ```

2. Edit `.env` with your actual values

### API Setup

1. Navigate to the api directory:
   ```bash
   cd api
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the server (from project root):
   ```bash
   python api/src/main.py
   ```

5. Run tests:
   ```bash
   pytest
   ```

The API will be available at `http://localhost:8000`

### UI Setup

1. Navigate to the ui directory:
   ```bash
   cd ui
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

The React app will be available at `http://localhost:3000`