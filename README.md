# Delhi Metro Network Analysis and Visualization

This project provides a comprehensive analysis of the Delhi Metro network using Python. It leverages libraries like `pandas` for data manipulation, and `Plotly` and `Folium` for creating insightful, interactive visualizations. The analysis explores the network's growth over time, characteristics of its various lines, and the connectivity provided by interchange stations.

## 📈 Features & Analysis

The Jupyter Notebook (`Metro1.ipynb`) performs the following analyses:

1.  **Geospatial Mapping**:
    * An interactive map of the entire Delhi Metro network is generated using `folium`.
    * Each station is marked with a pin, color-coded by its respective metro line.
    * Hovering over a station shows its name and line for easy identification.

2.  **Temporal Growth Analysis**:
    * **Annual Growth**: A bar chart visualizes the number of new metro stations opened each year, showing the expansion phases of the network.
    * **Cumulative Growth**: A line chart illustrates the cumulative total number of stations over time, highlighting the network's continuous growth since its inception.

3.  **Metro Line Characteristics**:
    * A detailed breakdown of each metro line, analyzing:
        * Total number of stations.
        * Total line length (in km).
        * Average distance between stations.
    * This is presented in both a summary table and a comparative bar chart.

4.  **Station Infrastructure Analysis**:
    * A bar chart shows the distribution of station layouts (e.g., Elevated, Underground, At-Grade), revealing the primary construction types across the network.

5.  **Interchange Connectivity Analysis**:
    * Identifies all interchange stations within the network.
    * A bar chart displays the number of interchange points on each line.
    * An interactive scatter plot provides a detailed view of each interchange station, its primary line, and the other lines it connects to.

## 📂 Dataset

The analysis is based on the `Delhi Metro Network new.csv` dataset. The key columns used in the analysis are:
* `Station Name`: The name of the metro station.
* `Line`: The metro line the station belongs to (e.g., Red line, Blue line).
* `Opening Date`: The date the station was opened to the public.
* `Station Layout`: The type of station (e.g., Elevated, Underground).
* `Latitude`: The geographical latitude of the station.
* `Longitude`: The geographical longitude of the station.

## 🛠️ Technologies Used

* **Python**: The core programming language.
* **pandas**: For data loading, cleaning, and manipulation.
* **plotly**: For creating interactive charts and graphs.
* **folium**: For generating the interactive geographical map.
* **Jupyter Notebook**: For organizing and running the analysis code.

## 🚀 How to Run

To run this project on your local machine, follow these steps:

1.  **Clone the repository or download the files.**

2.  **Ensure you have Python installed.**

3.  **Install the required libraries:**
    ```bash
    pip install pandas plotly folium
    ```

4.  **Place the dataset `Delhi Metro Network new.csv` in the same directory as the notebook.**

5.  **Launch Jupyter Notebook and open `Metro1.ipynb`:**
    ```bash
    jupyter notebook Metro1.ipynb
    ```

6.  **Run the cells in the notebook.** The `folium` map will be saved as `delhi_metro_map.html` in the project directory and will automatically open in your web browser. The `plotly` visualizations will be displayed directly within the notebook.

## 📁 File Structure
.
├── Delhi Metro Network new.csv   # The dataset file
├── Metro1.ipynb                  # The main Jupyter Notebook with all the analysis
└── README.md                     # This README file
