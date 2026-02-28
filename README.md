<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# [Project Name] 🎯
careguide-medical-support

## Basic Details

### Team Member
- Member 1: Tina Ann Thomas

### Hosted Project Link

[mention your project hosted link here]

### Project Description
CareGuide – A smart emergency support web application that evaluates symptom severity and suggests the appropriate medical department and nearby hospitals with direct contact and Google Maps integration.When every minute matters, CareGuide provides structured guidance and fast emergency recommendations.
### The Problem statement
In medical emergencies, timely and accurate decisions can save lives. Many people struggle to quickly identify the severity of symptoms, the appropriate medical department, and nearby hospitals with immediate contact options. Existing solutions are often fragmented, requiring users to manually search for hospitals, verify emergency services, and figure out which department to approach, leading to dangerous delays

### The Solution
CareGuide addresses this problem by providing a smart, symptom-driven web application that:

Evaluates the severity of the user’s symptoms (Low / Medium / High)

Suggests the correct medical department

Displays nearby hospitals with 24×7 emergency availability

Provides direct contact numbers and Google Maps navigation

Offers urgent actions like “Call Ambulance 108” for high-risk cases

By consolidating emergency guidance, hospital information, and immediate action prompts, CareGuide reduces decision-making delays and ensures faster, structured support during critical medical situations.

## Technical Details
Key Technical Details


### Technologies/Components Used

**For Software:**
- Languages used: [html,CSS,Javascript]
- Tools used: [e.g., VS Code, Git, ]

## Features
# Key Features

Symptom-based emergency level detection

Department recommendation system

District and city-based hospital filtering

24×7 emergency identification

Click-to-call integration

Direct Google Maps redirection

Clean and responsive UI

## Implementation
# How It Works
1. Symptom Configuration System

Each symptom is mapped to:

Severity level (Low / Medium / High)

Required medical department

Emergency message

Example:

Breathing Difficulty → High Severity → Emergency Department

2. Hospital Filtering Logic

The system filters hospitals based on:

Selected district

Selected city

Required department availability

If severity is High, hospitals with 24×7 emergency services are prioritized.

3️. Emergency Handling

For high severity cases:

Displays urgent alert

Shows "Call Ambulance 108 Immediately"

Highlights emergency-ready hospitals

Hospital Database

The system includes structured hospital data across multiple districts in Kerala, including:

District

City

Hospital Name

Address

Emergency Availability

Main Contact Number

Department-wise Contact Numbers

Google Maps Link


### For Software:

#### Installation
```bash
git clone https://github.com/tina-ann-thomas/careguide-medical-support.git
```

#### Run
```bash
cd careguide-medical-support
```

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)
<img width="1841" height="912" alt="image" src="https://github.com/user-attachments/assets/e33d8af1-94ec-4cb2-a2ad-29083301254b" />
<img width="1380" height="680" alt="image" src="https://github.com/user-attachments/assets/1691d15e-5ebd-4ee4-9ae0-63fa33d838b2" />
<img width="1613" height="832" alt="image" src="https://github.com/user-attachments/assets/559d17ac-e114-425c-b7d7-1a2496bc3a4c" />
<img width="1902" height="923" alt="image" src="https://github.com/user-attachments/assets/bcff9c7d-5f14-4965-a654-e05696de1f56" />

#### Diagrams

**System Architecture:**
<img width="831" height="718" alt="image" src="https://github.com/user-attachments/assets/11b13e7e-ec11-48ac-92dc-8e91cba09a96" />
**Application Workflow:**
1. Symptom Evaluation System

Each symptom is mapped to:

Severity Level: Low / Medium / High

Recommended Department: Emergency, Cardiology, Pulmonology, etc.

Emergency Message: Alerts for immediate action

The system uses JavaScript logic to process user inputs and determine the severity dynamically.

2. Hospital Filtering & Recommendation

Hospital database is structured with fields: District, City, Hospital Name, Address, Department Availability, Contact Numbers, 24×7 Emergency Status, Google Maps Link.

JavaScript filters hospitals based on:

User-selected District and City

Department availability matching the symptom

Prioritizes hospitals with 24×7 emergency services for high-severity cases

3. Emergency Handling & Actions

High severity cases trigger:

Urgent alert messages

“Call Ambulance 108” integration

Highlighted emergency-ready hospitals

Click-to-call functionality is implemented using HTML <a href="tel:..."> links.

Google Maps redirection uses embedded URLs for direct navigation.

4. User Interface

Built with HTML5, CSS3, and vanilla JavaScript

Clean, responsive layout suitable for mobile and desktop devices

Interactive forms for District, City, and Main Health Concern selection

Dynamic rendering of hospital lists, department recommendations, and emergency alerts

5. Project Goals

Reduce decision-making delay during emergencies

Provide structured symptom-to-department guidance

Enable instant access to hospitals and emergency services

6. Limitations & Disclaimer

CareGuide is a guidance tool, not a replacement for professional medical diagnosis

In life-threatening cases, users are advised to call emergency services immediately


## Project Demo
![demo video](video.mp4).
### Video

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g.,Gemini ChatGPT]

Made with ❤️ at TinkerHub
