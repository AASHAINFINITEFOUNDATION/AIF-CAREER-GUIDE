# AIF-CAREER-GUIDE
🌐 CSE Career Roadmap Dashboard

An interactive learning portal designed by AASHA INFINITE FOUNDATION to guide Computer Science Engineering students from basics to advanced streams.
This dashboard provides smart flows with dropdowns, curated resources, and a collaboration section where students can share resumes and GitHub repositories.


🚀 Features

Basic foundations — programming languages, Data Structures & Algorithms, and Maths/Probability/Statistics.
Seven Career Streams:

Backend / Full‑Stack / Web Development
UI / UX Design
Cloud Computing & Databases
Data Science & Analytics
Systems Analysis & Enterprise Solutions
DevOps & MLOps
AI‑Powered Development (plus a dedicated AI & Machine Learning track)



Dropdown menus for each stream to reduce clutter and keep the page scannable.
Visual flowcharts (SVG) linked from each stream for a quick roadmap overview.
Portfolio & Collaboration section for students to add Resume and GitHub/Linktree links.
Minimalist design with muted pastel colors and compact icons — no frameworks, no build step.



📂 Project Structure

cse-roadmap-dashboard/
├── index.html              # Main page — all roadmap sections & dropdowns
├── styles.css              # Page styling (pastel theme, dropdown UI)
├── script.js               # Dropdown open/close behavior
├── README.md                # Project documentation (this file)
└── flowcharts/              # SVG roadmap diagrams, one per stream
    ├── 00-common-foundation.svg
    ├── 01-backend-fullstack.svg
    ├── 02-ui-ux.svg
    ├── 03-cloud-database.svg
    ├── 04-data-science.svg
    ├── 05-systems-analysis.svg
    ├── 06-devops.svg
    └── 07-ai-powered-dev.svg


🛠️ Tech Stack


HTML5 — page structure and content
CSS3 — styling and layout
Vanilla JavaScript — dropdown interactivity (no dependencies)
SVG — flowchart diagrams


No build tools, package managers, or frameworks are required — it's a fully static site.


▶️ Running Locally

Since this is a static site, you can open it directly in a browser:

bash# Option 1: just open the file
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux

# Option 2: serve it (recommended, avoids any local-file restrictions)
python3 -m http.server 8000
# then visit http://localhost:8000


🌍 Deployment

Because there's no build step, this project can be hosted on any static-site platform:


GitHub Pages — push to a repo, enable Pages on the main branch.
Netlify / Vercel — drag-and-drop the folder or connect the repo.
Any static web host — just upload the files as-is.



✏️ Customizing Content


Add/edit a resource: find the relevant <div class="roadmap"> block in index.html and add a new <a href="...">Label</a><br> line inside its dropdown-content.
Add a new stream: copy an existing roadmap block, update the button label and links.
Update flowcharts: replace or add SVGs in flowcharts/ and link them with a flowchart-link anchor.
Update student profiles: edit the list inside the Portfolio & Collaboration section at the bottom of index.html.



🤝 Contributing

Students are welcome to contribute additional free/quality resources, flowcharts, or improvements to the layout. Suggested workflow:


Fork the repository
Add your changes (new links, fixed links, design tweaks)
Open a pull request describing what you added



📄 License

This project is intended for free educational use. 
