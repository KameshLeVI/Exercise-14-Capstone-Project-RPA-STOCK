# Exercise-14-Capstone-Project-RPA-STOCK
**Author**: Kamesh D

## Aim
Automate the capture of stock prices from the RPA Challenge Stock Market page and log them in an Excel file using UiPath.

## Components Required
- **Software**: UiPath Studio
- **Hardware**: PC with internet access
- **Additional Tools**: Microsoft Excel

## Procedure

1. **Prepare Excel Sheet**: List the company names and add columns `Value 1` and `Value 2`.
2. **Set Up UiPath Workflow**:
   - **Read Excel Data**: Use the `Read Range` activity to load the data.
   - **Open Browser**: Use `Open Browser` to navigate to the RPA Stock Market page.
   - **Loop for Each Company**:
     - Select each company using `Select Item` and capture values at 3-second intervals.
   - **Log Values in Excel**: Write back the updated data table to the Excel file.
   - **Close Browser**: Use `Close Application` to finish.
## Uipath procedure:
## Result
This automation successfully captures periodic stock prices for each company, demonstrating efficient RPA usage for real-time data logging.

## Conclusion
The project showcases how RPA can streamline periodic data capture, with potential applications for business monitoring.

