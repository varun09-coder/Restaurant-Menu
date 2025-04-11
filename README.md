# Restaurant Menu Recommender System

# Overview

This project implements a Restaurant Menu Recommender System that helps users select dishes from a menu while adhering to a specified calorie limit and maximizing their potential taste satisfaction. The system utilizes the 0/1 Knapsack algorithm for optimal dish selection and provides a user-friendly graphical interface (GUI) built with Python's Tkinter library.

## Features

* **Menu Item Input:** Easily add restaurant menu items with their names, calorie counts, and user-defined taste ratings.
* **Current Menu Display:** View a list of all added menu items within the application.
* **Menu Item Removal:** Remove items from the current menu if needed.
* **Calorie Limit Specification:** Set a maximum calorie limit for your desired meal.
* **Intelligent Recommendation:** The system uses the 0/1 Knapsack algorithm to find the optimal set of dishes that fit within the calorie limit and have the highest total taste rating.
* **Recommendation Output:** View the names of the recommended dishes.
* **Total Taste Rating:** See the total cumulative taste rating for the recommended meal.
* **User-Friendly GUI:** An intuitive graphical interface built with Tkinter for easy interaction.
* **Visually Appealing Theme:** A custom color theme is applied to enhance the user experience.

## Technologies Used

* **Python 3.x:** The primary programming language.
* **Tkinter (`tkinter` and `tkinter.ttk`):** Python's standard GUI library for creating the graphical interface with themed widgets.

## Usage

1.  **Run the `main.py` file:**
    ```bash
    python main.py
    ```
    This will launch the Restaurant Menu Recommender application.

2.  **Adding Menu Items:**
    * In the "Add Menu Item" section, enter the name of the dish, its calorie count, and your personal taste rating (a higher number indicates better taste).
    * Click the "Add Item to Menu" button to add the dish to the current menu.

3.  **Viewing and Removing Menu Items:**
    * The "Current Menu" listbox displays all the added dishes.
    * To remove a dish, select it in the listbox and click the "Remove Selected Item" button.

4.  **Getting Recommendations:**
    * In the "Calorie Limit" section, enter your desired maximum calorie intake.
    * Click the "Get Recommendations" button.

5.  **Viewing Recommendations:**
    * The "Recommendations" listbox will display the names of the dishes the system recommends.
    * The "Total Taste Rating" label will show the combined taste rating of the recommended dishes.

## Project Structure
