Web-Application mimicking Google sheets
Introduction

This project is a web-based spreadsheet application that enables users to input data, perform arithmetic operations, and generate charts for data visualization. It features a user-friendly interface with modern styling and dynamic functionalities similar to Google Sheets.

Live Demo
 https://rachu9.github.io/Web-Application-Mimicking-Google-Sheets/

Features

1. Spreadsheet Functionalities

Dynamic Grid: Initializes with 10 rows and 5 columns by default.

Editable Cells: Users can click and modify cell contents.

Row & Column Management: Add or remove rows and columns dynamically.

Cell Selection: Highlights selected cells for operations.

2. Formula Support

Basic Arithmetic: Users can enter formulas like =SUM(A1:A3), =AVG(A1:A3), =MIN(A1:A3), and =MAX(A1:A3).

Dynamic Computation: Formula results update in real time based on cell data changes.

3. Chart Generation

Supports Bar Chart, Line Chart, and Pie Chart.

Automatically fetches data from spreadsheet cells for visualization.

Assigns colors dynamically for better readability.

4. Data Exporting

Users can download spreadsheet data as an Excel file using SheetJS.

Ensures proper structuring for compatibility with Excel.

Technologies Used

HTML5 & CSS: Page structuring and styling.

JavaScript (Vanilla JS): Core logic for spreadsheet functionality.

Bulma CSS: Responsive UI framework.

Chart.js: For interactive data visualization.

SheetJS (xlsx.js): Export functionality for downloading spreadsheets as Excel files.

How to Use

Enter Data: Click any cell to input data.

Use Formulas: Enter a formula in the formula bar (e.g., =SUM(A1:A3)).

Generate Charts: Select a chart type to visualize data.

Export Spreadsheet: Click the export button to download data as an Excel file.

Future Enhancements

Support for multiplication, division, and conditional logic in formulas.

Undo/Redo functionality for error correction.

CSV Import/Export for handling external data.

Enhanced chart customization options (titles, labels, colors).

License

This project is open-source and licensed under the MIT License.

Author

Developed by Rachu. Check out more projects on GitHub.
