# Smart Lender - AI Powered Loan Approval Prediction System

Automating and accelerating the credit underwriting lifecycle using advanced Machine Learning models integrated into a secure Flask web application.

---

## 📖 Abstract & Overview
**Smart Lender** is an intelligent, data-driven web application designed to evaluate loan applicant profiles and predict credit eligibility. By transitioning from manual credit verification to an automated prediction system, financial institutions can significantly reduce processing times, eliminate human inconsistency, and improve decision accuracy.

The system processes applicant demographics and financial records (e.g., income, credit score, education, assets) and applies a trained **XGBoost Classifier** to deliver instant loan approval decisions (Approved or Rejected).

---

## 🚀 Key Features
- **Instant Eligibility Assessment:** Provides real-time loan approval classification.
- **Robust Preprocessing Pipeline:** Integrated imputation of missing values, SMOTE (Synthetic Minority Over-sampling Technique) to balance target classes, and feature scaling.
- **Multi-Algorithm Comparison:** Developed and evaluated using Decision Tree, Random Forest, K-Nearest Neighbors (KNN), and XGBoost algorithms.
- **User-Friendly Interface:** Intuitive HTML5/CSS3 frontend forms for entering applicant details and rendering eligibility decisions.
- **High Performance Backend:** Lightweight Flask server with serialized model execution (`.pkl`).

---

## 🛠️ Technology Stack
- **Backend Core:** Python 3.x, Flask
- **Data Engineering:** Pandas, NumPy
- **Machine Learning:** Scikit-learn, XGBoost
- **Visualization:** Matplotlib, Seaborn
- **Frontend Layer:** HTML5, CSS3, Vanilla JavaScript
- **Serialization:** Pickle

---

## 🏗️ Solution Architecture
The application follows a standard **Three-Tier Architecture**:
1. **Presentation Layer (Frontend):** 
   - `home.html` - Application entry point.
   - `predict.html` - Form to input applicant financial data.
   - `submit.html` - Displays the final loan approval prediction.
2. **Application Layer (Backend Server):**
   - Flask API Gateway (`app.py`) for handling client request routing.
   - Inference module for data scaling, input alignment, and executing model predictions.
3. **Data & Model Layer (Storage):**
   - Serialized XGBoost model (`.pkl` file).
   - Historical loan applications dataset.

---

## 📂 Repository Structure
```directory
├── 1. Brainstorming & Ideation
│   ├── Brainstorming & Idea Prioritization.pdf
│   ├── Define Problem Statements .pdf
│   └── Empathy Map.pdf
├── 2. Requirement Analysis
│   ├── Customer Journey Map.pdf
│   ├── Data Flow Diagram.pdf
│   ├── Solution Requirements.pdf
│   └── Technology Stack.pdf
├── 3. Project Design Phase
│   ├── Problem-Solution Fit.pdf
│   ├── Proposed Solution.pdf
│   └── Solution Architecture.pdf
├── 4. Project Planning Phase
│   └── Project Planning.pdf
├── 5. Project Development Phase
│   ├── Code-Layout, Readability and Reusability.pdf
│   └── Coding & Solution.pdf
├── 6.Project Testing
│   └── Performance Testing.pdf
├── 7.Project Documentation
│   ├── Project Executable Files.pdf
│   └── Sample Project Documentation.pdf
└── 8.Project Demonstration
    ├── Communication.pdf
    ├── Demonstration of Proposed Features.pdf
    ├── Project Demo Planning.pdf
    ├── Scalability & Future Plan.pdf
    ├── Team Involvement in Demonstration.pdf
    └── README.md (This file)
```

---

## ⚙️ Running the Project Locally

### 1. Prerequisites
Ensure you have Python 3.8+ installed on your system.

### 2. Install Dependencies
```bash
pip install flask pandas numpy scikit-learn xgboost
```

### 3. Run the Flask Web Application
1. Open terminal/cmd prompt.
2. Navigate to the development directory:
   ```bash
   cd "5. Project Development Phase"
   ```
3. Execute the server script:
   ```bash
   python app.py
   ```
4. Access the web interface at `http://127.0.0.1:5000/`.

---

## 👥 Project Team Details
* **Department:** Computer Science and Engineering
* **College:** Vishnu Institute of Technology
* **Git Repository URL:** [https://github.com/dharani756/Smart-Lender](https://github.com/dharani756/Smart-Lender)

### Team Members
- **Palli Dharani** (Team Leader)
- **Saikiran Kudipudi**
- **Yarabarla Manidweep**
- **Sita Rama Raju Datla**
- **Thota Leela Sai Krishna**
