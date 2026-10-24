# Projects

## Project 1: CSE Department Portal (Official)
- **Problem:** The department had no single system for logins, results, materials, attendance and certificates.
- **Solution:** A multi-role PWA for students, faculty and HOD, covering results, materials, real-time attendance, certificate generation and a PDF toolkit. It serves 633 students and 72 faculty.
- **Technologies:** Node.js, Cloudflare Workers, Firebase, JavaScript, PWA
- **My contribution:** Designed and built the full system, frontend and backend. It was approved by the Pro Vice Chancellor as the department system of record.
- **Possible improvement:** Add automated tests and push notifications for results and attendance.

## Project 2: LoanIQ Risk — Loan Risk Prediction
- **Problem:** Manually judging how risky a loan applicant is, is slow and inconsistent.
- **Solution:** An ML app that classifies applicants as Low, Medium or High risk using 14 engineered features on a 5,098-record dataset. I benchmarked 12 models, and the tuned Logistic Regression reached 87.75% accuracy and 0.9721 macro ROC-AUC.
- **Technologies:** Python, Scikit-learn, XGBoost, Streamlit, Pandas, ReportLab
- **My contribution:** Did the feature engineering, model benchmarking and tuning, and built the Streamlit app with batch scoring, what-if analysis and PDF reports.
- **Possible improvement:** Train on a larger real-world dataset and add model monitoring.

## Project 3: Smartgen — Bulk Certificate Generator
- **Problem:** Creating certificates for hundreds of event participants by hand takes hours.
- **Solution:** Upload a CSV and get QR-verified, branded certificates generated in bulk and downloaded as a ZIP. It has been used for university events.
- **Technologies:** JavaScript, QR, CSV, GitHub Pages
- **My contribution:** Built the whole tool, including CSV parsing, certificate rendering and QR verification.
- **Possible improvement:** Add an online verification page and email delivery of certificates.

## Project 4: Jarvis — Offline AI Automation Agent
- **Problem:** Cloud AI assistants need internet access and send personal data to external servers.
- **Solution:** A fully offline ReAct-style agent that uses a local LLM with tool calling to automate tasks on my own computer.
- **Technologies:** Python, Ollama, Local LLMs
- **My contribution:** Wrote the agent loop, the tool-calling logic and the local model integration.
- **Possible improvement:** Add voice input and a confirmation step before running system commands.
