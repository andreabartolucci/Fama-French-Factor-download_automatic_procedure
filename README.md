# Fama-French-Factor-download_automatic_procedure
The Python script retrieves the Fama-French factors data from the online data library provided by Professor Kenneth French R. French on his personal website https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/Data_Library/det_mom_factor.html
The data are store on hidden repositories that can be access from an hyperlink on the webpage, the download starts when the user click on the link. The script automates this procedure that otherwise must be performed manually.

The script uses libraries, including urllib, zipfile, and pandas, along with specific modules from Pandas.
The script download the zip files, extracts the contents of the zip file using the extractall method from the zipfile.ZipFile class and read the resulting csv files using Pandas.
