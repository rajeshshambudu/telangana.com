# 🏛️ Telangana State Surveyor Directory Portal
### *Independent Land Record Integrity & Verification System*

## 📌 Project Overview
A professional web portal designed to provide a searchable, verified directory of licensed land surveyors in Telangana. This project bridges the gap between raw public data and user-friendly verification tools, featuring digital credentialing and printable professional summaries.

## 🚀 Key Features
* [cite_start]**Dynamic Data Synchronization:** Real-time data fetching from Google Sheets (CSV) acting as a serverless CMS[cite: 11].
* [cite_start]**Professional Search:** Filter by Name, Phone Number, District, and Mandal[cite: 26].
* **Secure Verification:** URL-parameter-based validation logic for digital record confirmation.
* **QR Code Integration:** Automated generation of unique QR codes for every professional entry.
* **Print-Engine:** Specialized CSS for generating high-fidelity, formatted professional certificates.

## 🛠️ Tech Stack
* [cite_start]**Front-end:** HTML5, Tailwind CSS, JavaScript (ES6)[cite: 15, 26].
* **Libraries:** FontAwesome (Icons), QRCode.js (Dynamic QR generation).
* **Data Source:** Remote CSV (Google Sheets Integration).
* [cite_start]**Hosting:** GitHub Pages[cite: 16].

## 🏗️ DevOps Context
This project demonstrates several core DevOps principles:
1.  [cite_start]**Version Control:** Managed via Git and GitHub with clear branching[cite: 23].
2.  [cite_start]**Infrastructure:** Designed as a static, high-availability web app suitable for Azure Static Web Apps or Blob Storage hosting[cite: 18].
3.  [cite_start]**Security:** Implemented logic to ensure data integrity and clear legal disclaimers for public transparency[cite: 24].

## 📄 How it Works
1.  The app fetches the latest CSV data from a published Google Sheet.
2.  JavaScript parses the rows into a searchable object array.
3.  Users can search or scan a QR code to view a specific "Verified" profile.
4.  The "Print" function utilizes `@media print` CSS to hide UI elements and format a professional certificate.

---
[cite_start]*Created by [S.Rajesh Kumar] - Civil Engineer turned DevOps/Cloud Specialist*[cite: 1, 8, 34].# telangana.com
