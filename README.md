Daily Expense Categorizer (Machine Learning Project)

This project uses machine learning to automatically classify expense descriptions into categories such as food, transport, shopping, fitness, health, and utilities.
It is designed as a simple real-world example of text classification using Python, scikit-learn, and TF-IDF vectorization.

⸻

Features
	•	Classifies expense text into real-life categories
	•	Uses a Naive Bayes classifier
	•	Customizable dataset (expenses.csv)
	•	Easy to extend for personal finance apps or automation tools

⸻

Requirements

Install required packages:

pip install pandas scikit-learn


⸻

File Structure

project/
│
├── daily_expense_classifier.py
├── expenses.csv
└── README.md


⸻

Usage
	1.	Save the dataset as expenses.csv in the same directory:

description,category
uber ride to office,transport
grocery store purchase,food
monthly netflix subscription,entertainment
electricity bill payment,utilities
mcdonalds burger meal,food
...

	2.	Run the Python script:

python daily_expense_classifier.py

	3.	The program will:
	•	Load and vectorize the dataset
	•	Train a Naive Bayes classifier
	•	Print accuracy
	•	Predict categories for example expenses

⸻

How to Train With Your Own Data

Replace expenses.csv with your real bank or spending data.
Required columns:

description,category
coffee at starbucks,food
bus ticket,transport
...

Ensure the CSV uses lowercase category names for consistency.

⸻

License (MIT License)

MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


⸻

Optional Enhancements

You can expand this project with:
	•	A Streamlit web interface
	•	Automatic learning from new user inputs
	•	Monthly spending charts
	•	Integration with bank statement downloads
	•	Deployment as a mobile or web app
