# Dev-Sec-Ops
Dev-Sec-Ops Demo/Assignment
 

This repository contains code that demonstrates Dev-Sec-Ops using a FastAPI the application which predicts the flower class using the IRIS dataset (https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)

codecoverage:
https://app.codecov.io/gh/PGCSEDS-IIITH/devsecops-iris/

 

Running Instructions
Create a fork of the repo using the fork button.
Clone your fork using git clone https://www.github.com/<your-username>/mlops-iris.git
Install dependencies using pip3 install -r requirements.txt
Run application using python3 main.py
Run tests using pytest
 

CI/CD
unittest: Run the python unit tests using pytest
codecoverage: Analyze code quality using codecov and upload results
container-security: Scan docker image using anchore and upload SARIF report artifact
upload_zip: Package code and upload as artifact
 

Assignment Tasks
Fix badge to show coverage for your repo. (hint: find correct link for badge from codecov.io)
Add OS to matrix strategy along with PYTHON to test with different operating systems like ubuntu-latest, windows-latest etc.
Improve code coverage and bring it above 95%
Make a visualisation for sarif report using any tool. upload screenshot, image, html or pdf. Add it to the reports/ folder.
 

Submission
Please upload the link to the GitHub repository as a comment on Olympus along with a .txt file
 

Scoring guide (Rubric) - Week 14: Rubric
Criteria	Points
Fix badge to show coverage for your repo. (hint: find correct link for badge from codecov.io)
10
Add OS to matrix strategy along with PYTHON to test with different operating systems like ubuntu-latest, windows-latest etc.
10
Improve code coverage and bring it above 95%
10
Make a visualisation for sarif report using any tool. upload screenshot, image, html or pdf. Add it to the reports/ folder.
10
Points	40
