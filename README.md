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
![Screenshot 2024-11-14 002538](https://github.com/user-attachments/assets/1b2cfbe0-8ff8-4528-8d27-d7197917c20b)
![Screenshot 2024-11-14 002600](https://github.com/user-attachments/assets/526e8a79-415c-43d4-b7b1-b1606b995dd1)
![Screenshot 2024-11-14 002618](https://github.com/user-attachments/assets/6367a9c6-a6e2-48f7-bf74-b2f5a22c5ca9)
![Screenshot 2024-11-14 002631](https://github.com/user-attachments/assets/27a6cbdf-b13d-43c0-b330-04dd950f8129)
![Screenshot 2024-11-14 002656](https://github.com/user-attachments/assets/e2afe1e0-46a7-42d8-b6cc-e30474deaf6f)
![Screenshot 2024-11-14 002710](https://github.com/user-attachments/assets/f25277c0-153e-4c70-88de-8944b16424ca)
![Screenshot 2024-11-14 002722](https://github.com/user-attachments/assets/ffd662cb-5f90-443d-b09a-f11c09664c7a)
![Screenshot 2024-11-14 002739](https://github.com/user-attachments/assets/23083c65-4339-4869-a4f9-6e04c053221e)

## Result
This automation successfully captures periodic stock prices for each company, demonstrating efficient RPA usage for real-time data logging.

## Conclusion
The project showcases how RPA can streamline periodic data capture, with potential applications for business monitoring.

