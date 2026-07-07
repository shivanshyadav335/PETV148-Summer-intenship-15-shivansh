# PETV148-Summer-intenship-15-shivansh 
Website Metadata Extractor
A simple Flask-based web application that scans a website's HTML source and extracts useful metadata such as:

HTML Meta Tags
Page Title
Generator Information
Author Name
HTML Comments
Linked Images
PDF Files
Technology Information (if available)
Features
Extract website metadata
Find hidden HTML comments
Detect author and generator meta tags
List downloadable PDF files
Display image links
Clean and simple web interface
Invalid URL protection
Technologies Used
Python 3
Flask
BeautifulSoup4
Requests
HTML
CSS
Installation
Clone the repository
git clone https://github.com/shivanshyadav335/website-metadata-extractor.git
Move into the project folder
cd website-metadata-extractor
Install dependencies
pip install -r requirements.txt
Run the application
python app.py
The application will start on:

http://127.0.0.1:5000/
Project Structure
website-metadata-extractor/
│
├── static/
├── templates/
├── app.py
├── requirements.txt
├── Procfile
└── README.md
How It Works
Enter a website URL.
The application downloads the webpage.
It extracts metadata from the HTML source.
Hidden HTML comments are detected.
Images and downloadable PDF links are listed.
The extracted information is displayed in an organized format.
Future Improvements
Detect CMS and framework versions
Export metadata as PDF or CSV
Scan additional document types
Improve technology detection
Generate detailed reports
Author
Shivansh yadav 

GitHub: https://github.com/shivanshyadav335

License
This project is created for educational purposes.
