# ✅ TickTick-Inspired To-Do App

A simple, full-stack task management app built with **Next.js**, **Nest.js**, **PostgreSQL**, and **Tailwind CSS**, supporting recurring tasks.

---
DATABASE_URL="prisma+postgres://accelerate.prisma-data.net/?api_key=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhcGlfa2V5IjoiNmMxMDUxYWItMmRhMS00OTk1LWI2NzEtYzdiNjU5MjdjYWM1IiwidGVuYW50X2lkIjoiN2FjMTlkN2ZkMTU0ZGMwYzY4NjdkNWEyZGY4Y2RmMTlhMDZmY2IxNjYxZWUwMzg5NTUyODczYjEwOGFjYWI0ZCIsImludGVybmFsX3NlY3JldCI6IjMwNzM1NWE1LWZjNDctNGVhNS05NjdjLTAwYzBhZjY3NzIzZiJ9._afKAt46MkM63Lx_bZFGz0mJEpZVzboABUM-vqf6DHs"
## 🚀 Features

- 📝 Create, update, delete tasks
- 🔁 Recurring tasks:
  - Daily, weekly, monthly, yearly
  - Every X days/weeks/months/years
  - Specific weekdays (e.g. Mon/Wed/Fri)
  - Nth weekday of the month (e.g. 2nd Tuesday)
- 📅 Reusable date picker
- 📌 Mini-calendar with recurrence preview

---

## 🧱 Tech Stack

| Layer      | Tech          |
|------------|---------------|
| Frontend   | Next.js + Tailwind CSS |
| Backend    | Nest.js (Node.js) |
| Database   | PostgreSQL     |
| State Mgmt | Zustand (can swap with Jotai or Context API) |
| Styling    | Tailwind CSS   |
| Recurrence | `rrule` library |

---

## 📂 Project Structure

