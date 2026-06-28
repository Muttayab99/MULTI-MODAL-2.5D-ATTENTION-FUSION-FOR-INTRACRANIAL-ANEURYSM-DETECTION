# AERUX - AI-Powered Multimodal Intracranial Aneurysm Detection Platform

[![Next.js](https://img.shields.io/badge/Next.js-16.0-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-blue?style=for-the-badge&logo=react)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-007ACC?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)

**MULTI-MODAL 2.5D ATTENTION FUSION FOR INTRACRANIAL ANEURYSM DETECTION ACROSS CTA, MRA, AND MRI**

AERUX is an advanced web-based platform designed to assist medical professionals in detecting intracranial aneurysms using cutting-edge deep learning techniques. By leveraging a multi-modal 2.5D attention fusion architecture, the system analyzes multiple types of medical imaging (CTA, MRA, and MRI) to provide highly accurate and contextualized risk assessments.

## ✨ Features

- 🧠 **Multi-Modal AI Analysis:** Integrates data from CTA, MRA, and MRI scans to deliver robust aneurysm detection.
- 📊 **Interactive Dashboard:** Real-time data visualization, risk gauges, and detailed slice-by-slice reporting.
- 💬 **AI Medical Assistant:** Built-in OpenAI-powered chat widget to discuss patient results and clarify medical jargon.
- 🎨 **Modern & Fluid UI:** Fully responsive design with beautiful micro-animations using Framer Motion and Tailwind CSS.
- 🌗 **Dark/Light Mode:** First-class support for dynamic themes via `next-themes`.

## 🛠 Tech Stack

### Frontend Architecture
- **Framework:** Next.js 16 (App Router)
- **UI Library:** React 19
- **Styling:** Tailwind CSS v4, `clsx`, `tailwind-merge`
- **Animations:** Framer Motion, `tailwindcss-animate`
- **State Management:** Zustand, React Query (@tanstack/react-query)
- **Icons:** Lucide React
- **Forms:** React Hook Form + Zod validation

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites
Make sure you have Node.js (v20+) and npm installed on your machine.

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Muttayab99/MULTI-MODAL-2.5D-ATTENTION-FUSION-FOR-INTRACRANIAL-ANEURYSM-DETECTION.git
   cd MULTI-MODAL-2.5D-ATTENTION-FUSION-FOR-INTRACRANIAL-ANEURYSM-DETECTION
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. Set up environment variables
   Create a `.env.local` file in the root directory and add your API keys (e.g., OpenAI API key for the chat widget).
   ```env
   OPENAI_API_KEY=your_api_key_here
   ```

4. Run the development server
   ```bash
   npm run dev
   ```

5. Open your browser
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application in action.

## 📁 Project Structure

```text
├── app/                  # Next.js App Router (pages, api routes, layouts)
├── components/           # Reusable UI components (navigation, ui, motion, chat)
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions and API clients (e.g., OpenAI)
├── public/               # Static assets (images, icons)
├── store/                # Zustand state management stores
└── package.json          # Project dependencies and scripts
```

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
