# Central Government Data Visualization Project

## Overview

This project involves scraping data from a central government website and visualizing the contents using Power BI. The visualizations include bar charts, pie charts, and other graphical representations to provide insights into the data.

## Project Structure

- `data_scraping/`: Contains Jupyter notebooks used for scraping data from the central government website.
- `data/`: Directory where scraped data is stored.
- `powerbi_visualizations/`: Contains Power BI files and screenshots of visualizations.
- `README.md`: Project overview and instructions.

## Getting Started


### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/central-government-data-visualization.git
    cd central-government-data-visualization
    ```

2. **Install the required Python libraries:**
    ```sh
    pip install requests beautifulsoup4 pandas
    ```

3. **Open Jupyter Notebook:**
    ```sh
    jupyter notebook
    ```

4. **Navigate to the `data_scraping` directory and run the notebooks to scrape data.**

5. **Open Power BI Desktop and load the data from the `data` directory.**

## Usage

1. **Scraping Data:**
   - Open the Jupyter notebooks in the `data_scraping` directory.
   - Run the notebooks to scrape data from the central government website.
   - The scraped data will be saved in the `data` directory.

2. **Visualizing Data:**
   - Open Power BI Desktop.
   - Load the data from the `data` directory.
   - Use the provided Power BI files in the `powerbi_visualizations` directory or create your own visualizations.

## Visualizations

- **Bar Charts:** Display distribution and comparison of categories.
- **Pie Charts:** Show proportions of different categories.
- **Additional Charts:** Other charts as necessary to provide insights.

## Project Files

- `data_scraping/`
  - `scrape_data.ipynb`: Jupyter notebook for scraping data.
- `data/`
  - `scraped_data.csv`: Scraped data file.
- `powerbi_visualizations/`
  - `visualizations.pbix`: Power BI project file.
  - `screenshots/`: Directory containing screenshots of the visualizations.
- `README.md`: This file.




## Acknowledgements

- Election Commision website for providing the data.


