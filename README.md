# ⚡ EV Station Finder - Frontend

An interactive, high-performance web application designed for Electric Vehicle (EV) owners to discover, filter, and book charging slots in real-time. This project demonstrates a focus on modern React patterns, scalable architecture, and a premium User Experience (UX).

---

## ✨ Key Features

* **Interactive Station Map:** Real-time visualization of charging hubs with custom markers and status indicators.
* **Smart Filtering System:** Advanced search capabilities to filter stations by connector type, power output, and real-time availability.
* **Seamless Booking Flow:** An intuitive multi-step booking interface with conflict handling for time slots.
* **Dynamic User Dashboard:** Profile management, charging history tracking, and favorite station bookmarks.
* **Fully Responsive:** Mobile-first design approach ensuring a smooth experience across all screen sizes.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React.js (Functional Components & Hooks) |
| **State Management** | Redux Toolkit / Context API |
| **Styling** | Tailwind CSS (Utility-first CSS) |
| **Routing** | React Router v6 |
| **Data Fetching** | Axios with centralized API configuration |
| **Icons & UI** | Lucide React / HeroIcons |

---

## 🏗️ Technical Highlights

* **Component-Driven Development:** Built using a modular folder structure for high maintainability and reusability.
* **Performance Optimization:** Utilized React.memo, useCallback, and lazy loading to ensure lightning-fast page transitions.
* **Clean API Integration:** Implemented custom hooks and interceptors to manage global loading states and error handling gracefully.
* **Accessible UI:** Followed WAI-ARIA guidelines to ensure the application is usable for everyone.

---

## 🚦 Installation & Setup

To get a local copy up and running, follow these steps:

1. **Clone the repository:**
   git clone https://github.com/sridhar-2210/EV_Station_Frontend.git
   cd EV_Station_Frontend

2. **Install dependencies:**
   npm install

3. **Configure Environment Variables:**
   Create a .env file in the root directory:
   REACT_APP_API_URL=your_backend_api_url

4. **Start the application:**
   npm start

---

## 💡 Challenges & Solutions

**The Challenge:** Managing high-frequency updates for station availability without causing UI lag.
**The Solution:** Implemented a sophisticated state management strategy using Redux Toolkit to batch updates and background synchronization logic, ensuring the user always sees live data without performance trade-offs.

---

## 👤 Author

**Sridhar**
* **GitHub:** [@sridhar-2210](https://github.com/sridhar-2210)
* **LinkedIn:** [/vangara-sridhar](https://www.linkedin.com/in/vangara-sridhar/)

---
*This project was developed to showcase frontend engineering capabilities in the Green-Tech sector.*
