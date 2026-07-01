# SnapClass Landing Page

SnapClass Landing Page is a responsive Flask-based website created for **SnapClass Attendance**, an AI-powered attendance management system. The landing page introduces the project, showcases its key features, and provides access to the live attendance application.

## Live Links

- **Landing Page:** [https://snap-class-landing-page-six.vercel.app](https://snap-class-landing-page-six.vercel.app)
- **Main Attendance App:** [https://snapclass-attendance2026.streamlit.app/](https://snapclass-attendance2026.streamlit.app/)
- **Main App Repository:** [https://github.com/harshitha-karne/Snapclass-Attendance](https://github.com/harshitha-karne/Snapclass-Attendance)

## About The Project

This repository contains the frontend landing page for SnapClass Attendance. It is built using Flask with HTML, CSS, and JavaScript. The website explains the purpose of SnapClass and presents the product in a clean, simple, and user-friendly way.

SnapClass Attendance helps teachers automate classroom attendance using AI-powered face recognition, voice recognition, QR-based enrollment, and real-time attendance tracking.

## Features

- Responsive landing page design
- Flask route for rendering the homepage
- HTML template-based structure
- Custom CSS styling
- JavaScript-based frontend interactions
- Static image support
- Project overview section
- Feature showcase section
- Call-to-action button for the main app
- Clean deployment-ready structure

## Tech Stack

- **Python**
- **Flask**
- **HTML**
- **CSS**
- **JavaScript**
- **Jinja2 Templates**
- **Google Fonts**
- **Git and GitHub**

## Related Main App Tech Stack

The connected SnapClass Attendance app uses:

- Python
- Streamlit
- Supabase
- dlib
- face_recognition_models
- scikit-learn
- SVM Classifier
- NumPy
- Pandas
- Pillow
- librosa
- Resemblyzer
- bcrypt
- Segno

## Project Structure

```text
SnapClass-LandingPage/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── static/
│   ├── css/
│   │   └── styles.css
│   ├── img/
│   └── js/
└── templates/
    └── index.html
```

## Installation

Clone the repository:

```bash
git clone https://github.com/harshitha-karne/SnapClass-LandingPage.git
cd SnapClass-LandingPage
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

For Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running The Project

Run the Flask application:

```bash
python app.py
```

The project runs on:

```text
http://127.0.0.1:5002
```
## Deployment

The landing page is deployed online here:

```text
https://snap-class-landing-page-six.vercel.app
```

## Purpose

This landing page supports the main SnapClass Attendance system by giving users a quick overview of the product, its features, and its AI-powered attendance workflow.

## Repository

GitHub Repository: [https://github.com/harshitha-karne/SnapClass-LandingPage](https://github.com/harshitha-karne/SnapClass-LandingPage)

## Author

**Harshitha Karne**

## License

This project is open source and available for learning, portfolio, and academic use.