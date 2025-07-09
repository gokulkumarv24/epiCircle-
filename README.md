# ♻️ epiCircle

A dual-role eco-recycling platform that connects **Customers** who want to schedule scrap pickups with **Partners** who manage and process those pickups. Built with React Native, this system is ideal for mobile users to promote clean, eco-friendly waste management.

---

## 📱 Apps Overview

### 👤 Customer App
- **Login via OTP** (mocked)
- **Schedule Pickups** with date & time slot
- **Google Maps** integration for accurate pickup location
- **Order History** with status tracking
- **PDF export** of past orders
- **Reminders** via notifications before scheduled pickups

### 👷 Partner App
- **Login via OTP** (mocked)
- **Assigned Pickups** list (filtered by status)
- **Pickup Workflow** with multiple steps:
  - Accept Pickup
  - Validate Pickup Code
  - Add Item Details (qty & price)
  - Submit for Approval
  - Status auto-tracks from Pending → Completed

---

## 🗂 Project Structure

epiCircle-/
├── CustomerApp/ # React Native app for customers
├── PartnerApp/ # React Native app for partners
├── db.json # JSON server mock backend (shared)
├── README.md
└── .gitignore

yaml
Copy
Edit

---

## 🚀 Tech Stack

| Layer         | Technology                 |
|---------------|-----------------------------|
| Frontend      | React Native (Expo)        |
| UI Components | React Native Paper         |
| Backend (Mock)| JSON Server                |
| Storage       | AsyncStorage               |
| Location      | Expo Location              |
| Notifications| Expo Notifications         |

---

## 📦 Features

### ✅ Common
- Smooth onboarding via OTP (mocked for dev)
- Stylish material UI
- Realtime status updates

### 👤 Customer
- Location fetch with 📍Google Map preview
- Schedule with reminder notifications
- History with PDF export (optional)

### 👷 Partner
- Step-wise workflow management
- Total value calculation 💰
- Automatic session logout for inactivity
###👨‍💻 Developer
- Gokul Kumar V
- 📧 gokulkumarv2024@gmail.com
- 🔗 Portfolio 1:https://jazzy-muffin-89a87d.netlify.app/
- 🔗 Portfolio 2:https://gk-portfolio-5q3f.vercel.app/
- 🐱 GitHub:https://github.com/gokulkumarv24
- 💼 LinkedIn:https://www.linkedin.com/in/gokul-kumar-v-236a24217


---

## 🧪 How to Run Locally

### 1. Clone Repo

```bash
git clone https://github.com/gokulkumarv24/epiCircle-.git
cd epiCircle-
2. Start Backend (JSON Server)
bash
Copy
Edit
npm install -g json-server
json-server --watch db.json --port 3001
3. Run Customer App
bash
Copy
Edit
cd CustomerApp
npx expo start
4. Run Partner App
bash
Copy
Edit
cd PartnerApp
npx expo start
📷 Screenshots
Customer App	Partner App


📌 Future Improvements
✅ Firebase OTP Authentication

🔄 Reassign pickup if partner is unavailable

📦 Admin Dashboard (Web-based)

🧾 Download PDF invoice for every order

📃 License
MIT © Gokul Kumar V

yaml
Copy
Edit

---

### ✅ Next Steps

1. Save this as `README.md` inside your project root (`epiCircle-/README.md`)
2. Commit and push it:

```bash
git add README.md
git commit -m "Added README documentation"
git push origin main# epiCircle-
React Native Assignment
