![Screenshot 2024-07-23 012850](https://github.com/user-attachments/assets/52f7f742-a142-4db2-83bc-af76ed628a58)![Screenshot 2024-07-23 012903](https://github.com/user-attachments/assets/c4825ffb-0861-4f04-8404-0ae7f59a140c)

# Resume Analyzer using NLP

## Project Description
The Resume Analyzer is a tool designed to automate the extraction and analysis of key information from resumes using Natural Language Processing (NLP) techniques. This project aims to streamline the resume screening process, making it faster and more accurate for HR departments and recruiters.

## Features
- Extracts names, emails, phone numbers, and skills from resumes.
- Supports PDF format.
- Utilizes NLP techniques for information extraction.
- Provides a user-friendly interface using Streamlit.

## Technology Stack
- **Programming Language:** Python
- **Libraries:**
  - `pdfminer3`: For PDF parsing
  - `pyresparser`: For resume parsing
  - `streamlit`: For creating the web app
  - `pandas`: For data manipulation
  - `pafy`, `youtube-dl`: For video processing
  - `plotly`: For data visualization
  - `pymysql`: For database connection
  - `streamlit-tags`: For tagging UI
  - `Pillow`: For image processing
  - `nltk`, `spacy==2.3.5`: For NLP

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/resume-analyzer.git
   cd resume-analyzer
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Download NLTK and spaCy resources:**
   ```bash
   python -m nltk.downloader all
   python -m spacy download en_core_web_sm
   ```

## Usage
1. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
   ```

2. **Upload a resume in PDF format through the web interface.**

3. **View the extracted information displayed on the web app.**

## System Architecture
- **Input:** PDF resumes
- **Processing:**
  - Text extraction using `pdfminer3`
  - Information extraction using NLP (tokenization, NER, regex)
- **Output:** Structured data (name, email, phone, skills, etc.)
- **User Interface:** Streamlit web application

## Demo
A live demonstration of the application can be found [here](#).

## Challenges
- Ensuring high accuracy in extracting relevant details.
- Handling different resume formats and structures.
- Optimizing the system for faster processing of large volumes of resumes.

## Future Work
- Support for more file formats (e.g., DOCX, TXT).
- Integration with Applicant Tracking Systems (ATS).
- Advanced analytics and reporting features.
- Incorporating machine learning models to improve extraction accuracy.
![Screenshot 2024-07-23 012833](https://github.com/user-attachments/assets/37768e0d-ebc1-49af-a3d8-6d9e3bb8b966)
![Screenshot 2024-07-23 012757](https://github.com/user-attachments/assets/b4cfb12c-a38b-4215-a8e9-990759455af3)
![Screenshot 2024-07-23 012408](https://github.com/user-attachments/assets/864ada91-78de-48a5-90d0-d4403aea87ba)
![Screenshot 2024-07-23 012353](https://github.com/user-attachments/assets/7948f67a-e140-4f7e-8af3-0a00383e10e1)
![Screenshot 2024-07-23 012333](https://github.com/user-attachments/assets/da96245d-a29d-4307-ab5b-60571cdd4c69)
![Screenshot 2024-07-23 012145](https://github.com/user-attachments/assets/dd1c24a2-73dc-4778-8304-54ed36fe4e92)



## Contact
**Rakesh Rana**  
Email: ranrakesh8328@gmail.com 


---

Feel free to customize this README file with specific details and links as needed.
