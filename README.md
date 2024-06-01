# I-FIT Macronutrients Tracker

## Overview

This project is a web application for tracking macronutrient intake throughout the day. Users can log their food intake, view a breakdown of their macronutrients consumption in a table and pie chart, and monitor their daily calorie intake using a progress bar.

## Features

- **Add Food Items:** Users can add food items from a dropdown menu.
- **View Intake:** Added items are displayed in a table with details on calories, carbs, protein, and fats.
- **Progress Bar:** A progress bar shows how many calories have been consumed out of the daily goal of 2000 Kcal.
- **Pie Chart:** A pie chart visually represents the proportion of carbs, protein, and fats consumed.
- **Delete Items:** Users can remove items from their daily intake, and the totals will update accordingly.
- **Total Macronutrients:** The total macronutrients consumed are displayed at the bottom of the table.

## Tech Stack

- **Backend:** Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (default with Django)

## Setup Instructions

1. **Download the ZIP File:**
    - Go to the [GitHub repository](https://github.com/yourusername/macro-nutrients-tracker).
    - Click on the "Code" button.
    - Select "Download ZIP".

2. **Extract the ZIP File:**
    - Extract the downloaded ZIP file to your desired location.

3. **Navigate to the Project Directory:**
    ```sh
    cd macro-nutrients-tracker
    ```

4. **Create and Activate Virtual Environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

5. **Install Dependencies:**
    ```sh
    pip install django
    ```

6. **Run Migrations:**
    ```sh
    python manage.py migrate
    ```

7. **Create Superuser:**
    ```sh
    python manage.py createsuperuser
    ```

8. **Run the Server:**
    ```sh
    python manage.py runserver
    ```

9. **Access the Application:**
    Open your web browser and navigate to `http://127.0.0.1:8000`.

## Usage

1. **Login/Register:**
    Register a new account or login with your credentials.

2. **Add Food Items:**
    Select a food item from the dropdown menu and add it to your daily intake.

3. **View and Manage Intake:**
    - The added items will appear in the table below.
    - The progress bar at the top will update to show the calories consumed.
    - The pie chart on the side will display the distribution of carbs, protein, and fats.
    - You can delete any item from the table to update the totals.
