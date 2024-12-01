# Smart Resume Analyser App

- Extracting user's information from the Resume, I used [PyResparser](https://omkarpathak.in/pyresparser/)
- Extracting Resume PDF into Text, I used [PDFMiner](https://pypi.org/project/pdfminer/).

## Features
- User's & Admin Section
- Resume Score
- Career Recommendations
- Resume writing Tips suggestions
- Courses Recommendations
- Skills Recommendations
- Youtube video recommendations

## Set Up & Installation of


## Getting Started

Clone the project

```bash
  git clone https://github.com/nevilsonani/TalentMatch.git
```

Go to the project directory

```bash
  cd my-project
```

Run following command.
  ```bash
  pip install -r requirements.txt
  ```
  
Start the server

```bash
  python app.py
```

- `App.py` is the main Python file of Streamlit Web-Application. 
- `Courses.py` is the Python file that contains courses and youtube video links.
- Download XAMP or any other control panel, and turn on the Apache & SQL service.
- To run app, write following command in CMD. or use any IDE.
  ```
  streamlit run App.py
  ```
- `Uploaded_Resumes` folder is contaning the user's uploaded resumes.
- `Classifier.py` is the main file which is containing a KNN Algorithm.. 

## Screenshots

## User side
<img src="https://github.com/nevilsonani/Resume_Analyser/blob/main/sc1.png">

## Admin Side
<img src="https://github.com/nevilsonani/Resume_Analyser/blob/main/sc2.png">



