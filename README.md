first_site/
├── config.toml
├── content/
│ ├── _index.md
│ ├── students/
│ │ └── abhi.md, rahul.md, ...
│ └── teachers/
│ └── mrs-kapoor.md, ...
├── layouts/
│ ├── _default/
│ │ └── baseof.html
│ ├── students/
│ │ └── list.html, single.html
│ ├── teachers/
│ │ └── list.html, single.html
│ └── index.html
├── static/
│ └── images/
│ ├── students/
│ └── teachers/
└── public/ (generated)

yaml
Copy
Edit

---

## 🚀 Features

- 🔹 Homepage with portal intro
- 🔹 Students and Teachers listing
- 🔹 Detail pages for each student/teacher
- 🔹 Images, hobbies, and metadata for every profile
- 🔹 Modular layouts and partials
- 🔹 Clean URL routing (e.g. `/students/rahul/`)

---
hugo version
2. Run Development Server
bash
Copy
Edit
cd first_site
hugo server
Visit: http://localhost:1313

⚙️ Build for Deployment
bash
Copy
Edit
hugo
All static files will be generated in the public/ folder.
