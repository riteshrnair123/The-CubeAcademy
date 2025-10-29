🧩 The Cube Academy | WCA Mastery Classes

Project Overview

The Cube Academy is a single-page, fully responsive static website for thecubeacademy.in, designed to promote and manage online speedcubing classes. The academy, led by WCA competitor Ritesh R Nair, offers a tiered curriculum focused on mastering World Cube Association (WCA) events, from beginner methods to expert-level techniques.

The site is built as a lead-generation platform, providing a professional and engaging interface for potential students to view course offerings, learn about the instructor, and submit enrollment inquiries or sign up for one-time solve critiques.

✨ Key Features

Single-Page Application (SPA) Feel: Uses client-side JavaScript for smooth, animated navigation between distinct views (Events, Courses, Instructor, Critique, Contact) without page reloads.

Comprehensive Curriculum: Detailed breakdown of course tiers: Foundation, Advanced Speed, and Ultimate Speedcubing.

Expert Instructor Profile: Dedicated page featuring WCA competitor Ritesh R Nair (WCA ID: 2022NAIR06), complete with a professional profile image and WCA stats.

Paid Solve Critiques: A dedicated page for a one-time "Solve Critique" service, linking to a Google Form for submission and payment.

Fully Responsive Design: Built with Tailwind CSS (via CDN) to ensure optimal viewing and usability on all devices (mobile, tablet, and desktop), including a mobile menu.

Formspree Integration: Enrollment and contact inquiries are handled via a Formspree endpoint in a pop-up modal, eliminating the need for a custom backend.

GitHub Pages Deployment: The repository is configured with a GitHub Actions workflow (static.yml) to automatically build and deploy the site to GitHub Pages.

Custom Domain: The CNAME file configures the GitHub Pages site to use the custom domain thecubeacademy.in.

🛠 Tech Stack

HTML5: Core structure and content.

Tailwind CSS: Utility-first framework for all styling and layout, loaded via CDN.

JavaScript (ES6+): All client-side logic (navigation, modal management, dynamic content) is contained within a <script> tag in index.html.

Formspree: Backend service for handling form submissions.

GitHub Actions: For CI/CD and deployment to GitHub Pages.

🚀 Local Setup & Running the Site

This project is a single static HTML file and requires no complex setup or server to run locally.

Clone the Repository:

git clone [https://github.com/riteshrnair345/thecubeacademy.git](https://github.com/riteshrnair345/thecubeacademy.git)
cd thecubeacademy


Ensure Assets are Present:
Verify that the image files (like PHOTO-2025-05-15-21-55-37.jpg) are in the same directory as index.html.

Run Locally (Easiest Method):
Simply double-click the index.html file in your file explorer. It will open directly in your default web browser.

Run with VS Code (Recommended for Development):

Install the "Live Server" extension (by Ritwick Dey) in VS Code.

Right-click index.html and select "Open with Live Server" to view the site. This will also enable automatic browser refreshing whenever you save changes.

(Note: The style.css and script.js files in the repository are minimal and not currently used by index.html. All core CSS and JavaScript logic is embedded directly within index.html.)
