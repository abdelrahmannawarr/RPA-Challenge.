# RPA Challenge – UiPath Project

## Overview
This project automates the completion of the [RPA Challenge](https://rpachallenge.com/) using UiPath. The challenge involves filling out a web form with dynamically changing field positions using data from an Excel file.

## Objective
Demonstrate UiPath's capability to handle:
- Dynamic web elements
- Data-driven automation
- Reliable input submission in a loop

## Features
- Reads input data from an Excel file
- Detects and fills dynamic input fields on the form
- Clicks submit and processes all rows
- Measures and logs completion time and accuracy

## Technologies Used
- UiPath Studio
- Excel Activities
- Web Automation
- Dynamic Selectors
- Looping and Exception Handling

## How It Works
1. Input data is loaded from an Excel sheet (First Name, Last Name, Company, etc.).
2. For each row, the bot identifies the form fields using dynamic selectors.
3. The form is filled and submitted for each row until all entries are completed.

## Prerequisites
- UiPath Studio installed
- Internet connection
- Excel file with input data (placed in the `Input` folder)

## Output
- Completed form submissions on the RPA Challenge site
- Execution logs (if enabled)
- Optionally, summary of completion stats in the console or Excel

## How to Use
1. Clone or download the project.
2. Place the input Excel file in the `/Input` folder.
3. Open the solution in UiPath Studio.
4. Run the project and monitor browser actions.

## Author
Created as part of RPA training to showcase dynamic web automation using UiPath.

---

You can extend this project by capturing success messages or measuring performance.
