# Google Search Analysis

## Description

This project provides an analysis of Google search trends for the keyword "Cloud Computing" using the pytrends library. It fetches data on search interest over time, by region, related queries, and keyword suggestions, with visualizations for better insights.

## Features

- **Interest Over Time**: Retrieves search interest data for the last 12 months and for specific timeframes (e.g., January 2024).
- **Interest by Region**: Analyzes search interest across different regions and visualizes the top 10 regions using a bar chart.
- **Related Queries**: Fetches and displays related search queries for the keyword.
- **Keyword Suggestions**: Provides suggestions for similar keywords based on the input.

## Installation

1. Ensure you have Python installed (version 3.6 or higher recommended).
2. Install the required libraries using pip:
   ```
   pip install pytrends pandas matplotlib
   ```
3. Open the `Google_search_Analysis.ipynb` notebook in Jupyter Notebook or JupyterLab.

## Usage

1. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```
2. Open `Google_search_Analysis.ipynb`.
3. Run the cells sequentially to execute the analysis.
   - The notebook includes code to build payloads, fetch data, sort and display results, and generate plots.
   - Note: The script includes a `time.sleep(5)` to handle rate limits imposed by Google Trends.

## Dependencies

- `pytrends`: For accessing Google Trends data.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating visualizations.
- `time`: Built-in Python module for delays.

## License

This project is licensed under the MIT License. See the LICENSE file for more details (if applicable).

## Contributing

Feel free to fork the repository and submit pull requests for improvements or additional features.

## Contact

For questions or issues, please open an issue in the repository.
