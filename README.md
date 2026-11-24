
<div align="center">

# 🍽️ L'Essence Gastronomique
### *Where Culinary Art Meets Artificial Intelligence*

[![Owner](https://img.shields.io/badge/Owner-farhan-swe-amber?style=for-the-badge&logo=github)](https://github.com/farhan-swe)
[![Repo](https://img.shields.io/badge/Repository-Restaurant--Landingpage--Lessence-black?style=for-the-badge&logo=github)](https://github.com/farhan-swe/Restaurant-Landingpage-Lessence)
[![Tech](https://img.shields.io/badge/Built%20With-React%20%26%20Tailwind-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![AI](https://img.shields.io/badge/Powered%20By-Google%20Gemini-orange?style=for-the-badge&logo=googlegemini)](https://ai.google.dev/)

---

<p align="center">
  <img src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?auto=format&fit=crop&w=1200&q=80" alt="L'Essence Banner" width="800" style="border-radius: 20px; border: 1px solid #333;" />
</p>

**L'Essence Gastronomique** is an ultra-premium, modern restaurant landing page designed for an immersive dining discovery experience. Featuring high-end aesthetics, liquid-smooth animations, and a state-of-the-art **AI Sommelier** powered by Google Gemini.

[Explore the Menu](#-menu) • [Make a Reservation](#-reservations) • [Meet the AI Concierge](#-ai-concierge)

</div>

---

## ✨ Key Features

| Feature | Description | Label |
| :--- | :--- | :--- |
| **Elegant UI/UX** | Dark-themed, glassmorphic design with gold accents and high-end typography. | `UI/UX` |
| **AI Concierge** | Real-time AI Sommelier trained on the restaurant's unique menu and philosophy. | `Gemini AI` |
| **Interactive Menu** | Filterable culinary categories with hover-sensitive animations and rich imagery. | `Interactivity` |
| **Reservation System** | Sophisticated booking interface with integrated validation and feedback. | `Functionality` |
| **Fully Responsive** | Optimized for mobile, tablet, and desktop viewports with adaptive layouts. | `Responsive` |
| **Animated Assets** | Entrance animations, parallax scrolling effects, and pinging AI indicators. | `Animation` |

---

## 🛠️ Technology Stack

<div align="center">

| Core | Styles | Icons | AI Engine |
| :---: | :---: | :---: | :---: |
| **React 19** | **Tailwind CSS** | **Lucide React** | **Google Gemini 3** |
| ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white&style=flat-square) | ![Tailwind](https://img.shields.io/badge/-TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white&style=flat-square) | ![Lucide](https://img.shields.io/badge/-Lucide-FF69B4?logo=lucide&logoColor=white&style=flat-square) | ![Gemini](https://img.shields.io/badge/-Gemini-4285F4?logo=google&logoColor=white&style=flat-square) |

</div>

---

## 📂 Project Structure

```text
.
├── components/
│   ├── AIConcierge.tsx   # Gemini-powered floating chat interface
│   ├── Header.tsx        # Sticky navigation with mobile menu
│   ├── Hero.tsx          # Dynamic landing section
│   ├── Menu.tsx          # Filterable dish selection
│   └── Reservation.tsx   # Booking form component
├── services/
│   └── geminiService.ts  # Logic for AI Sommelier communication
├── constants.ts          # Centralized menu data and testimonials
├── types.ts              # TypeScript interfaces
├── App.tsx               # Main layout assembly
├── index.tsx             # Entry point
└── index.html            # HTML Shell with Tailwind & Fonts
```

---

## 🤖 AI Concierge Implementation

The **AI Sommelier** is a specialized integration of the `@google/genai` SDK. It uses `gemini-3-flash-preview` to provide:
- **Wine Pairing Recommendations**: Sophisticated suggestions based on the specific menu items.
- **Dietary Guidance**: Knowledge of "Truffle Scallops" (Gluten-Free) and "Wagyu A5 Striploin" (Premium).
- **Tone Control**: A refined, elegant persona that matches the brand identity of *L'Essence*.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/farhan-swe/Restaurant-Landingpage-Lessence.git
   ```

2. **Set up Environment Variables:**
   Ensure `process.env.API_KEY` is configured with your Google Gemini API Key.

3. **Install Dependencies:**
   ```bash
   npm install
   ```

4. **Launch Application:**
   ```bash
   npm start
   ```

---

## 👤 Owner Details

<div align="center">

**Project Lead:** `farhan-swe`

[![Follow on GitHub](https://img.shields.io/github/followers/farhan-swe?label=Follow%20%40farhan-swe&style=social)](https://github.com/farhan-swe)

</div>

---

<div align="center">

*Designed with passion for the culinary arts.*  
[Back to Top](#-lessence-gastronomique)

</div>
