# 🚀 Laravel React Starter

> Fullstack starter kit built with **Laravel 11**, **React 18**, **Vite**, and **Tailwind CSS** — ready for building scalable and modern web applications. Includes authentication, RESTful API structure, Docker setup, and clean architecture.

---

## 🧠 Tech Stack

| Layer | Technology |
|-------|-------------|
| Backend | Laravel 11 (API Mode) |
| Frontend | React 18 + Vite |
| UI | Tailwind CSS + Shadcn/UI |
| Auth | Laravel Sanctum |
| API Docs | Laravel Scribe |
| Database | PostgreSQL / MySQL |
| DevOps | Docker + Nginx |
| Testing | PestPHP + Vitest |
| Tools | Prettier + ESLint + Husky |

---

## 📂 Project Structure

laravel_react_starter/
├── backend/ # Laravel 11 backend API
│ ├── app/
│ ├── bootstrap/
│ ├── config/
│ ├── database/
│ ├── routes/
│ ├── tests/
│ └── ...
│
├── frontend/ # React + Vite frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── hooks/
│ │ ├── routes/
│ │ └── utils/
│ ├── public/
│ ├── index.html
│ └── vite.config.js
│
├── docker/
│ ├── nginx/
│ │ └── default.conf
│ └── php/
│ └── Dockerfile
│
├── docker-compose.yml
├── README.md
└── .env.example


---

## ⚡ Features

- 🔐 **Authentication (Login/Register)** via Laravel Sanctum  
- 🧱 **RESTful API structure** with versioning (`/api/v1/...`)  
- 🌈 **React Router v6** with protected routes  
- 🎨 **Tailwind + Shadcn UI** components  
- 🧪 **Testing ready**: Pest (Laravel) + Vitest (React)  
- 🐳 **Dockerized** (Nginx + PHP-FPM + Node + DB)  
- 📄 **API documentation** auto-generated  
- 🚀 **Production-ready build scripts**

---

## 🧰 Installation

### Backend (Laravel)
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve

Frontend (React)
cd frontend
npm install
npm run dev

🐳 Docker Setup (Optional)

You can run the full stack in Docker using:

docker compose up -d


Then open:

Backend API → http://localhost:8000

Frontend App → http://localhost:5173

🔗 Example API Endpoints
Method	Endpoint	Description
POST	/api/v1/login	User login
POST	/api/v1/register	Register user
GET	/api/v1/user	Get profile
GET	/api/v1/posts	Get all posts
POST	/api/v1/posts	Create post
🧪 Testing
Laravel
php artisan test

React
npm run test

💅 Code Style

Backend → Laravel Pint

Frontend → ESLint + Prettier

Pre-commit hooks via Husky

npm run lint
npm run format

📦 Build for Production
Backend
php artisan optimize

Frontend
npm run build

🧠 Architecture Overview
Frontend (React)
   ↕️ Axios API calls
Backend (Laravel)
   ↕️ Eloquent ORM
Database (PostgreSQL/MySQL)


The project uses service-based architecture in Laravel, and component-driven design in React.
Ideal for scaling or integrating with mobile apps later (e.g., React Native / Flutter).

🧩 Future Enhancements

🔄 Role & Permission System (Spatie)

🌍 Multi-language support (i18n)

💳 Stripe / Midtrans integration

🧠 AI CRUD generator

📱 Mobile app (React Native)

👨‍💻 Author

Muhammad Irhamul Umam
Fullstack Developer • Founder @ Irhamu Dev Company

🌐 irhamu.dev

💼 LinkedIn

📧 hi@irhamu.dev

⭐ Contributing

Contributions are welcome!
Please fork, make changes on a new branch, and submit a PR 🚀
📜 License

This project is licensed under the MIT License
.

🖼️ Screenshots (Optional)
Frontend	API Docs

	

Built with ❤️ by Irhamu Dev Company
