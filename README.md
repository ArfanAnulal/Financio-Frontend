# Financio Frontend

Financio is a modern personal finance management web application. This is the frontend built using [Vite](https://vitejs.dev/) and [React](https://react.dev/), designed to interface with a RESTful backend API.

## 🚀 Features

- Responsive, user-friendly UI for managing personal finances
- Authentication and secure API interaction
- Real-time updates and clean data visualizations
- Environment-based configuration

## 📦 Tech Stack

- **React** (with Vite)
- **Axios** for HTTP requests
- **React Router** for client-side routing

## 🔧 Setup & Development

### 1. Clone the repository

```bash
git clone https://github.com/your-username/financio-frontend.git
cd financio-frontend
```

### 2. Clone the repository
```bash
npm install
```

### 3. Configure environment variables
Create a .env file 
in the root of the project and add:
```bash
VITE_BACKEND_URL=http://localhost:5000
```

- During development, use your local backend URL.

- In production, set VITE_BACKEND_URL to your deployed backend's URL.

### 4. Run the development server
```bash
npm run dev
```

### 5. 🛠 Build for Production
```bash
npm run build
```
This will create an optimized production build in the dist/ folder.

###6. 🌐 Deployment
You can deploy the production build to any static site hosting service (like Vercel, Netlify, or your custom server). Just ensure the VITE_BACKEND_URL 
is set to the correct backend endpoint in your deployed environment.
