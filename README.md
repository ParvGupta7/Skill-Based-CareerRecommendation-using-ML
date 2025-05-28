# Skill-Based Job Recommendation System 💼🚀

A lightweight, interpretable, and modular machine learning system that recommends jobs based on your current skillset, highlights your skill gaps, and suggests a personalized learning path to bridge them.

## 🔍 Overview

This project helps users:
- Get job recommendations based on their current technical skills.
- Understand how close they are to their desired job role.
- Identify missing skills (Skill Gap Analysis).
- Receive curated course recommendations to upskill.
- Track career progress dynamically.

It is implemented as a web application using **Streamlit** and **scikit-learn**, using structured `.csv` datasets.

---

## 🧠 How It Works

### 📌 Step-by-Step Workflow:
1. **User inputs their skills** using checkboxes.
2. System **vectorizes skills** using `MultiLabelBinarizer`.
3. **KMeans clustering** groups similar job roles.
4. **KNN** recommends jobs that best match user’s profile.
5. Missing skills are extracted via vector difference.
6. Mapped learning resources are suggested for each gap.
7. Everything is shown instantly via the Streamlit frontend.

