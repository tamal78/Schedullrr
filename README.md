# Schedulrr 📅

![Schedulrr Preview](https://github.com/user-attachments/assets/0d4b2ce7-ebfb-4e31-a48e-a394c2cb3ddc)

**Schedulrr** is a full-stack meeting scheduling platform built with **Next.js**. It allows users to create and manage events, share booking links, and automatically generate Google Meet links for streamlined collaboration. Schedulrr ensures a responsive and user-friendly experience, with robust backend support for handling availability, schedules, and events.

---

## 🌟 Features

- 📅 **Create Events**  
  Effortlessly create customizable events with dynamic scheduling options.

- 🔗 **Share Booking Links**  
  Share event booking links to simplify scheduling for others.

- 📧 **Google Meet Integration**  
  Automatically generate Google Meet links for every event.

- 🕒 **Availability Updates**  
  Seamlessly update and manage your availability in real time.

- 🚀 **Responsive Design**  
  Enjoy a beautiful and intuitive interface on any device.

- 💾 **Robust Backend**  
  Manage user data, events, and schedules with PostgreSQL and Prisma.

---

## 🛠️ Tech Stack

- **Frontend**: Next.js, TailwindCSS
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL with PrismaORM
- **Third-Party API**: Google Calendar API

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [PostgreSQL](https://www.postgresql.org/) or [NeonDB](https://neon.tech/)
- A Google API Project with Calendar API enabled.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tamal78/schedulrr.git
   ```

2. Navigate to the project directory:

   ```bash
   cd schedulrr
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables:  
    Create a `.env` file in the root directory and configure the required variables, e.g.:

   ```env
   DATABASE_URL=....
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
   CLERK_SECRET_KEY=...
   ```

5. Run database migrations (if applicable):

   ```bash
   npx prisma migrate dev
   ```

6. Start the development server:

   ```bash
   npm run dev
   ```

7. Open the app in your browser:
   ```
   http://localhost:3000
   ```

---

## 📸 Screenshot

![Schedulrr Preview]()

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for suggestions and improvements.

---

### 🌐 Live Demo

Check out the live demo [here](https://schedullrr.vercel.app/)
