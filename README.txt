Overview:

Extracted invoice data from 4 e-commerce PDF files (2 from Amazon, 2 from Flipkart) using Python scripts. It uses only open-source Python libraries, no third-party APIs.

Folder Structure:  

Input Folder: Stores the original PDF invoices
Output Folder: Stores the generated Excel files
Code Folder: Contains Python scripts

Tech Stack:  

Python  
pandas  
openpyxl

Process:  

Use pre-extracted OCR data from the four PDF invoices.  
Apply custom Python logic to extract key details like Order ID, Product Description, Quantity, Price, Tax, and Totals.  
Save each invoice’s data into separate Excel files in the Output folder.  
Merge the Excel files into one final Excel file (Merged_Accounting_Orders.xlsx) with only accounting columns, stored in the Output folder.

Submitted by: Shohrab Haque Shahil
