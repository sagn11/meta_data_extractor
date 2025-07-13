File Metadata Extractor API

  

A lightweight Flask API that accepts file uploads and returns metadata including filename, file type, size in KB, and timestamp.

  

Endpoints:

  

POST /upload

Upload any file as form-data under the key `file`.

  

Example Response:

{

"filename": "example.pdf",

"type": "application/pdf",

"size\_kb": 142.35,

"timestamp": "2025-07-13T16:01:12.843275"

}

  

Setup:

  

pip install -r requirements.txt

python app.py

  

Go to: [http://localhost:5000](http://localhost:5000)

  

Tech Stack:

  

*   Python 3



*   Flask

