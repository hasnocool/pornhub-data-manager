# Pornhub-Data-Manager

## Overview
Pornhub-Data-Manager is a specialized data management application designed for interacting with data scraped from Pornhub. Built using PyQt6, it offers a user-friendly interface for organizing, analyzing, and enhancing your scraped Pornhub data.

## Features
- Thumbnail Downloading: Automatically download thumbnails for videos, providing a visual representation alongside the data.
- Duplicate Removal: Identify and remove duplicate entries based on video URLs, keeping your data clean and organized.
- Data Filtering: Filter data based on various criteria, such as video duration, ratings, or view count, for focused analysis.
- Data Refresh: Refresh the displayed data by reloading it from the CSV file, ensuring you work with the latest information.
- Sorting and Column Resizing: Sort data in columns and resize columns for better visibility and organization.

## Getting Started
To start using Pornhub-Data-Manager, follow these simple steps:

1. Clone or download the repository:

`git clone https://github.com/your-username/pornhub-data-manager.git`

2. Navigate to the project directory:

`cd pornhub-data-manager`

3. Install the required Python packages (if not already installed):

`pip install PyQt6 requests`

4. Run the application:

`python main.py`

5. The Pornhub-Data-Manager window will open, providing you with tools to manage and analyze your scraped Pornhub data.

## Usage
- Load Data: Click the "Load Data" button to load your scraped data from the CSV file into the table view.
- Download Thumbnails: Click the "Download Thumbnails" button to fetch and save thumbnails for the loaded videos.
- Remove Duplicates: Utilize the "Remove Duplicates" button to identify and remove duplicate entries, ensuring a streamlined dataset.
- Filter Data: Use the "Filter" field to narrow down your data based on specific criteria, such as duration, ratings, or views.
- Refresh Data: Click the "Refresh" button to update the displayed data with the latest information from the CSV file.
- Sorting and Column Resizing: Sort data by clicking column headers and resize columns for improved readability.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
