PythonVerse Academy

Learn Python Libraries & Frameworks by Building Real Projects

PythonVerse Academy is a production-ready, highly interactive, responsive single-file Learning Management System (LMS), Browser IDE, and Project-Based Learning Platform. Designed with a clean, educational visual theme inspired by Coursera, GitHub Classroom, VS Code, and Replit, it replaces dry theoretical lectures with hands-on, sandbox-driven coding milestones.

🚀 Key Features

1. Unified Authentication System

Predefined Student Access: Students log in using secure predefined IDs (e.g., KD001, PJ002). Registration is disabled to maintain a controlled classroom roster.

Dedicated Admin Portal: Separate administrative credentials (ADMIN001) allow instructors to manage students, review live-submitted code, provide score ratings, request revisions, and broadcast platform-wide bulletins.

2. Interactive Browser IDE Sandbox (VS Code Style)

Multi-File Explorer: Real-time management of sandbox files (e.g., main.py, data.csv, README.md) with options to create, rename, delete, and download individual files.

Indentation Helper: Custom key handlers override browser default behavior to permit standard 4-space tab indentation.

Auto-README Generator: Craft GitHub-ready project descriptions automatically with a single click.

ZIP Exporter: Simulate and download the entire directory structure in a single packaged text configuration.

3. Bash Shell Simulator & Live Output Preview

Interactive Terminal: Custom terminal parser handling standard commands:

ls: List directory contents

touch [file] / mkdir [dir]: Create files and directories

cat [file]: Print file content streams

pip install [package]: Simulate library installation into the environment

python main.py: Compile and run primary scripts

Dynamic Graphical Previews: Renders realistic visualization blocks when specific Python paradigms are evaluated:

Matplotlib/Pandas/Plotly: Renders real responsive grade graphs and metrics.

OpenCV/Pillow: Simulates bounding box coordinate overlays for face detection.

FastAPI: Generates live, interactive Swagger docs with sample GET routes.

4. Project-Based Roadmaps & Quizzes

Syllabus Tracks: Covers Python Fundamentals, Data Science & Utilities (NumPy, Pandas, BeautifulSoup, SQLite3), and Enterprise Web Frameworks (FastAPI, Flask, Streamlit).

Gamified Achievements: Offers interactive micro-quizzes for each module that award platform XP and unlock custom daily streak badges.

🛠️ Technical Stack

Frontend: HTML5, CSS3, Tailwind CSS (Utility-first styling).

Core Engine: React 18.2 (Virtual DOM & State Management) transpiled dynamically with Babel.

CDNs: Hosted with global high-uptime jsDelivr CDNs ensuring uninterrupted loading on sandboxed environments and GitHub Pages.

State Persistence: Automatic, fail-safe JSON serialization utilizing localStorage with integrated safety try-catch blocks to protect against data corruption.

📂 Deployment & Installation

Local Execution

Download the index.html file from the Canvas editor.

Double-click index.html to open it directly in any modern web browser (Chrome, Firefox, Edge, Safari). No web server, Node.js, or local Python dependencies are required.

GitHub Pages Deployment

Create a public or private GitHub repository.

Rename the main academy file to index.html and commit it to the root of your repository.

Navigate to Settings -> Pages.

Set the Source branch to main (or master) and folder path to /root. Click Save.

Your platform is now globally accessible via your GitHub Pages URL!

👥 Seed User Database

Student Portals

Student Name

Predefined ID

Secure Password

Default Assigned Project

Kedar Chougale

KD001

Kedar@2026

Student Management System (Pandas, SQLite3, Matplotlib)

Pranav Jadhav

PJ002

Pranav@2026

Interactive Weather Dashboard (Requests, Plotly, JSON)

Rajlakshmi Khot

RK003

Raj@2026

Dynamic Expense Tracker (SQLite3, Tkinter, OpenPyXL)

Samruddhi Patil

SP004

Sam@2026

Adaptive Image Matrix Processor (OpenCV, Pillow, NumPy)

Kalyani Kamble

KK005

Kalyani@2026

Enterprise Library Engine API (FastAPI, SQLAlchemy, Pydantic)

Administrator Portal

Predefined Username: ADMIN001

Secure Password: Admin@Python2026

👨‍💻 Development & Customization

The workspace code is modularly structured in the HTML source file:

STUDENTS & STUDENT_TASKS: Modify these JSON variables to register additional students, redefine project criteria, or change code templates.

ROADMAP: Update this configuration array to introduce new libraries, alter quiz questions, modify industry use explanations, or add new frameworks.

BrowserIDE: To customize the bash outputs, add new command handlers to the executeTerminalInput switch block or define custom chart patterns in runPythonCode.
