# Veridia — Internship Hiring Platform  
Submission for Veridia Internship  
Deadline: October 20, 2025

## GitHub Repository
Repository link: https://github.com/Krishna-7772/Veridia-Internship.git

---

## Summary
Veridia is a single-page front-end application that implements an end-to-end internship application platform with separate Applicant and HR experiences. It includes a multi-step application form (with autosave/drafts), applicant dashboard, HR admin dashboard (filtering, sorting, bulk actions), built-in email templates, sample dataset and localStorage-backed data simulation for demo/testing. The UI uses Tailwind CSS with custom styles and some tasteful glass/gradient visuals.

---

## Tech stack
- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- LocalStorage (as mock backend)

---

## Features implemented
### 1. Multi-step Application Form
- Personal Details → Education & Skills → Experience & Submission steps
- Progress bar, validation, autosave & drafts (using localStorage)
- Resume upload and preview support

### 2. Applicant Dashboard
- Displays user profile, application history, and notifications

### 3. HR Dashboard
- Applicant summary cards, filtering, sorting, pagination, and bulk actions
- CSV export and simulated applicant data

### 4. Email Templates
- Predefined templates for submission confirmation, interview invite, and rejection
- Used in HR “Change Status” modal

### 5. Simulated Backend
- LocalStorage seeded with demo applications and user data (`init_local_db()`)

### 6. UI Enhancements
- Tailwind-based responsive design with gradients and glass-effect cards
- Dynamic modals, toasts, and progress components


---

## Login Credentials for testing:
HR Login Credentials

• Email: hr@veridia.com

• Password: hr123

• Name: HR Admin

• Role: HR

Purpose: Gives access to the HR Dashboard, where you can view, filter, and manage all applications.

Test Applicant Login Credentials

• Email: applicant@test.com

• Password: test123

• Name: Test Applicant

• Role: Applicant

Purpose: Logs into the Applicant Dashboard, where you can view and track your submitted applications.


## Screenshots Included
Placed in `assets/screenshots/` folder:

1. `01_hero_and_about.png` — Hero section with heading and stats  
2. `02_application_form_step1.png` — Personal details form  
3. `03_application_form_step2.png` — Education & Skills form  
4. `04_application_form_step3.png` — Experience & Resume upload  
5. `05_applicant_dashboard.png` — Applicant dashboard  
6. `06_hr_dashboard.png` — HR dashboard with filters and table  
7. `07_change_status_modal.png` — Email template modal

---

## Improvements Suggested
- Integrate backend (Node.js / Firebase)
- Add authentication and role-based access
- Implement email sending using SendGrid/Mailgun
- Add unit tests and linting

---

## Author
Developer: Krishna Pandey  
Internship: Veridia Internship Program  
Date: October 20, 2025


