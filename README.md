# finalTaHack
Step 1: 
Open terminal and go to any directories, desktop, documents, downloads
- git clone "link"

Step 2:
Open FinalTahack Folder
- cd Finaltahack

Step 3: 
Install venv on folder with the same directory as manage.py
- python -m venv "filename ng virtualenv nyo"

Step 4:
Run virtual environment
- In the root folder where it contains the manage.py
- .\venv\Scripts\activate

Step 5:
- Install the needed requirements
- pip install -r requirements.txt

Step 6:
- Check if tailwindcss is downloadded successfully by checking the version
- tailwindcss

Step 5:
- Run tailwindcss
- tailwindcss -i ./static/src/main.css -o ./static/src/output.css --minify --watch

Step 6:
- Run Server
- python manage.py runserver
