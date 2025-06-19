# Patagonia app
When you download and save the zip folder of the Patagonia Suggestion App, here's how to run it:

On Your Local Machine:
Extract the zip file to a folder on your computer
Go to the project directory in your terminal/command prompt
Install Python dependencies (if you have a pyproject.toml or requirements.txt):
pip install flask
Run the application:
python main.py
Access the app at http://localhost:8080 in your browser
Back on Replit:
If you want to upload the project back to a new Repl:

Create a new Python Repl
Upload your files using the file manager
The app will run automatically when you click the Run button

Important Notes:
The database files (product_suggestions.db) won't be included in downloads, so any saved suggestions will be lost
Environment variables and secrets need to be reconfigured if you had any
The app is configured to run on 0.0.0.0:8080 which works great on Replit but locally you'll access it via localhost:8080
The project is self-contained with Flask as the only dependency, so it should run smoothly once you have Python and Flask installed.

