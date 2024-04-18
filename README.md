
# Image to PDF Converter

This is a small tool to convert images to PDF.




## Features

- Takes png, jpg and jpeg
- Coverts to PDf
- Downloads instantly
- API support


## Tech Stack

**Client:** HTML, TailwindCSS

**Server:** Python, Flask


## API end point
- the end point is `/api/upload`
- the method is `POST`
- accepts an array of files
- returns a url to download the pdf

## Running the Project
- Your machine needs to have latest version of python

## Then run this commands
- python -m venv venv
- venv\Scripts\activate
- `pip install -r requirements.txt`
- `python app.py`

Then go to http://127.0.0.1:5000/

