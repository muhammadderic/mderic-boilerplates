# 🚀 Express Boilerplate

Minimal and production-ready Express.js API boilerplate with built-in routing, validation, error handling, and environment configuration.

---
## 📦 Features
- Folder structure (modular, scalable)
- Environment setup (dotenv)
- Middleware (JSON parser, CORS)
- Database setup (Mongoose)

---
## ⚙️ Configuration
| Key | Default Value | Description |
| --- | --- | --- |
| `PORT` | `5000` | Port to run the server |
| `NODE_ENV` | `development` | Environment mode |
| `MONGODB_URI` | - | Database connection string |

> You can configure all of these in the .env file.
> Make sure to rename .env.example to .env and adjust your settings.

---
## 📁 Folder Structure
```
mderic-boilerplates/
└── [express-api]/
    ├── src/
    │   ├── routes/
    │   ├── config/
    │   ├── api.js
    │   └── server.js
    ├── .env.example
    ├── package.json
    └── README.md  ← (You are here)
```

---
## 📌 Version
```json
{
  "version": "1.0.0"
}
```
You can also find this in `boilerplate.json`.

---
## 🙋‍♂️ Author / Maintainer
- **Name**: muhammadderic
- **Last Updated**: `2025-06-25`