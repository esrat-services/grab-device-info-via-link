# 📱 grab-device-info-via-link

A simple web-based project that captures basic device information such as selfie (camera capture), location (GPS), and device details when a user opens a shared link.

> ⚠️ **Disclaimer:** This project is for educational and testing purposes only. Always obtain proper consent before collecting any user data.

---

## 🚀 Features
- Capture user selfie via browser camera  
- Retrieve GPS location  
- Collect basic device informations like IP/IPV4/IPV6, Internet speed many More
- Lightweight and easy to deploy  

---

## 🛠️ Project Variants

This repository includes two versions:

1. **Supabase Version**
   - `index.html`
   - `data.html`

2. **Firebase Version**
   - `firebase.index.html`
   - `firebase.data.html`

---

## ⚙️ Setup Instructions

### 1. Configure Backend
- Open any pair of files (either Supabase or Firebase version) in your code editor.
- Add your credentials:
  - **Supabase:** Insert your Supabase URL and API key  
  - **Firebase:** Add your Firebase configuration  

---

### 2. Deploy the Website
You can host the project using any static hosting platform:
- Vercel  
- Netlify  
- GitHub Pages  
- Any other hosting service  

---

### 3. Usage
1. Share the hosted link with the target user  
2. When the user opens the link and grants permissions:
   - Data will be captured and stored  
3. Open the corresponding data page (`data.html` or `firebase.data.html`) to view the collected information  

---

## 📌 Notes
- Requires user permission for camera and location access  
- Works best on modern browsers  
- Ensure HTTPS hosting (required for camera & GPS access)  

---

## ⚠️ Ethical Use
This tool should only be used:
- For learning purposes  
- With explicit user consent  

Misuse of this project may violate privacy laws.

---

## ⭐ Contribution
Feel free to fork, improve, and contribute to the project!
