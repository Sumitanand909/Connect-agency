# Connect-agency

## Live Link: 
- http://connect-agency.netlify.app

This project provides a direct way for people to reach out and connect, making it easy for anyone interested to send a message or email to start a conversation. The integrated contact form allows individuals to quickly get in touch for collaboration, questions, or networking opportunities. For anyone wanting to connect or discuss potential work, simply fill out the contact form and the response will go directly to the creator via email, ensuring seamless and efficient communication.

## Features

-  Responsive design Provides a seamless user experience across all device sizes, from mobile to desktop.
-  Modern tech stack Built with React, Tailwind CSS, and Vite for fast development and clean styling.
-  Light and dark mode toggle Instantly switch themes for personalized viewing comfort.
-  Dynamic service section Interactive service cards highlight agency offerings with engaging visual effects.
-  Team showcase Presents expert team members with images and bios to build trust with visitors.
-  Trusted by brands Displays client logos to build credibility and trustworthiness.
-  Contact form integration Web3Forms-powered contact form lets visitors reach out quickly and easily.
-  Newsletter subscription Visitors can subscribe for agency updates, news, or marketing tips.
-  Sticky navigation bar Makes site navigation consistent and intuitive for users.
-  SEO-friendly layout Ensures optimized visibility and performance for search engines.
-  Modular code structure Keeps code maintainable and scalable for future development.

## Tech Stack

```
      Technology            Usage
  ---------------------------------------------------
      React	                Frontend framework
      Tailwind CSS	        Utility-first styling
      Vite	                Development environment
      Web3Forms	            Contact form handling
      React-Hot-Toast       Notifications and feedback
```

## Getting Started

Prerequisites
-  Node.js (version 18+ recommended)
-  npm or yarn

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Sumitanand909/connect-agency.git
```

2. Change directory:
```bash
cd connect-agency
```

3. Install dependencies:
```bash
npm install
```
or
```bash
yarn install
```

## Running the Application
```bash
npm run dev
```
or
```bash
yarn dev
```

## File Structure
```
src/
│
├── components/
│   ├── Navbar/
│   │   └── Navbar.jsx
│   ├── Hero/
│   │   └── Hero.jsx
│   ├── TrustedBy/
│   │   └── TrustedBy.jsx
|   ├── OurWork/
│   │   └── OurWork.jsx
│   ├── Services/
│   │   ├── Services.jsx
│   │   └── ServiceCard.jsx
│   ├── Teams/
│   │   └── Teams.jsx
│   ├── ContactUs/
│   │   └── ContactUs.jsx
│   ├── Footer/
│   │   └── Footer.jsx
│   ├── ThemeToggleBtn/
│   │   └── ThemeToggleBtn.jsx
│   └── Title/
│       └── Title.jsx
│
├── assets/
│   └── ... (images, logos, icons, data files)
│
├── styles/
│   └── index.css
│
├── App.jsx
├── main.jsx
│
└── index.js (optional, for entry point)
```

## Customization

- Replace logo and images in /src/assets for branding.
- Update servicesData and teamData in respective component folders to reflect your agency.
- Web3Forms integration key can be replaced in ContactUs.jsx

## Author
- Sumit Anand
- Full stack Developer
