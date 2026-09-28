# ICAICSE 2026 — Conference Website

International Conference on Artificial Intelligence for Computational Science and Engineering (20–21 October 2026).
Organized by **National Institute of Technology Srinagar (NIT Srinagar)** · Sponsored by **J&K Bank**.

---

## Deploying to Voroa (voroa.com / getvoroa.com)

This repository is pre-configured for one-click deployment on **Voroa**:

### Option 1: Deploy as a Static Site (Fastest & Free)
1. Sign in to [Voroa Dashboard](https://getvoroa.com).
2. Click **Create New Service** → Select **Static Site**.
3. Connect your GitHub repository: `animeshx45/ConfrenceProject`.
4. Leave **Build Command** empty (or `npm run build`).
5. Set **Publish Directory** to `./` (root directory).
6. Click **Deploy**. Your site goes live instantly with SSL HTTPS.

---

### Option 2: Deploy as a Web Service (Node.js)
1. Sign in to [Voroa Dashboard](https://getvoroa.com).
2. Click **Create New Service** → Select **Web Service**.
3. Select the repository: `animeshx45/ConfrenceProject` (`main` branch).
4. Voroa will auto-detect Node.js:
   - **Build Command**: `npm run build`
   - **Start Command**: `npm start`
   - **Port**: Auto-detected from `PORT` environment variable (defaults to 3000)
5. Click **Deploy**.

---

## Local Development
To preview the website locally:

```bash
# Using Node.js server:
npm start

# Or directly open in any browser:
# double-click index.html
```
