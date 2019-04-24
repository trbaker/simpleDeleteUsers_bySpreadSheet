# simpleDeleteUsers_bySpreadSheet
Python script to delete AGO users (not content or groups) as listed in a spreadsheet

To use:
1. Add the ipynb file to your Jupyter Notebookss. 
2. Unzip and place data.zip (the data folder) in the same folder as the ipynm file. The data folder becomes a subfolder of the ipynb file. 
3. Add your admin user/pw to the admin CSV in the data folder.
4. Update the user CSV with a list of NEVER LOGGED IN users.
5. Update the AGO org url in the ipynb file (cell 2, line 3)

There is no undo on a "delete script".  Test the script in development organization before production. Use at your own risk. 

Run script.
