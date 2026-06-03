# vocational_training_centre_analytics
The analysis involved loading, cleaning, and merging a multi-sheet dataset to conduct exploratory data analysis, resulting in static and interactive dashboards. These dashboards provided insights into student performance, gender gaps, and program effectiveness, leading to actionable recommendations and identified limitations.
### The Dataset Used
For this project, I utilized the **Vocational Training Centre dataset (ds3_training_centre.xlsx)**. This dataset provides information across three sheets: `trainees`, `enrollments`, and `scores`, allowing for a comprehensive analysis of trainee performance and program engagement.
Tools and libraries used: ("Python, Pandas")
This interactive dashboard provides a dynamic and comprehensive overview of the training centre's performance, allowing for deeper exploration of key metrics.

**1. Overall Pass/Fail Distribution (Top-Left):**
- The donut chart visually represents the high success rate (95% passed) and the small proportion of students who failed (5%). This indicates a generally effective training program.
- **Interactivity:** Hovering over the segments reveals exact counts and percentages, making it easy to see the absolute numbers behind the proportions.

**2. Average Score by Course (Top-Right):**
- This horizontal bar chart ranks courses by their average overall score. 'Graphic Design' and 'Data Analysis' remain the top performers, while 'Digital Marketing' and 'Web Development' are at the lower end.
- **Interactivity:** Bars can be hovered over to see the precise average score for each course, aiding in quick comparative analysis.

**3. Average Score by Gender (Bottom-Left):**
- The bar chart compares the average overall scores between male and female students. Similar to the static dashboard, it shows male students having a slightly higher average score than female students.
- **Interactivity:** Tooltips provide exact average scores for each gender.
### How to Run This Project

To run this data analysis project, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
    (Or, if you prefer, download the `.zip` file directly from GitHub.)

2.  **Open in Google Colab:** Upload the `vocational_training_centre_analytics.ipynb` file to Google Colab.

3.  **Install Dependencies:** Ensure all required libraries are installed by running the first code cell in the notebook:
    ```python
    !pip install plotly openpyxl -q
    ```

4.  **Execute the Notebook:** Run all cells in the notebook from top to bottom. This will load the data, perform the analysis, generate visualizations, and create the dashboards.
