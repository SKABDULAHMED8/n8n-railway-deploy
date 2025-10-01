# 🚀 Free n8n Deployment on Railway

This repo lets you deploy your own **free n8n automation server** on Railway with one click.

---

## 🔹 How to Deploy

Click below to deploy on Railway:

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?repository=https://github.com/SKABDULAHMED8/n8n-railway-deploy&ref=main)


---

## 🔑 Environment Variables Required

When deploying, Railway will ask you for these:

- **N8N_BASIC_AUTH_USER** → Your login username (choose your own, e.g. `abdul`)
- **N8N_BASIC_AUTH_PASSWORD** → Your login password (choose your own, e.g. `mysecret123`)
- **DB_POSTGRESDB_HOST** → From Railway PostgreSQL service
- **DB_POSTGRESDB_DATABASE** → Usually `railway`
- **DB_POSTGRESDB_USER** → e.g. `postgres`
- **DB_POSTGRESDB_PASSWORD** → Database password from Railway

---

## 📂 Database Setup

1. In Railway, create a new **PostgreSQL Database service**.  
2. Copy the credentials (host, user, password, database).  
3. Use them when deploying this project.  

---

## 🌐 After Deployment

- You will get a URL like `https://yourapp.up.railway.app`  
- Login with your chosen username & password  
- Start building workflows 🎉

---

⚡ Enjoy your free self-hosted **n8n automation server** on Railway!
