# 📱 PRAM App – QA Testing Project

This repository contains **manual testing artifacts** created while testing the PRAM mobile application.  
The app provides educational services, wellness services, and job/internship opportunities for students.

---

## 🔍 Scope of Testing
The testing focused on the following modules/screens:
- **Home Dashboard** (Educational & Wellness services)
- **Jobs for Students** (Internship, Fresher Jobs, Part-time Jobs)
- **Tuition Teacher / Coach** profiles
- **Educational Jobs** (Teacher roles like Yoga, EVS, etc.)
- **Service Providers** (Coaching, Hostels, Consultants)

---

## 📑 Test Cases
All detailed test cases with **Test ID, Expected Result, Actual Result, Status** are documented in:
👉 [`test-cases/PRAM_App_Test_Cases.xlsx`](./test-cases/PRAM_App_Test_Cases.xlsx)

### Example Test Cases:
| Test Case ID | Test Case Description | Expected Result | Actual Result | Status |
|--------------|-----------------------|-----------------|---------------|--------|
| TC001 | Educational Jobs - Missing job posted date | Job listing should display posting date | No posting date visible on listing | ❌ Fail |
| TC002 | Tuition Teacher/Coach - Same photos used | Each tutor should have unique profile photo | Duplicate stock image observed | ❌ Fail |
| TC003 | Jobs for Students - Limited role options | More diverse roles should be listed | Only broad role categories visible | ❌ Fail |
| TC004 | Notification Bell | Notification bell should open panel | Opens correctly | ✅ Pass |
| TC005 | Safety Tips | Safety tips should open and display content | Opens correctly | ✅ Pass |

---

## 🐞 Bug Reports  
Each bug is reported with:
- **Steps to Reproduce**
- **Expected vs Actual Result**
- **Screenshots (from `/screenshots`)**
- **Severity & Priority**

---

## 📸 Screenshots
Screenshots of the app modules tested:
- Home Dashboard  
- Jobs for Students  
- Tuition Teacher Profiles  
- Educational Jobs  

---

## 🛠️ Tools Used
- **Excel** → Test case design and execution
- **Mobile App (Android)** → Manual exploratory testing
- **Screenshots** → Visual documentation of issues
- **GitHub** → Portfolio & version control

---

## ✅ Key Learnings
- Designed and executed **5+ functional test cases** with clear pass/fail criteria.
- Identified **UI/UX issues** (duplicate images, missing posting date, limited job roles).
- Practiced **real-world bug reporting** with reproducible steps and screenshots.
- Hands-on experience in **test documentation** and portfolio building.

---

