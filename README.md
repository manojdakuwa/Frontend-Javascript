This repository contains the code for a chemical inventory table application. The table allows users to:

Add, delete, move rows up an down and save row.
Sort columns in ascending and descending order.
Edit individual cells by clicking on the corresponding checkboxes.
Save changes to the data.

Note: I am not using any SQL to save the data. instead i am appending and dlsicing the data for save and delete method.

Dependencies

Bootstrap 5.3.2 (for styling and responsive design)
Installation

Clone this repository or download the ZIP file.
Install Bootstrap using a package manager like npm or yarn or add cdn:
Bash
npm install bootstrap@5.3.2

Include the Bootstrap CSS and JavaScript files in your HTML file (refer to the index.html file for an example).
Usage

Open the index.html file in a web browser.
You should see the chemical inventory table with the toolbar buttons and editable fields.
Click on the "Add Row" button to add a new row.
Select rows using the checkboxes.
Click on the "Move Row Up" or "Move Row Down" buttons to reorder the selected rows.
Click on the "Delete Row" button to delete the selected rows.
Edit the values in the editable cells.
Click on the "Save Data" button to save the changes (I am not using any SQL to save the data. instead i am appending and dlsicing the data for save and delete method).
Customization

You can customize the table's appearance using CSS.
Modify the chemicalData.js file to add or remove chemical entries.
Implement your own data saving logic in the saveButton event listener.
Add more features like filtering, searching, or exporting data as needed.
Additional Notes

Ensure you have the necessary dependencies installed and configured correctly.
Adjust the code to match your specific requirements and data structure.
Test the application thoroughly to ensure it works as expected.

#Install this app.
Once you run this app, you will be able to dpwnload this as PWA. and can perform the same functionality.
