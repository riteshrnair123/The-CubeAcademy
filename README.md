🧩 The Cube Academy | WCA Mastery Classes
Project Overview
The Cube Academy is a single-page, fully responsive static website designed to promote and manage online speedcubing classes. The academy, led by WCA competitor Ritesh R Nair, offers tiered curriculum focused on mastering the 12 core World Cube Association (WCA) events, from beginner methods to expert-level techniques like Full CFOP, CLL, and Yau.

The site is built for lead generation, providing a professional and engaging platform for potential students to view course offerings and submit enrollment inquiries.

✨ Key Features
Single-Page Application (SPA) Simulation: Uses client-side JavaScript for smooth, rapid navigation between four distinct views (Events, Courses, Instructor, Contact) without page reloads.

Comprehensive Curriculum: Detailed breakdown of course tiers: Foundation, Advanced Speed, and Ultimate Speedcubing Tier, covering 12 WCA events.

Expert Instructor Profile: Dedicated page featuring WCA competitor Ritesh R Nair (WCA ID: 2022NAIR06), complete with a professional profile image.

Fully Responsive Design: Built with Tailwind CSS to ensure optimal viewing and usability on all devices (mobile, tablet, and desktop).

Form Integration: Enrollment and contact inquiries are handled using a Formspree endpoint, eliminating the need for a custom backend server.

Social Proof: Dedicated section on the Courses page featuring sample 4-star customer reviews.

🛠 Tech Stack
HTML5: Core structure and content.

Tailwind CSS: Utility-first framework for all styling and responsive layout management.

JavaScript: Client-side scripting for navigation, modal management, and content rendering.

Formspree: External service for handling secure form submissions via email.

🚀 Local Setup & Running the Site
This project is a single static HTML file and requires no server configuration to run locally.

Clone the Repository:

git clone [YOUR_REPO_URL]
cd cube-academy

Ensure Image is Present:
Verify that the instructor's image file (PHOTO-2025-05-15-21-55-37.jpg) is located in the same directory as rubiks_classes.html.

Run Locally (Easiest Method):
Simply double-click the rubiks_classes.html file in your file explorer. It will open instantly in your default web browser.

Run with VS Code (Recommended for Development):

Install the "Live Server" extension (by Ritwick Dey) in VS Code.

Right-click rubiks_classes.html and select "Open with Live Server" to view the site and enable automatic browser refreshing on save.

📧 Form Submission Configuration
To receive inquiries submitted through the "Enrollment Inquiry" modal, you must configure the Formspree link:

Get Your Endpoint: Create a free form on Formspree and copy the unique endpoint URL (e.g., https://formspree.io/f/xbjnopqo).

Update HTML: Open rubiks_classes.html and replace the placeholder URL on Line 622 with your unique Formspree endpoint:

<form id="enrollment-form" action="YOUR_UNIQUE_FORMSPREE_URL_HERE" method="POST">
