# return_all_modified_files_after_date

## return_all_modified_files_in_dir_after_date.py
- purpose: to determine which files in a directory have been modified after a given date
-- searches the directory structure recursively
- returns a pandas DataFrame object of all files modified after a given date.
- the DataFrame can be saved as an Excel file if desired
- To use:
1. cd into directory which you would like to search
2. in command line:
[ python mod_files_new.py "Oct 31 2019" "C:\Users\John\directory_to_search" 1 ]
3. strings must be surrounded by double quotes
4. optional argument 1 or 0
5. 1 will save returned DataFrame as an Excel (.xlsx) file in the directory searched
6. 0 or nothing will not save as an Excel file
