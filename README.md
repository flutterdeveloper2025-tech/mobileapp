# IT Service Desk — MERN

Complete foundation using:
- React + Vite frontend
- Node.js + Express backend
- MongoDB + Mongoose
- JWT authentication
- Responsive mobile-first UI
- PWA-ready structure
- Capacitor-ready path for Android APK packaging

## Run backend
cd server
npm install
copy .env.example .env
npm run dev

## Run frontend
cd client
npm install
npm run dev

Set `VITE_API_URL` in client/.env if the API is not localhost.

## Android APK
After the React app is configured and tested:
npm run build
npx cap add android
npx cap sync
npx cap open android

Build the signed APK from Android Studio.
