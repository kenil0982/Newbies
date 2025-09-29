## EcoQuest Frontend (Vite + React + TS)
Perfect 👍 now I’ll give you the *entire functionality list of the EcoQuest project* (not just backend) — meaning everything your project will do as a *whole system*.

---

# 🌍 *EcoQuest – Full Project Functionalities*

## 1. 🔐 *Authentication & Authorization*

* User signup/login with JWT (students, teachers, NGOs, admins).
* Secure password hashing (bcrypt).
* Role-based access (different dashboards & permissions).
* Refresh token handling (stay logged in).

---

## 2. 👩‍🎓 *Student Functionalities*

* Personal *dashboard* with:

  * EcoPoints balance.
  * Badges earned.
  * Progress tracking.
* Access *interactive lessons* & *quizzes*.
* Attempt quizzes → earn EcoPoints & results stored.
* Take part in *eco-challenges* assigned by teachers.
* Submit proof (photo/video) for completed challenges.
* Join NGO events (clean-ups, workshops, etc.).
* View *leaderboards*:

  * Global rank (all students).
  * School-wise rank.
* Access *rewards page* (badges, certificates, eco-champion highlights).

---

## 3. 👨‍🏫 *Teacher Functionalities*

* Teacher *dashboard* with class overview.
* Assign eco-challenges to students (with deadline & points).
* Approve/reject student challenge submissions.
* Create/manage quizzes.
* Track student quiz results & progress.
* Monitor school leaderboard & student performance.

---

## 4. 🌱 *NGO Functionalities*

* NGO *dashboard* to create/manage eco-events (tree plantation, clean-up drives, workshops).
* Post event details (title, description, points, date).
* Track student/school participation.
* Approve submissions or verify participation.
* Award EcoPoints to verified participants.

---

## 5. 🛠 *Admin Functionalities*

* Admin *dashboard* with analytics & control panel.
* Manage:

  * Users (CRUD: Students, Teachers, NGOs).
  * Schools (add/edit/remove).
  * NGOs & their events.
* Oversee challenges & events.
* Manage quizzes database.
* Control leaderboards & badges assignment.
* Generate reports (monthly eco-champion, school rankings, activity stats).

---

## 6. 🏆 *Gamification System*

* *EcoPoints*: Earned from quizzes, challenges, events.
* *Badges*: Automatically assigned when milestones achieved (e.g., “Tree Planter”).
* *Leaderboards*:

  * Individual (global + school-wise).
  * School rankings (collective EcoPoints).
* *Rewards*: Certificates, digital badges, monthly eco-champions.

---

## 7. 🎉 *Events & Collaboration*

* NGOs create eco-events.
* Students & schools can join events.
* Proof of participation uploaded & verified.
* EcoPoints awarded after NGO verification.
* Schools get leaderboard points for collective event participation.

---

## 8. 📝 *Quizzes & Lessons*

* Teachers/Admin can create quizzes.
* Students attempt quizzes → auto-check answers → assign EcoPoints.
* Progress tracked (per-student & per-class).
* Difficulty levels for quizzes.
* Integration of *interactive lessons* with quizzes.

---

## 9. 🖥 *Frontend (UI/UX)*

* *Landing page*: EcoQuest overview, signup/login.
* *Dashboards*:

  * Student, Teacher, NGO, Admin (role-based).
* *Leaderboard page* with school & student rankings.
* *Rewards page* with badges & certificates.
* *Reusable components*:

  * Navbar & sidebar (role-based navigation).
  * Card components for quizzes, challenges, events.
  * Modals for proof submissions & quiz attempts.
  * Badge showcase with animations (Framer Motion).

---

## 10. 🔒 *Security*

* JWT authentication with refresh tokens.
* Password hashing.
* Input validation & sanitization.
* Role-based access control (RBAC).
* Rate limiting & CORS config.
* HTTPS deployment.

---

## 11. ⚙ *DevOps & Deployment*

* *Frontend:* Deploy to Vercel/Netlify.
* *Backend:* Deploy to Render/Railway/AWS.
* *Database:* MongoDB Atlas.
* *Dockerized setup* for frontend + backend.
* *CI/CD* with GitHub Actions.
* .env for secrets (JWT\_SECRET, MONGO\_URI).

---

## 12. 🔮 *Future Enhancements (Phase 2)*

* Mobile app (React Native).
* AI-based eco-coach (personalized eco-tips).
* Blockchain-based eco-certificates.
* Google Classroom & Microsoft Teams integration.
* Social features (share badges & eco-impact stats).

---

✅ So in short, EcoQuest = *Gamified Learning + Eco-Challenges + Quizzes + NGO Collaboration + School Leaderboards + Admin Control, all tied together with **points, badges, and rewards*.

---

Do you want me to now *convert this functionality list into a roadmap* (step-by-step milestones to build EcoQuest) so you can plan development easily?

Local development:

```sh
npm i
npm run dev
```

Build and preview:

```sh
npm run build
npm run preview
```

This repository also includes a backend in `server/` once scaffolding is complete.
