# Blog Platform Frontend

Frontend application for a modern blogging platform built with React and Vite.

---

## Features

- Responsive Design
- Authentication Pages
- Create/Edit Blog Posts
- Draft Management
- Category Filtering
- Tag Filtering
- REST API Integration
- Modern User Experience

---

## Tech Stack

| Technology | Version |
|------------|----------|
| React | Latest |
| Vite | Latest |
| React Router | Latest |
| Axios | Latest |
| CSS/Tailwind | Optional |

---

## Project Structure

```text
src

├── components
├── pages
│   ├── Login
│   ├── Home
│   ├── PostDetails
│   ├── CreatePost
│   └── EditPost
│
├── services
│
├── hooks
│
├── routes
│
├── layouts
│
└── assets
```

---

## Screens

### Public

- Home Page
- Blog Details
- Categories
- Tags

### Protected

- Dashboard
- Create Post
- Edit Post
- Draft Posts

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/blog-frontend.git
cd blog-frontend
```

### Install Packages

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

Application runs at:

```text
http://localhost:5173
```

---

## Environment Variables

Create:

```env
.env
```

```env
VITE_API_URL=http://localhost:8080/api/v1
```

---

## API Communication

Example:

```javascript
import axios from "axios";

const api = axios.create({
  baseURL: import.meta.env.VITE_API_URL
});
```

---

## Authentication

JWT token is stored in browser storage and attached to every protected request.

Example:

```http
Authorization: Bearer <token>
```

---

## Build Production

```bash
npm run build
```

Output:

```text
dist/
```

---

## Deployment

Frontend can be deployed on:

- Nginx
- Vercel
- Netlify
- Docker

---

## Future Improvements

- Dark Mode
- Rich Text Editor
- Markdown Support
- Search Functionality
- User Profiles
- Infinite Scroll

---

## Author

Radman Hayati
