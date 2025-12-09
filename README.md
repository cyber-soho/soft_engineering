Software Engineering Course Explorer

Overview

This project is an interactive, single-page application (SPA) designed to serve as the central navigation hub for a comprehensive Software Engineering course. It provides students with a visual "at a glance" understanding of the course structure, interactive module navigation, and quick access to assessments and critical disclaimers.

The interface is built to be clean, responsive, and user-friendly, utilizing Tailwind CSS for styling and Chart.js for data visualization.

Features

1. Visual Course Analytics

Topic Weight Visualization: A dynamic bar chart (powered by Chart.js) visualizes the density of the course, showing the number of sub-topics per main module. This helps students estimate the workload for each section.

2. Interactive Module Navigation

Accordion Design: To prevent information overload, the course content is organized into collapsible accordion sections.

Direct Access: Users can drill down into specific modules to find direct links to lecture notes, labs, and chapter files.

3. Assessment Hub

Provides quick access to Midterm and Final assessment materials, including review documents and Self-Assessment Questions (SAQs).

4. Legal & Security Compliance

Prominently displays safety warnings regarding lab environments (sandboxing requirements) and legal disclaimers regarding the use of security tools.

Technical Stack

Structure: HTML5

Styling: Tailwind CSS (via CDN)

Visualization: Chart.js (via CDN)

Icons: Inline SVG icons for UI elements

File Structure & Course Map

This index.html acts as the root entry point. Ensure the following files are present in the same directory for all links to function correctly:

/
├── index.html                                      # Main entry point (this file)
├── 01. intro.html                                  # Foundations of SE
├── 02. labs_overview.html                          # Intro to SE Labs
├── 03. ch-5.html                                   # Professional & Ethical Responsibility
├── 04. practice and requirements.html              # Software Processes (IEEE 1074)
├── 05.01. software design-1.html                   # Requirements Elicitation
├── 05.02. lab-1.html                               # Software Analysis
├── 06. software design-2.html                      # Software Design
├── 07. software coding.html                        # Software Coding
├── 08. ch-07.html                                  # Software Testing
├── 09. ch-08.html                                  # Software Delivery
├── 10. ch-22.html                                  # Configuration Management
├── 11. ch-15_16_17.html                            # Software Quality Assurance (New Link)
├── saqs.html                                       # Midterm Assessment SAQs
└── Midterm_Review.html                             # Comprehensive Exam Review


Usage

Download all files to a local directory.

Open index.html in any modern web browser (Chrome, Firefox, Edge, Safari).

Ensure you have an active internet connection to load the CDNs for Tailwind CSS and Chart.js.

Important Disclaimers

Security Warning

CRITICAL: All lab exercises involving security or network analysis must be performed in a secure, isolated virtual environment (sandbox). Unauthorized testing on public networks is strictly prohibited.

License

Copyright © 2025 Cyber Soho. All Rights Reserved.
This material is protected by intellectual property laws. Reproduction or distribution without written permission is prohibited.


