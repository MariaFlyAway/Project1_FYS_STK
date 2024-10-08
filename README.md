# Project 1 FYS-STK3155

## Description
This project aims to find the optimal model for fitting topographical data for Glittertind, Lom in Norway.

## Project Structure
The project is organized into several directories.

### `Report/`
Contains the report written for this project in pdf-format

#### `Regression and Resampling Methods Topographical Analysis with Ordinary Least Squares, Ridge and Lasso Regression`
The report

#### `ChatGPT_conversations`
Contains links to ChatGPT conversations

### `Code/`
Contains all code used in the project

#### `Additional_plots/`
Contains some additional plots not present in the report.

#### `Exercises/`
Contains notebooks for solution of all exercises except 1d and 1g.

#### `Latex/`
Contains .tex-files for exercise 1d.

- **`Images/`**:
  - Contains all figures included in the report
 
#### `Topographical_dataset`

Contains all files related to exercise 1g. 
- `Fitting_topographical_data`: fitting of data with OLS, Ridge and Lasso with cross validation and bootstrap.
- `gridsearch`: implements gridsearch for finding optimal parameters for OLS, Ridge and Lasso as well as the optimal model for higher degree fits.
- `modyfying_dataset`: Reads in the topographical data, displays it and writes it to `topographical_data.npy`.
- `report_plots`: contains code for making visualizations for the report.

## License

The data used in this project is licensed under the Creative Commons Attribution 4.0 International Licence - see the [LICENSE]: Topographical_dataset/_Lisens_License.txt for details.

## Contributors
- **Jonas Jørgensen Telle**
- **Marius Torsheim**
- **Maria Klüwer Øvrebø**
