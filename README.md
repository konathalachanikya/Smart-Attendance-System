# 🚀 Smart Attendance System (TrackAS)

A modern attendance platform built with **React + Vite**, using **QR codes** and **geolocation** to ensure accurate, location-verified check-ins. Ideal for universities, workshops, conferences, and corporate training.

## ✨ Features

- **QR-based attendance** (unique session token per class)
- **Geolocation verification** (Haversine distance; anti-proxy)
- **Lecturer dashboard** (create schedules, generate QR)
- **Attendance history & analytics**
- **Export to XLSX**
- **Secure auth & RLS with Supabase**
- Responsive UI with **Tailwind CSS + DaisyUI**

---

## 🧰 Tech Stack

- **Frontend:** React, Vite, React Router
- **Styling:** Tailwind CSS, DaisyUI
- **Backend (BaaS):** Supabase (Auth + Database)
- **Geo/Maps:** Leaflet, React-Leaflet
- **QR:** `qrcode.react`, `react-qr-code`
- **HTTP:** Axios
- **Date/Time:** Day.js
- **Export:** FileSaver, XLSX
- **Linting:** ESLint (optional)

---

## 🔐 Environment Variables

Create `.env` from `.env.example`:

```bash
VITE_SUPABASE_URL=YOUR_SUPABASE_URL
VITE_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY
VITE_LOCALHOST_URL=http://localhost:5173
VITE_VERCEL_URL=YOUR_DEPLOY_URL   # optional
