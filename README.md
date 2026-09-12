# Phishing Website Detection - Final Project

## Files
- `phishing_project.ipynb` - all the code
- `report.docx` - the written report (some spots say "fill in", fill those after you run the notebook)
- `requirements.txt` - packages needed

## How to run
```
pip install -r requirements.txt
```
Then open `phishing_project.ipynb`, restart the kernel, run all cells top to bottom.
Needs internet the first time (downloads the dataset).

## Dataset
PhishingWebsites dataset from OpenML (id 4534). 30 url/site structure features, target column Result (-1 = phishing, 1 = legit).

## Note
random_state = 42 used everywhere so results stay the same each run.
