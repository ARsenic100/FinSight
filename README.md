# 💸 Finsight -- Smart Expense Tracker (React Native + Express)

Finsight is a full-stack personal finance tracker built using **React
Native (Expo)** and **Express.js**, designed to help users manage
income, track expenses, and maintain overall financial clarity.

## 📸 App Preview

`/mobile/assets/images/screenshot-for-readme.png`

## 🚀 Features

-   🔐 Email authentication with Clerk (6-digit code)
-   💵 Add income & expenses
-   📊 Real-time balance updates
-   📜 Transaction history
-   🔄 Pull-to-refresh
-   🗑 Delete transactions
-   ⚙️ Express backend API
-   🗄️ PostgreSQL (Neon)
-   ⚡ Redis rate limiting

## 🧩 Tech Stack

-   **Mobile:** React Native (Expo), React Navigation, Context API\
-   **Backend:** Node.js, Express.js, PostgreSQL, Prisma, Clerk, Redis

## 📂 Project Structure

    Finsight/
    │
    ├── backend/
    │   ├── src/
    │   ├── package.json
    │   └── .env
    │
    └── mobile/
        ├── app/
        ├── components/
        ├── assets/
        ├── package.json
        └── .env

## ⚙️ Environment Variables

### `/backend/.env`

    PORT=5001
    NODE_ENV=development
    CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
    CLERK_SECRET_KEY=<your_clerk_secret_key>
    DATABASE_URL=<your_neon_postgres_url>
    REDIS_URL=<your_redis_url>

### `/mobile/.env`

    EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>

## ▶️ Run the Project

### Backend

    cd backend
    npm install
    npm run dev

### Mobile App

    cd mobile
    npm install
    npx expo start

## 🔮 Future Enhancements

-   Budget planner
-   Analytics dashboard
-   CSV/PDF export
-   Multi-currency
-   Dark mode
