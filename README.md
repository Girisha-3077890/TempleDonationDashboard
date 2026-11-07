# TempleDonationDashboard
Temple Donation Dashboard built on Salesforce - LWC Dashboard for simhachalam Temple tracking
# 🛕 Temple Donation Dashboard - Salesforce

> Live tracking of temple donations for Simhachalam Temple & other temples using Salesforce LWC.

### 🔗 Live Demo Screenshot
![Dashboard](https://via.placeholder.com/800x400?text=Upload+Your+Screenshot+Here)
*Note: Replace with your actual Lightning App Builder screenshot showing Top Temples - Donations*

### ✨ Features Built
- **Custom App:** `temple_donation_system`
- **Custom LWC:** `templeDonationDashboard`
- **Lightning App Page:** One Region Template in App Builder
- **Data:** Displays donation amount per temple (e.g., Simhachalam Temple - ₹2000, ₹500)
- **Use Case:** Temple management real-time donation tracking

### 🛠️ Tech Stack
- Salesforce Developer Edition
- Lightning Web Components (LWC)
- Lightning App Builder
- SOQL / Apex (for data fetching)
- GitHub for Version Control

### 📸 How it Works
1. LWC component fetches Donation__c records
2. Groups by Temple Name
3. Displays in App Page with progress bars - Top Temples

### 👨‍💻 Developer
**Girisha** | CSE Student | Visakhapatnam, AP
Built as part of Salesforce Admin + Development Learning

### 📂 How to Deploy in Your Org
1. Clone repo
2. Push LWC `templeDonationDashboard` via VS Code / SFDX
3. Create App Page in Lightning App Builder & drag component
4. Activate as Org Default
