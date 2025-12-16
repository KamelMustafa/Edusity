# Edusity – Educational Landing Page

Edusity is a modern, responsive educational landing page built with React.
The project presents an academic platform layout including programs, campus
gallery, testimonials, and contact sections using a clean component-based
architecture.

---

## Features

- Built with React (Functional Components & Hooks)
- Component-based structure for easy maintenance
- Video modal player controlled via React state
- Responsive navigation bar
- Programs showcase section
- Campus gallery
- Student testimonials
- Contact form section
- Fully responsive design

---

## Application Structure

The application is a single-page layout composed of reusable components:

Navbar  
Hero  
Programs  
About (with video trigger)  
Campus  
Testimonials  
Contact  
Footer  
VideoPlayer (modal)

The video modal state is managed globally in App.jsx using React useState.

---

## Main App Logic

The video player visibility is controlled using React state:

playState → controls opening and closing the video modal  
setPlayState → passed to About and VideoPlayer components

This keeps the state management clean and centralized.

---

## Built With

- React
- JavaScript (ES6+)
- HTML5
- CSS3
- Vite

---

## Project Structure

```
src
├── components
│   ├── Navbar
│   ├── Hero
│   ├── Programs
│   ├── Title
│   ├── About
│   ├── Campus
│   ├── Testimonials
│   ├── Contact
│   ├── Footer
│   └── VideoPlayer
│
├── App.jsx
├── main.jsx
└── index.css
```

---

## Getting Started

Prerequisites:

- Node.js (v14 or higher)
- npm or yarn

Installation:

```
git clone https://github.com/KamelMustafa/Edusity.git
cd Edusity
npm install
```

Run the project:

```
npm run dev
```

The application will run at:

```
http://localhost:5173
```

---

## Build for Production

```
npm run build
```

Preview production build:

```
npm run preview
```

---

## Use Case

This project is suitable for:

- Educational platforms
- University or academy websites
- Frontend portfolio projects
- Practicing React component-based architecture

---

## Author

Kamel Mustafa  
Frontend Developer  
GitHub: https://github.com/KamelMustafa

---

## License

This project is open-source and intended for learning and portfolio use.
