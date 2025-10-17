<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Nithish-Krishna/dynamic-omr-app">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Dynamic OMR App</h3>

  <p align="center">
    A Flutter-based OMR Examination Management App for Teachers to Create, Scan, and Evaluate Exams Digitally
    <br />
    <a href="#">🎥 View Demo (Figma Prototype)</a>
    ·
    <a href="https://github.com/Nithish-Krishna/dynamic-omr-app/issues">Report Issue</a>
  </p>
</div>

---

## 📘 About the Project

The **Dynamic OMR App** is a Flutter-based mobile application built to streamline exam evaluation for teachers.  
It allows educators to **create OMR sheets, scan student responses, and generate detailed performance reports** — all from a single, intuitive interface.

---

> ⚠️ **Project Disclaimer**
> 
> - 🧩 Developed as part of an internal company project at **Vidwath Innovative Solutions Pvt. Ltd.**  
> - ❌ Not deployed to production due to API pricing constraints.  
> - 🖋️ Screenshots may include the **Vidwath** watermark or branding.  
> - 🔒 Source code remains private and is showcased here **for demonstration and portfolio purposes only**.



### 🎯 Core Purpose
Teachers often spend hours evaluating answer sheets manually.  
This app automates that process using **Aspose.OMR Cloud SDK**, allowing teachers to:
- Create custom OMR sheets for exams  
- Set answer keys for objective tests  
- Scan filled sheets via camera  
- Instantly generate and export results in CSV or PDF  

---

## 🛠️ Built With

* **Framework:** Flutter  
* **Language:** Dart  
* **Local Storage:** Hive (for caching & offline persistence)  
* **SDK:** Aspose.OMR Cloud SDK for Dart  
* **IDE:** Android Studio  
* **Architecture:** REST API–driven, cloud OMR recognition  

---

## ⚙️ Project Flow

Below is a simplified walkthrough of how the app works, along with key interface mockups:

---

### 🏠 1. Exams Screen (Home)
Displays a list of all created exams.  
Teachers can add new exams or access existing ones.

<p align="center">
  <img src="mockups/exam_details.png" alt="Exam Details" width="350"/>
</p>

---

### 📝 2. Create Exam
Teachers input essential exam details such as:
- Exam name  
- Class name  
- Exam date  
- Number of questions & columns  

The app uses an API call to automatically generate a corresponding OMR template.

<p align="center">
  <img src="mockups/create_exam.png" alt="Create Exam" width="350"/>
</p>

---

### 🔑 3. Answer Key Setup
Teachers define correct answers (A/B/C/D) for all questions through an interactive interface.  
Supports multiple-correct options for complex question patterns.

<p align="center">
  <img src="mockups/answer_key.png" alt="Answer Key" width="350"/>
</p>

---

### 📷 4. Scan OMR Sheets
Teachers enter a student’s name and scan their OMR sheet using the device camera.  
Aspose API detects bubbled responses, matches them with the answer key, and stores results securely via Hive.

<p align="center">
  <img src="mockups/scan_screen.png" alt="Scan Screen" width="350"/>
</p>

---

### 📊 5. View Scores
Displays all students’ names, total marks, percentages, and question-wise accuracy.  
Includes **copy**, **CSV/PDF export**, and **share** options for quick result dissemination.

<p align="center">
  <img src="mockups/student_details.png" alt="Student Details" width="350"/>
</p>

---

### 📈 6. Student Analysis
A detailed breakdown per student showing:
- Question number  
- Selected vs. Correct answer  
- Auto-evaluated result (✅/❌)  
- Editable answers for teacher corrections or disputes  

<p align="center">
  <img src="mockups/student_analysis.png" alt="Student Analysis" width="350"/>
</p>

---

### 🧾 7. Edit Answers  
Teachers can review and modify individual student responses if scanning errors or disputes occur.  
Each question entry shows:  
- Question number  
- Student’s marked option  
- Correct answer  
- Result (✅ / ❌)  
- Editable input for manual correction  

<p align="center">
  <img src="mockups/edit_answer.png" alt="Edit Answer" width="350"/>
</p>

---

### 📤 8. Export & Manage  
Teachers can:  
- Download printable OMR sheet templates  
- Export class-level reports (CSV or PDF)  
- Delete outdated exams or results

---

## ☁️ APIs Used

| Function | Description |
|-----------|-------------|
| Create OMR Sheet | Generates OMR templates based on teacher inputs |
| Scan OMR Sheet | Recognizes bubbled answers and returns response data |
| Result Calculation | Matches scanned responses with answer key |
| Export Results | Generates downloadable CSV/PDF reports |

All API interactions are performed securely via **Aspose.OMR Cloud SDK for Dart**.

---

## 💡 Challenges & Learnings

**Challenges faced:**
- Managing API latency while scanning multiple sheets in real-time.  
- Handling edge detection and skewed scans gracefully.  
- Optimizing local caching with Hive for seamless navigation.  
- Designing a smooth UX flow for teachers with minimal tech experience.

**Learnings:**
- Deeper understanding of SDK integration and REST APIs in Flutter.  
- Building modular UI architecture for scalable state management.  
- Balancing between cloud-based scanning and local data handling.  

---

## 🚧 Future Roadmap

- [ ] Offline scanning support using on-device ML models  
- [ ] Student portal for individual performance tracking  
- [ ] Admin dashboard for multi-class management  
- [ ] Improved OMR template customization  

---

## 👨‍💻 Developer

**👤 Nithish Krishna K S**  
Junior Software Developer @ Vidwath  
📍 Mysuru, Karnataka  
📧 [nithish.krishna0101@gmail.com](mailto:nithish.krishna0101@gmail.com)  
🌐 [nk.xo.je](https://nk.xo.je)  
🔗 [LinkedIn](https://linkedin.com/in/nithishkrishna01)

---

## 🗒️ Notes

> 🔒 *This project was developed as part of a company initiative.  
Source code is private and shared here only for portfolio demonstration.*  

> 🧠 *All API keys, configurations, and assets have been omitted for confidentiality.*

---

<p align="right">(<a href="#readme-top">back to top</a>)</p>
