# 🔬 Science Fair Projects Website
This project is a single-page, static HTML file (index.html) serving as the main landing page for an annual Science Fair. It provides information about the event, lists project categories, showcases multimedia content (videos/audio), and includes a project submission form and interactive elements (Canvas and Geolocation).

🚀 Key Features
Navigation Menu: A responsive drop-down menu for accessing different parts of the site (Student Details, Project, Rules, Management Console, Exit).

Project Catalog: A detailed table listing student groups, their project titles, and corresponding academic categories.

Multimedia Content: Embedded audio welcome message and multiple video presentations from Group Coordinators detailing expectations for different project categories.

Interactive Elements:

A Canvas element demonstrating basic graphics drawing.

Geolocation feature to find and display the user's current latitude and longitude.

Project Submission Form: A basic form to collect project metadata (Email, Demo URL, Date, Color).

About Us Section: Provides background information and a contact link for the organizing team.

📂 Project Structure
This file assumes the following directory structure for the media and external CSS files referenced in the code

.
├── index.html          (The provided code)
├── css/
│   └── style.css       (External stylesheet for layout and styling)
├── assets/
│   ├── imgs/
│   │   └── SciencefairBanner.jpg
│   ├── audio/
│   │   └── Audio.html  (This should likely be an .mp3 or similar audio file)
│   ├── video/
│   │   ├── webtech presenter.mp4
│   │   ├── Arctecturepresentor.html.mp4
│   │   ├── Statisticspresenter.html.mp4
│   │   ├── digitalDesignpresenter.html.mp4
│   │   ├── Databasepresenter.html.mp4
│   │   └── javapresentor.html.mp4
└── pages/
    ├── Studentdetails.html
    ├── project.html
    └── Rulesandcriteria.html


💡 Technologies Used
Technology	Purpose
HTML5	Structure and content definition.
CSS	Basic embedded styling and reliance on external style.css.
JavaScript (Inline)	Handling the dropdown menu, drawing on the Canvas, and managing the Geolocation API (navigator.geolocation).

Export to Sheets

▶️ Running Locally
Clone or Download: Get a copy of the index.html file and the required asset folders (as outlined above).

Open in Browser: Simply open the index.html file in any modern web browser (e.g., Chrome, Firefox) by double-clicking it.

Local Server Note: Links to the Science Fair Projects Management page point to a local host address (http://127.0.0.1:5501/...). To use this link, you must have the corresponding Node/MySQL CRUD application running locally on that port.
