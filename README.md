## Flask Cafe Database Application

This project is a Flask web application that allows users to add and view cafes along with details such as location, opening hours, coffee quality, wifi strength, and power socket availability.

This is an updated version of the previous implementation, where proper form submission handling using GET and POST methods has been implemented to ensure reliable data processing.

The application uses Flask-WTF for form handling and validation, and stores data in a CSV file as a lightweight database.

This project was built as part of the #90DaysOfCode challenge to strengthen backend concepts such as form handling, validation, routing, and file-based data storage.

---

## Technologies Used

Python  
Flask  
Flask-WTF  
WTForms  
Bootstrap-Flask  
CSV (File Handling)  
HTML5  
Jinja2 Templating  

---

## Key Concepts Demonstrated

Handling GET and POST requests correctly in Flask

Form validation using Flask-WTF and WTForms

Storing structured data in CSV files

Reading and rendering CSV data dynamically

Using SelectField for structured input

Redirecting users after form submission

Template inheritance and dynamic rendering

---

## Project Structure

```
project/
│
├── main.py
├── cafe-data.csv
├── requirements.txt
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── add.html
│   └── cafes.html
│
├── static/
│   └── css/
│       └── styles.css
```

---

## Application Workflow

1. User opens the homepage
2. Navigates to the add cafe page
3. Submits the form with cafe details
4. Flask validates the form using WTForms
5. Data is appended to a CSV file
6. User is redirected to the cafes page
7. All stored cafes are displayed dynamically

---

## Installation

Install dependencies

```
pip install -r requirements.txt
```

---

## Run

```
python main.py
```

Open in browser:

```
http://127.0.0.1:5000
```

---

## Why This Project Matters

This project demonstrates how backend systems handle user input, validate data, and store structured records without a database.

It reflects real-world patterns such as:

Form submission workflows  
Data persistence  
Dynamic content rendering  
Request handling (GET vs POST)  

---

## Author

Faiz Hasan  
Python Automation & Backend Developer
