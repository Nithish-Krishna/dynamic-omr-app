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

The **Dynamic OMR App** is a Flutter mobile application designed to simplify exam evaluation for teachers.  
It enables educators to **create OMR sheets, scan students’ responses, and generate results** with just a few taps — all through a single integrated interface.

> 🧩 Built as part of a company project (not deployed due to API pricing constraints).  
> Source code is private and shared here only for **demonstration and portfolio purposes**.

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

Below is a simplified walkthrough of how the app works:

1. **🏠 Exams Screen (Home)**  
   Displays a list of all created exams.  
   Teachers can add new exams or access existing ones.  
   *(Placeholder: ![Exam Screen](images/exam_screen.png))*

2. **📝 Create Exam**  
   Teachers input exam details such as:  
   - Exam name  
   - Class name  
   - Exam date  
   - Number of questions & columns  
   The app uses an API call to generate a matching OMR template.  
   *(Placeholder: ![Create Exam](images/create_exam.png))*

3. **🔑 Answer Key Setup**  
   Teachers select correct answers (A/B/C/D) for all questions via an intuitive interface.  
   Multiple answers per question are supported for multiple-correct patterns.  
   *(Placeholder: ![Answer Key](images/answer_key.png))*

4. **📷 Scan OMR Sheets**  
   Teachers enter a student name and scan the OMR sheet using the back camera.  
   Aspose API detects bubbles, evaluates answers, and stores the data locally via Hive.  
   *(Placeholder: ![Scan Page](images/scan_page.png))*

5. **📊 View Scores**  
   Displays student names, scores, accuracy stats, and question breakdowns.  
   Supports copying results for WhatsApp sharing and exporting to CSV/PDF.  
   *(Placeholder: ![Results Screen](images/results_screen.png))*

6. **📈 Student Analysis**  
   Detailed view per student — including each question’s chosen option, expected answer, and correction tools for teacher override.  
   *(Placeholder: ![Student Analysis](images/student_analysis.png))*

7. **🧾 Export & Manage**  
   - Download OMR sheet templates for printing  
   - Export class results  
   - Delete old exams  

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
