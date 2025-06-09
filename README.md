# 🎯 AI-Powered Resume Matcher – Frontend

This is the **frontend interface** of the **AI Resume Matcher** project – a smart web-based tool designed to help job seekers evaluate how well their resumes match specific job descriptions. Users can upload a resume and paste a job description, and the app visually displays the match score, keyword overlap, and suggestions for improvement.

---

## 🌐 Live Frontend

You can try out the live frontend here:  
**🔗 GitHub Pages:** [https://pallavirani123.github.io/resume-matcher-frontend](https://pallavirani123.github.io/resume-matcher-frontend)

The frontend connects to a Flask backend deployed on Render:  
**🛠 Backend API:** [https://resume-matcher-api-rkvj.onrender.com](https://resume-matcher-api-rkvj.onrender.com)

---

## 🧠 Features

- Upload resume files in **PDF, DOCX, or TXT** formats
- Paste any job description into a text area
- Click **Match Resume** to send data to the backend
- Displays:
  - ✅ **Match Score**
  - 🧠 **Matched Keywords**
  - 💬 **Suggested Feedback**
- Responsive UI with smooth pastel styling
- Fully integrated with the deployed backend using **JavaScript Fetch API**

---

## 📁 Project Structure
resume-matcher-frontend/
├── frontend.html # Main frontend HTML page
├── README.md # Project documentation


> Note: All frontend logic is written inside `frontend.html` (pure HTML + CSS + JavaScript)

---

## 🎨 Technologies Used

- **HTML5** – Structure and layout
- **CSS3** – Styling with soft pastel gradients
- **JavaScript (Fetch API)** – Handles backend interaction
- **Google Fonts** – `Quicksand` for a clean and modern look
- **GitHub Pages** – For deployment

---

## 🔄 How It Works

1. User uploads a resume file (PDF, DOCX, or TXT)
2. Pastes a job description in the provided box
3. Clicks the **Match Resume** button
4. The frontend sends a `POST` request to:
https://resume-matcher-api-rkvj.onrender.com/upload
5. The backend processes the resume + job description and returns:
- A keyword match score
- List of matched keywords
- Suggested keywords to add
6. The results are dynamically displayed in a beautiful output box

---

## 🧪 Example Output

✅ Match Score: 82.1% match based on keywords.

🧠 Matched Keywords: flask, experience, render, deployment, sagemaker, transformers, aws, python, resume...

💬 Feedback:
Try adding these keywords: including, backend, services


---

## 🚀 Deployment

To host this frontend yourself:

### 1. Fork and Clone

```bash
git clone https://github.com/pallavirani123/resume-matcher-frontend.git
cd resume-matcher-frontend

2. Open index.html in browser (for local testing)
Simply open it directly in a web browser. Ensure the backend API is accessible.

3. Deploy to GitHub Pages
Push changes to your main branch and enable GitHub Pages in your repo settings (point to main branch → / (root)).


🔗 Related Repositories
Backend Code: https://github.com/pallavirani123/resume-matcher-backend

👩‍💻 Developed By
Pallavi Rani Velagala
💡 Passionate about Data Science, NLP, and solving real-world job search problems using AI.
🔗 [LinkedIn](https://www.linkedin.com/in/pallavirani-velagala-41434625b/)
