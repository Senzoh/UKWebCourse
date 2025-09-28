# UKWebCourse
instructions = """UKWebCourse - Setup Instructions
=================================

A simple Node.js + Express + Tailwind CSS project.

Requirements
------------
- Node.js (v18+ recommended)
- npm (comes with Node.js)

Installation
------------
1. Clone the repository:
   git clone https://github.com/Senzoh/UKWebCourse.git
   cd UKWebCourse

2. Install dependencies:
   npm install

Development
-----------
Run the CSS watcher (Tailwind):
   npm run dev:css

Run the server with auto-reload (nodemon):
   npm run dev:server

Open your browser at:
   http://localhost:3000

Production Build
----------------
1. Build CSS (minified):
   npm run build:css

2. Start the server:
   npm start

Project Structure
-----------------
UKWebCourse/
├── public/              # Compiled CSS + static files
├── src/
│   └── styles/
│       └── input.css    # Tailwind input file
├── server.js            # Express server
├── package.json
└── README.txt
"""
