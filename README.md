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

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/yourusername/macro-nutrients-tracker.git
    cd macro-nutrients-tracker
    ```

2. **Create and Activate Virtual Environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install Dependencies:**
    ```sh
    pip install django
    ```

4. **Run Migrations:**
    ```sh
    python manage.py migrate
    ```

5. **Create Superuser:**
    ```sh
    python manage.py createsuperuser
    ```

6. **Run the Server:**
    ```sh
    python manage.py runserver
    ```

7. **Access the Application:**
    Open your web browser and navigate to `http://127.0.0.1:8000`.

## Usage

1. **Run the project:**
    Access the django application

2. **Add Food Items:**
    Select a food item from the dropdown menu and add it to your daily intake.

3. **View and Manage Intake:**
    - The added items will appear in the table below.
    - The progress bar at the top will update to show the calories consumed.
    - The pie chart on the side will display the distribution of carbs, protein, and fats.
    - You can delete any item from the table to update the totals.
