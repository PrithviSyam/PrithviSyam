This repository contains the source code for my personal portfolio website, a fully responsive, single-page application designed to showcase my projects, skills, and publications in the fields of Data Science, AI/ML, and Software Development. The site follows a modern and tech-focused aesthetic, featuring horizontal scroll navigation, extensive animations, and hidden interactive easter eggs. The portfolio is designed to provide an engaging experience for visitors, especially recruiters and fellow developers, while demonstrating advanced front-end development skills.


A. UI/UX & Animations

        1. Horizontal Scrolling: The entire site navigates horizontally, with each section spanning the full viewport width, creating a gallery-like browsing experience.

        2. Glassmorphism UI: Cards and navigation elements employ blurred, semi-transparent “liquid glass” styling to create depth.

        3. Fluid Hover Effects: Navigation links, project cards, and skill headers feature smooth “liquid light” animations on hover.

        4. Hero Animation: The name “Prithvi Syam D S.” is revealed with a custom decode effect, followed by a timed transformation into a vibrant underline.

        5. Scroll-Reveal Animations: Content fades and slides into view as the user scrolls, maintaining a smooth visual flow.

        6. Animated Section Dividers: Subtle SVG wave animations separate sections, enhancing the fluid design language.

        7. Glitch Effect on Name: The header name animates with a controlled glitch effect on hover, adding a high-tech aesthetic.

        8. 3D Parallax Tilt: Project and skill cards tilt dynamically with mouse movement, featuring a reflective glare effect.

        9. Gooey Button Morphing: Primary buttons distort with a liquid-like morphing animation on hover.

        10. Animated Social Icons: Social media links animate with unique, branded effects for a polished feel.

B. Multi-Theme System

        1. Light/Dark Modes: Users can toggle between a clean light mode and a sleek dark mode. Preferences persist across sessions.

        2. Neon Hacker Theme (Easter Egg): A hidden neon-green theme with futuristic fonts and angular UI. Activated by triple-clicking the theme toggle button.

        3. Theme-Specific Styles: Each theme alters not only colors but also fonts and UI roundness, creating distinct aesthetics.


C. Interactive Backgrounds

        1. Personalized Animated Sky Chart: A canvas-based starfield rendering the real sky chart from my birthday. Stars like Sirius, Betelgeuse, and Regulus are included, making the design uniquely personal. The sky subtly drifts and reacts to cursor movements.

        2. Interactive Particle Layer:
                    a. Cursor leaves a glowing light trail across the screen.
                    b. Particle bursts are triggered on click and when hovering over skill headers.

D. Interactive Sections

        1. 3D Flip Cards for Projects: Project titles flip to reveal descriptions, tech stack details, and links. Only one card can be flipped at a time to maintain focus.

        2. Accordion Skills Menu: Skills are organized into expandable categories for better readability and navigation.


E. Hidden Easter Eggs

        1. Terminal: Clicking the header name five times opens a fullscreen glass-style terminal. Commands include: help, projects, skills, and exit.

        2. Hidden Sea Chart: Typing nautical in the terminal reveals a wave animation and a hidden sea chart with the alias “The Nautical One.”

        3. Deep Sea Discovery: Clicking the footer text triggers an ASCII-art galleon animation with the signature: Captain on deck: The Nautical One.

        4. Developer Console Message: A custom-styled greeting appears in the browser console.

        5. Konami Code (Retro 8-Bit Mode): Entering the Konami Code transforms the entire site into a retro 8-bit style with pixel fonts and starfield background.

        6. Flappy Bird Mini-Game: Typing 2004 in the terminal launches a playable Flappy Bird overlay, dynamically themed based on the current site mode.

F. Technology Stack

        1. Core: HTML5, CSS3, JavaScript (ES6)

        2. Styling: Tailwind CSS (utility-first). All custom styles, animations, and glassmorphism effects are contained in a single <style> block.

        3. Fonts:
            a. Inter for body/UI text.
            b. Fira Code for terminal and ASCII art.
            c. Cinzel for nautical-themed easter eggs.
            d. Orbitron for neon hacker mode.
        4. Deployment: GitHub Pages.

G. Code Structure

        1. Single File: Entire project is contained within index.html for simplicity and portability.

        2. Head Section: Meta tags, external assets (Tailwind, Google Fonts), and custom <style> block with keyframes and effects.

        3. Body Section:
            a. <header>: Fixed navigation bar.
            b. <main class="flex">: Horizontal scroll container holding all sections (Hero, About, Projects, Skills, Contact).
            c. <section class="page-section">: Each section styled to fill viewport width and height.
            d. Hidden modals & overlays (Terminal, Sea Chart, Flappy Bird, Deep Sea Discovery) located at the end of the body.
        4. Script Section:
            a. Single <script> at the end of the body.
            b. Wrapped in DOMContentLoaded for reliable execution.
            c. Handles horizontal scrolling, navigation, mobile menu toggle, card flips, skills accordion, theme switching, sky chart rendering, particle effects, and all easter egg logic.
