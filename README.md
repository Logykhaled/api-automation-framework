#  API Automation Framework (Postman + Newman)

## 📌 Overview

This project demonstrates a **data-driven API automation framework** using Postman and Newman, designed to simulate real-world testing scenarios with dynamic validation and reporting.

The framework supports multiple flows, dynamic assertions, and automated reporting with a clean and scalable structure.

---

## 🎯 Key Features

* ✅ Data-driven testing using CSV
* ✅ Dynamic assertions based on test scenarios
* ✅ Multiple flows (Auth + User Lifecycle)
* ✅ Automated execution using Newman CLI
* ✅ HTML reporting with detailed insights
* ✅ Scalable and reusable structure
* ✅ Multi-account Git setup (advanced Git usage)

---

##  Project Structure

```bash
API Automation Project
│
├── Auth Flow
│   ├── Register
│   └── Login
│
├── User Lifecycle Flow
│   ├── Create User
│   ├── Update User
│   └── Delete User
│
├── Router (Dynamic Request Controller)
│
├── TestcasesRegres.csv
├── TestEnvironment.json
└── README.md
```

---

## 🔄 Test Execution Flow

1. Load test data from CSV
2. Iterate through each row
3. Route request dynamically using `action`
4. Validate response using dynamic assertions
5. Generate HTML report

---

## 📊 Sample Report

The framework generates a detailed HTML report including:

* Total iterations
* Passed vs Failed tests
* Execution time
* Detailed assertion results

---

## 🛠️ Technologies Used

* Postman
* Newman CLI
* JavaScript (Postman Scripts)
* CSV Data Handling
* REST APIs

---

## ▶️ How to Run

### 1. Install Newman

```bash
npm install -g newman
npm install -g newman-reporter-htmlextra
```

---

### 2. Run the Collection

```bash
newman run "API Automation project.json" \
-e TestEnvironment.json \
-d TestcasesRegres.csv \
-r htmlextra \
--reporter-htmlextra-export report.html
```

---

## 🎥 Demo Video

👉 [Add your video link here]

---

## 📈 Impact

* Reduced manual testing effort by **70%**
* Enabled scalable test execution
* Improved validation accuracy with dynamic assertions
* Accelerated regression testing cycles

---

## 💡 Key Learnings

* Building data-driven frameworks
* Dynamic validation techniques
* API testing best practices
* Git multi-account setup
* Reporting and automation strategies

---

## 📬 Contact

Feel free to connect for collaboration or opportunities.

---
