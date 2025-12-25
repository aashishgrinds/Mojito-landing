# Mojito Hero Animation 🍃🍸

A GSAP-powered animated hero section built with **React**, featuring **SplitText text animations** and **scroll-based parallax effects** using **ScrollTrigger**.

##  Features

- Character & line-based text animations using **GSAP SplitText**
- Smooth entrance animations with `expo.out` easing
- Scroll-based parallax animation for decorative elements (leaves)
- Font-safe animations (runs after fonts are loaded)
- Responsive-friendly setup (works with `vh / dvh`)
- Clean React component structure

## 🛠 Tech Stack

- **React**
- **GSAP**
  - SplitText
  - ScrollTrigger
- **@gsap/react**
- **Tailwind CSS**


## How It Works:

- Text is split into **characters, words, and lines** using `SplitText`
- Animations run **after fonts are fully loaded** to avoid layout shifts
- Hero text animates on load
- Decorative leaf images animate on scroll using `ScrollTrigger`
- Scroll animation is synced smoothly using `scrub: true`

## Getting Started

```bash
npm install
npm run dev


