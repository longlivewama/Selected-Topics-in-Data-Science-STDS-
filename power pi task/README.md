# Netflix Content Strategy Analysis Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)

![Netflix Dashboard](Dashborad.png)

## Project Overview

This project is a comprehensive data visualization dashboard built using **Tableau**. It analyzes the Netflix dataset to understand content trends, genre popularity, and the distribution of Movies vs. TV Shows across different countries and time periods.

The goal of this analysis is to provide insights into Netflix's content strategy and library evolution.

## Files in this Repository

| File Name | Description |
| :--- | :--- |
| **`Netflix.twb`** | The Tableau Workbook file containing the visualizations and dashboard layout. |
| **`netflix_titles.csv`** | The raw dataset used for this analysis. |
| **`Dashborad.png`** | A snapshot of the final dashboard visualization. |

## Key Insights & Features

The dashboard provides interactive visualizations covering the following metrics:

* **Content Split:** Analysis of the ratio between Movies and TV Shows.
* **Geographical Distribution:** A map visualization showing where content is produced globally.
* **Rating Analysis:** Breakdown of content by maturity ratings (e.g., TV-MA, PG-13).
* **Release Trends:** A timeline showing the volume of content added over the years.
* **Genre Analysis:** Identification of the most popular genres and categories.

## Tools Used

* **Tableau Desktop:** Used for data connection, cleaning, calculation, and visualization.
* **Microsoft Excel / CSV:** Used for initial data inspection.

## How to Run This Project

Since the workbook file provided is a `.twb` (Tableau Workbook) and not a `.twbx` (Packaged Workbook), it relies on the external CSV file.

1.  **Clone the repository** or download the ZIP file.
2.  Ensure both `Netflix.twb` and `netflix_titles.csv` are in the **same folder** on your computer.
3.  Ensure the image `Dashborad.png` is also in the folder to view it in the README locally.
4.  Open `Netflix.twb` using **Tableau Desktop** or **Tableau Public**.
5.  *Note: If Tableau asks to locate the data source, navigate to the folder where you saved `netflix_titles.csv` and select it.*

## Dataset Details

* **Source:** Netflix Movies and TV Shows Dataset.
* **Columns:**
    * `show_id`, `type`, `title`
    * `director`, `cast`, `country`
    * `date_added`, `release_year`
    * `rating`, `duration`, `listed_in`, `description`

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](issues).

## Author

**[Ahmed fahim]**
* [LinkedIn Profile](https://www.linkedin.com/in/longlivewama)

