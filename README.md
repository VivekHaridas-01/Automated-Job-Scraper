# Automated-Job-Scraper
## Introduction
The **Automated Job Scraper** is a Generative AI agent designed to simplify the job-hunting process. It aggregates job listings from platforms like Indeed based on user-defined preferences such as role, location, and resume skill set. The project leverages advanced scraping techniques and AI-based analysis to provide relevant job listings tailored to the user's profile.

## Getting Started
To set up the project and install the necessary dependencies, follow these steps:
1. Clone the repository:
```
git clone https://github.com/VivekHaridas-01/Automated-Job-Scraper.git
cd Automated-Job-Scraper
```
2. Install the required Python dependencies:
```
pip install -r requirements.txt
```
3. Additionally, install the python-jobspy package (_Python version >= [3.10](https://www.python.org/downloads/release/python-3100/) required_):
```
pip install -U python-jobspy
```
4. Launch the application by running the main script:
```
python app.py
```

## Features
- Upload a resume to customize job searches based on skills.
- Filter job listings by preferred role and location.
- Interactive agent for real-time queries about job recommendations.
- Access detailed job descriptions with one click.
- Maintain a history of relevant jobs viewed or applied.
- Replace the uploaded resume anytime for updated searches.
- Export job listings in CSV format (if applicable).

## Demonstration

Below are key sections of the **Automated Job Scraper** with relevant visuals showcasing the interface and functionality.

### 1. Landing Page
This is the starting page where users can upload their resumes to begin the job scraping process.

![Landing Page](images/1.png)

---

### 2. Preferences Page
Users can specify their preferences such as **Preferred Job Role** and **Location** to tailor job recommendations.

![Preferences Page](images/2.png)

---

### 3. Interactive Interface
The job agent provides an interactive experience where users can ask questions and browse recommended jobs.

![Interactive Interface](images/3.png)

---

### 4. Relevant Job Descriptions
By clicking "View Details" on a job card, users can access a comprehensive job description.

![Relevant Job Descriptions](images/4.png)

---

### 5. Resume Tab
In the **Resume Tab**, users can view and replace their uploaded resumes.

![Resume Tab](images/5.png)

---

### 6. History of Relevant Jobs
The **Job History** tab displays previously applied or viewed job recommendations.

![History of Relevant Jobs](images/6.png)

---

### 7. Interaction Example
An example of a conversation where the agent provides job listings based on the user's query.

![Interaction Example](images/7.png)

---

## Future Updates
- Cleaner UI and output display
- Apply to jobs directly from the UI. Integrate job application history.
- Integrate Scraping from other websites like LinkedIn without limit.
