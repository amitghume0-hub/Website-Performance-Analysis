

# 📈 Website Performance Analysis (Web Analytics & Optimization)

## Project Overview

This project is an **Exploratory Data Analysis (EDA)** focused on interpreting raw website performance metrics (likely from Google Analytics) to drive business optimization. The primary goal is to understand user behavior, traffic trends over time, and the effectiveness of various marketing channels to improve engagement and conversion.

## Key Analysis Goals

This analysis was structured to answer the following critical business questions:

1.  What patterns or trends can be observed in website sessions and users over time?
2.  Which marketing channel brought the highest number of users to the website?
3.  Which channel has the highest average engagement time, and what does this tell us about content effectiveness?
4.  How does the engagement rate vary across different traffic channels?
5.  Which channels are driving more engaged sessions?
6.  At what hours of the day does each channel drive the most traffic?
7.  Is there any correlation between high traffic (sessions) and high engagement rate over time?

---

## Technical Details

### Technologies Used

* **Language:** Python
* **Libraries:**
    * `Pandas` for robust data cleaning and manipulation.
    * `NumPy` for numerical operations.
    * `Matplotlib` & `Seaborn` for statistical data visualization.

### Data Preparation & Wrangling

The initial data required significant cleaning to be analysis-ready, demonstrating key data engineering skills:

1.  **Header Correction:** The initial file had incorrect headers; the second row was promoted to be the proper column names.
2.  **Column Renaming:** Renamed complex column titles for clarity and ease of use (e.g., handling the default channel group column).
3.  **Data Type Conversion:** Converted key columns from generic `object` (string) type to appropriate numerical types for calculation.
4.  **Date/Time Processing:** Converted the raw `DateHour` integer string (YYYYMMDDHH) into a proper Python `datetime` object and extracted the `Hour` feature for time-series analysis.

## How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone <Your-Repository-URL>
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the analysis:**
    The analysis is contained within the **`Website_Performance_Analysis.ipynb`** Jupyter Notebook. Open and run the cells sequentially to reproduce the analysis and visualizations.
    ```bash
    jupyter notebook Website_Performance_Analysis.ipynb
    ```

## Author

- **Amit Ghume**
- **Email:** amitghume0@gmail.com
- **Connect on LinkedIn:** [linkedin.com/in/amit-ghume-7b8b13375](https://www.linkedin.com/in/amit-ghume-7b8b13375)
