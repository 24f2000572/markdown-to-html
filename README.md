# Markdown to HTML Viewer

This project provides a simple, single-page web application (`index.html`) to dynamically convert and display Markdown content from an `input.md` file as styled HTML. It leverages modern web technologies to offer a clean and responsive viewing experience.

## Features

-   **Markdown Conversion:** Utilizes the `marked.js` library to parse Markdown into HTML.
-   **Responsive Design:** Built with Tailwind CSS for a mobile-first, responsive layout.
-   **Styled Content:** Employs Tailwind's `@tailwindcss/typography` plugin to automatically style the rendered Markdown content for optimal readability (e.g., headings, paragraphs, lists, code blocks).
-   **Single-File Application:** All necessary HTML, CSS (via CDN), and JavaScript (via CDN) are contained within `index.html`, making it easy to deploy or share.

## Getting Started

To use this Markdown viewer, simply follow these steps:

1.  **Save the files:** Ensure `index.html` and your Markdown file, named `input.md`, are in the same directory.
2.  **Open `index.html`:** Double-click `index.html` in your web browser.

The page will automatically fetch the content of `input.md`, convert it to HTML, and display it with a clean, readable layout.

## Project Structure

-   `index.html`: The main web page, containing the application logic and UI.
-   `input.md`: The Markdown file whose content will be converted and displayed.
-   `README.md`: This file, providing an overview and instructions.
-   `LICENSE`: The MIT License for the project.

## Technologies Used

-   **HTML5:** Structure of the web page.
-   **Tailwind CSS (CDN):** For utility-first CSS styling and responsive design.
-   **Marked.js (CDN):** For fast and easy Markdown parsing.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.