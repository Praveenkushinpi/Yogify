# 🧘‍♂️ Yogify — Your Social Yoga & Wellness Tracker

![Yogify Banner](https://hc-cdn.hel1.your-objectstorage.com/s/v3/1f1295fef29dfda9869ed00214f5b72ce9fb360e_banner.jpg) 

Welcome to **Yogify**, a beautiful and nature-inspired yoga and health tracking app where you can connect with friends and grow together on your wellness journey.

> **Track. Connect. Thrive.** 🌿

---

## 🚀 Live Preview
Coming soon...

## 📦 Repository  
🔗 [https://github.com/Praveenkushinpi/Yogify](https://github.com/Praveenkushinpi/Yogify)

---

## 🌿 Features

- 🧘 Track yoga sessions & daily health
- 📈 Visual progress charts
- 👫 Add friends & see their health journey
- 🔔 Goal reminders & motivational nudges
- 🌱 Nature-inspired, calming UI

---

## 🛠 Tech Stack

| Tech           | Purpose                             |
|----------------|-------------------------------------|
| **Next.js**    | Fullstack React Framework           |
| **React**      | Frontend UI Components              |
| **Supabase**   | Auth, Realtime DB, Storage           |
| **Tailwind CSS** | Utility-first responsive styling |
| **Recharts**   | Visualizing health progress         |
| **Framer Motion** | Smooth animations & transitions |

---

## 🧠 Supabase Schema (Simplified)

### `users`
- `id`, `email`, `name`, `avatar_url`, `bio`

### `yoga_sessions`
- `id`, `user_id`, `duration_minutes`, `type`, `date`, `notes`

### `health_stats`
- `id`, `user_id`, `weight`, `bmi`, `sleep_hours`, `mood`, `date`

### `friends`
- `id`, `user_id`, `friend_id`, `status` (pending/accepted)

---
📈 Future Roadmap
✅ Friend system

✅ Yoga session tracking

🔲 Group yoga sessions

🔲 Mood journal

🔲 In-app nature sounds (ambient audio)

🔲 Mobile app (Expo)

🤝 Contributing
PRs are welcome! If you find bugs or have ideas, feel free to open an issue.

📜 License
MIT License © Praveenkushinpi

