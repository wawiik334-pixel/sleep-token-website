The Unveiling: Sleep Token Tribute Portal

A responsive, 4-page web application built as a tribute to the band Sleep Token. This project was developed for a Computer Information Technology curriculum to demonstrate mastery of multi-page site architecture, thematic CSS styling, and responsive interface design.

Technical Highlights
  - Thematic State Management: Utilizes unique <body> classes (e.g., .home-theme, .music-theme) to dynamically switch color palettes, background assets, and UI components across the site while maintaining a single global stylesheet.
  - Modern Layout Engine: Implements CSS Grid for complex member bios and Flexbox for the navigation system and media containers.
  - Responsive Media Handling: Employs @media queries to transform desktop-sidebars into mobile-stacked layouts, ensuring a high-quality UX on all devices.
  - Semantic HTML5 Architecture: Built with accessibility in mind using semantic tags like <article>, <section>, and <nav>, along with aria-current attributes to assist screen readers.

Project Structure
  - index.html: The "Water" themed landing page utilizing fixed-background parallax effects.
  - music.html: The "Earth" themed discography module featuring complex list structures and embedded media placeholders.
  - worship.html: The "Shadow" themed performance tracker using data tables to organize international tour dates.
  - vessels.html: The "Light" themed member portal featuring a CSS Grid biography section and a functional, styled contact form.

Technical Implementation Snippet: Responsive Logic
The site features a robust breakpoint system at 768px to handle shifting content:
/* Example of the breakpoint logic used to manage album layouts */

@media (max-width: 768px) {

    .album-details {
    
        flex-direction: column; /* Stacks content for mobile readability */
        
        align-items: center; 
        
    }
    
    .album-details img {
    
        max-width: 80%; /* Scales assets for smaller viewports */
        
    }
    
}

Setup and Use
  1. Clone the Repo: Ensure all folders (css/, media/) are kept in the same root directory as the HTML files.
  2. Launch: Open index.html in any modern browser.
  3. Navigation: Use the header-level navigation to move between the four thematic modules.
