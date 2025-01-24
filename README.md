# TkinterGUIProject
# Data Visualizer

## Description
The **Data Visualizer** is a Python-based GUI application built with `tkinter`. It allows users to upload a CSV dataset, select columns of interest, and generate various types of visualizations, including:

- Bar Charts
- Histograms
- Pie Charts
- Box Plots

This tool provides an interactive way to explore and visualize data.

---

## Features
1. **File Browser**: Upload CSV files for analysis.
2. **Column Selection**: Select specific columns for visualization.
3. **Chart Options**: Choose from Bar Chart, Histogram, Pie Chart, and Box Plot.
4. **Dynamic Plotting**: Automatically updates the plot when selections are made.

---

## Prerequisites
- Python 3.7 or higher
- Required libraries:
  - `tkinter` (built-in with Python)
  - `pandas`
  - `matplotlib`

---

## Installation
1. Clone the repository or download the source code.
   ```bash
   git clone https://github.com/your-username/data-visualizer.git
   cd data-visualizer
   ```
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib
   ```

---

## Usage
1. Run the application:
   ```bash
   python data_visualizer.py
   ```
2. Use the **Browse Files** button to select a CSV file.
3. Select the columns you want to visualize from the list.
4. Check the desired chart type(s).
5. The selected charts will be generated and displayed dynamically.

---

## File Structure
```
data-visualizer/
├── data_visualizer.py    # Main source code
├── README.md             # Documentation file
```

---

## Example
1. Select a CSV file with numeric columns.
2. Choose columns like `sales`, `profit`, etc., from the list.
3. Select "Bar Chart" or "Histogram".
4. The visualization will appear in the main window.

---

## Screenshots
- **Main Interface:**
  - Includes buttons for file selection and checkboxes for chart options.
- **Plot Area:**
  - Displays the selected chart in the GUI.

(Include screenshots here if applicable)

---

## Limitations
1. Pie Charts require numeric columns, and only the first row is used for plotting.
2. Bar Charts and Box Plots require numeric data.

---

## Future Enhancements
- Add support for other chart types like scatter plots.
- Enhance error handling and user feedback.
- Add styling options for charts.

---

## License
This project is licensed under the MIT License.

---

## Author
**Your Name**
- GitHub: [Your GitHub Profile](https://github.com/your-username)
- Email: your-email@example.com

