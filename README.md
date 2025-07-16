# Create README.md file for GitHub documentation
echo """# Event Horizon Searcher

Event Horizon Searcher is a web-based application designed to search, filter, and analyze event logs efficiently. It is ideal for developers, system administrators, and security analysts who need to track, debug, or audit system behavior through log data.

 Features
- Upload and parse event log files
- Search logs using keywords or custom queries
- Filter logs by timestamp, type, severity, and source
- Highlight errors or critical logs visually
- Responsive UI built with modern frontend technologies

Tech Stack
- *Frontend:* React / Next.js
- *Styling:* Tailwind CSS / Bootstrap
- *Backend:* Node.js (if applicable)
- *Deployment:* Vercel
- *Version Control:* Git & GitHub

 How to Run Locally
bash
git clone https://github.com/Bharadwaj2904/event-horizon-searcher.git
cd event-horizon-searcher
npm install
npm run dev  # or npm start

Visit: http://localhost:3000
""" > README.md 
