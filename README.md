# SOZ-DATA


Data files for use in **SOZ-LIVE**.

> Note:  
> - The **SOZ-FILES** repo must be loaded to use this functionality.  


## File Formats

These directories contain three types of data files for use in **SOZ-LIVE**.

### SOZFiles - *.DAT 

These are **SOZ** objects stored line by line in a file format with the ability to reference preceeding objects using an ID.

They are imported into **SOZ-LIVE** using the **I-SOZ** command.

> Note:  
> - As these files only store the arguments for each object they are an extremely compact file format.  
> - While being in text format - they are still easy to read and even edit in a text editor.  

### CSVArray Files *.CSV

These are **SOZ** objects stored in CSV format with the ability to reference preceeding objects using an ID.

They are imported into **SOZ-LIVE** using the **I-ARRAY** command.

> Note:  
> - The headings for CSV Array files is formatted with surrounding "  

### Class Files *.CSV

These are plain CSV files stored in a format for a specific Class, eg: SZCEShape-CPurlin.

They are imported into **SOZ-LIVE** using the **I-CLASS** command.

> Note:  
> - The headings for CSV files is formatted with surrounding "  
