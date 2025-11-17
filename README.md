# SMiShing Awareness Simulator  
Browser-based training tool for demonstrating how SMS phishing works in a safe, controlled environment.

## Overview  
A classroom-ready simulator that recreates realistic SMiShing scenarios without sending messages or collecting data. Trainees interact with mock SMS prompts while a live attacker preview illustrates what a malicious actor would see. Suitable for cybersecurity lessons, teacher workshops, and controlled demonstrations.

## Features  
-  **One scenario at a time:** Users receive a single SMS and choose to open, ignore, or report.  
- **Realistic messages:** Includes scenarios from BDO, GCash, SSS, Pag-IBIG, Globe, TikTok, Gmail, Microsoft, DepEd LIS, and others.  
- **Attacker preview:** Displays what a malicious actor could capture based on user actions.  
- **Trainer controls:** Seed scenarios, shuffle messages, push next scenario, and reset the session.  
- **Offline-ready:** No external dependencies; runs entirely in the browser.  
- **No Data Collection:** The simulator does not track, upload, or store any input.  
- Frontend only (HTML, CSS, JS).

## Intended Use  
- Cybersecurity awareness training  
- Teacher and staff orientation  
- Classroom demos for ICT or Senior High School  
- Workshops and seminars on digital safety

## File Structure  
/project-root
│── index.html
│── scenarios.js

## How to Run  
1. Download or clone the repository.  
2. Keep all files in the same folder.  
3. Open `index.html` in any modern browser.  
4. Click **Start Demo** to begin the simulation.  
5. Interact with the SMS prompts and observe the attacker preview.
or.
1. You can just click the Github Pages link here: 

## Safety Notes  
- The simulator does not access contacts, phone numbers, or messaging APIs.  
- No logs, credentials, or personal data are stored.  
- Designed strictly for education, awareness, and demonstration.

## License  
MIT License
