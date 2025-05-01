# Cardano Constitution Reader & Search Tool

A simple, client-side web application for reading, searching, and interacting with the text of the Cardano Constitution. This tool is built with plain HTML, CSS, and JavaScript, requiring no backend or build process.

## Features

* **Full Text Display:** Renders the complete Cardano Constitution, including Preamble, Articles, and Appendices (Guardrails & Supporting Guidance).
* **Interactive Table of Contents (ToC):** Automatically generated ToC based on document headings (Articles and Sections) for quick navigation. The ToC is collapsible on mobile devices.
* **Live Search:** Search the entire constitution text in real-time. Matching terms are highlighted in snippets within the search results view.
* **Search Result Snippets:** Displays relevant snippets of text containing the search term, along with the corresponding heading. Clicking a result takes you to that section in the full view.
* **Checklist Functionality:** Mark specific sections (Articles or Sections with headings) as 'Compliant' (✓), 'Non-Compliant' (✕), or 'For Review' (?) using dedicated buttons next to headings.
* **Local Storage Persistence:** Your checklist selections are automatically saved in your browser's local storage, so they persist between sessions.
* **Clear Controls:** Buttons to easily clear the current search or reset all checklist selections.
* **Responsive Design:** Adapts to different screen sizes, ensuring usability on both desktop and mobile devices.

## How to Use

This is a static web application. You can use it in two main ways:

1.  **Locally:**
    * Clone or download this repository.
    * Navigate to the directory containing the files.
    * Open the `index.html` file directly in your web browser.

2.  **Web Hosting:**
    * Upload the `index.html`, `style.css`, and `script.js` files to any static web hosting service (like GitHub Pages, Netlify, Vercel, etc.).

## Files

* `index.html`: The main HTML structure of the application.
* `style.css`: Contains all the styling rules for layout, appearance, and responsiveness.
* `script.js`: Handles all the application logic, including:
    * Storing and parsing the constitution text (Markdown format).
    * Generating the HTML content and Table of Contents.
    * Implementing the search functionality.
    * Managing the checklist state and local storage interaction.
    * Handling UI events and responsiveness.

## Technology

* HTML5
* CSS3
* Vanilla JavaScript (ES6+)

## License

This project is licensed under the Apache License, Version 2.0.
