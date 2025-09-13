This repository contains the source code for my personal portfolio website, a fully responsive, single page application designed to showcase my projects, skills, and publications in the fields of Data  Science, AI/ML, and Software Development. The site is built with a "Modern & Techie" aesthetic, featuring a unique horizontal scroll, extensive animations, and interactive easter eggs. 

Features:   The portfolio is designed to be an engaging and interactive experience for visitors, especially recruiters and fellow developers.

UI/UX & Animations: 

• Horizontal Scrolling: The entire website navigates horizontally, with each section occupying a full viewport width, creating a unique gallery-like experience. 

• Glassmorphism UI: A "liquid glass" effect is used on cards and navigation elements, creating a sense of depth with blurred, semi-transparent backgrounds. 

• Fluid Hover Effects: Navigation links, project cards, and skill headers feature a smooth "liquid light" animation on hover, enhancing interactivity. 

• Hero Animation: The name "Prithvi Syam D S." is revealed with a custom "decode" effect, followed by a 2-second pause before the final period gracefully transforms into a vibrant underline. 

Interactive Sections: 

• 3D Flip Cards for Projects: The project showcase initially displays only the project titles. On click, each card performs a 3D flip to reveal a detailed description, the tech stack used, and links to publications. Only one card can be flipped at a time to maintain focus. 

• Accordion Skills Menu: The "Technical Toolkit" section is organized into an interactive accordion. Clicking a category header smoothly expands a dropdown list of relevant skills, each presented in a clean, modern tile. 


Hidden Easter Eggs: 

• To add a personal touch and showcase creativity, the site includes several hidden features: 

• The Terminal: Clicking on the name in the header 5 times reveals a full-screen, glass-style  command-line terminal. Users can type commands like help, projects, skills and exit. 

• The Hidden Sea Chart: Typing nautical into the terminal triggers a wave animation that reveals a hidden sea chart displaying the gaming name "The Nautical One." 
• The Deep Sea Discovery: Clicking the "Designed & Built by Prithvi Syam" text in the footer triggers a full-screen overlay where an ASCII art of a majestic galleon is drawn line-by-line, followed by the signature: > Captain on deck: The Nautical One. 

• Developer Console Message: A custom, styled message is logged in the browser's developer console for curious visitors.

Technology Stack: 

• This project was built from the ground up with a focus on simplicity, performance, and 
modern aesthetics, using only front-end technologies. 

• Core: HTML5, CSS3, JavaScript (ES6) 

• Styling: Tailwind CSS for a utility-first workflow. All custom styles, including animations and 
glassmorphism effects, are contained within a single <style> block. 

• Fonts: Google Fonts are used for typography: 

    o Inter for the main body and UI text. 
    o Fira Code for the terminal and ASCII art easter eggs. 
    o Cinzel for the "Nautical" themed easter egg. 

• Deployment: on GitHub Pages. 


Code Structure: 

• For maximum portability and ease of deployment, the entire project is contained within a 
single index.html file. 

• <head> Section: 

      o Contains all meta tags and links to external assets (Tailwind CSS and Google Fonts). 
      o A single <style> tag holds all custom CSS, including @keyframes for all animations (name reveal, liquid effects, etc.) and utility styles for the glass UI and interactive elements. 

• <body> Section: 

    o <header>: The fixed navigation bar at the top of the page.<main class="flex">: This is the core container that enables the horizontal layout. All page sections are direct children of this element. 
    o <section class="page-section">: Each distinct part of the portfolio (Hero, About, Projects, Skills, Contact) is wrapped in a section tag that is styled to be 100vw wide and 100vh high. 
    o Modals & Overlays: The HTML for all pop-ups (Contact Modal, Terminal, Sea Chart, Deep Sea Discovery) is located at the end of the <body> and is hidden by default with CSS. 
    
• <script> Section: 

    o A single script tag at the very end of the <body> contains all the JavaScript logic. 
    o Event Listeners: The script is wrapped in a DOMContentLoaded event listener to ensure all HTML elements are loaded before it runs. 
    o Functionality: It handles all interactive features, including the horizontal scroll navigation, mobile menu toggle, project card flipping, skills accordion, and the logic for triggering and displaying all easter eggs.








