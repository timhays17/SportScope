# Intro 
We have two floders, The Initial Project and football_analyzer Final Porject. 

For The Initial Project, it includes the models that we tried to fix our problem but we failed. Inside this folder we have two plan. To be more specific, they are Plan A and Plan B. 

For Plan A, we tried YOLO model, Segment Anything 2(Sorry that I cannot find the original file right now), and stablization method. 

For Plan B, Tim used the manuel attempt method.

For the football_analyzer Final Porject, it is our final outcome. You can try it out by following the instruction below. 

# 🏈 Football Video Analyzer
A simple web app that lets you upload an American football video and get AI analysis (Offense & Defense) using Google Gemini.


# ⭐ Features
•	Upload and preview football video clips

•	Coach Mode:the web offers three different coach personalities 

•	AI analyzes offense and defense separately

•	Simple progress bar and playback speed

•	History of previous analyses (local only)

•	Export the analysis into a excel file 


# 🔐 Get a Gemini API Key
1.	Go to https://aistudio.google.com/app/apikey
2.	Click Create API Key
3.	Copy the key (looks like AIzaSy...)
4.	Paste the key into the app’s API key input box


# 🚀 How to Run
1.	Install dependencies:
2.	pip install flask google-genai pydantic
3.	Start the server:
4.	python app.py
5.	Open your browser:
6.	http://127.0.0.1:5000


# 🧠 How to Use
1.	Paste your Gemini API Key
2.	Upload a football video (MP4)
3.	Select the coach mode
4.	Click Analyze
5.	View Offense/Defense results
6.	Switch between results or select from History
7.	click the export button and you could export all the info into an excel file

# Contribution 
Football analyzer files (app.py,style.css & index.html) - Zhiyuan Li

The Manuel Attempt.ipynb - Timothy Hays & Zhiyuan Li

Data Collection & Manually Labeled Clips - Timothy hays

Yolo for Football.ipynb - Zhiyuan Li

Stabalization.ipynb - Zhiyuan Li

README - Zhiyuan Li & Timothy Hays

Report -Timothy Hays, Peixin Yang， Zhiyuan Li
