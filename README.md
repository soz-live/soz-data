# SOZ-DATA


Data files for use in **SOZ**.

> Note:  
> - The **SOZ-FILES** repo must be loaded to use this functionality.  


## File Formats

These directories contain three types of data files for use in **SOZ**.

### DAT Files

These are **SOZ** objects stored line by line in a file format with the ability to reference preceeding objects using an ID.

They are imported into **SOZ** using the **I-SOZ** command.

> Note:  
> - As these files only store the arguments for each object they are an extremely compact file format.  
> - While being in text format - they are still easy to read and even edit in a text editor.  

### CSV Array Files

These are **SOZ** objects stored in CSV format with the ability to reference preceeding objects using an ID.

They are imported into **SOZ** using the **I-ARRAY** command.

> Note:  
> - The heading for CSV Array files is formatted with surrounding "  

### CSV Class Files

These are plain CSV files stored in a format for a specific Class, eg: SZCEShape-CPurlin.

They are imported into **SOZ** using the **I-CLASS** command.

> Note:  
> - The heading for CSV files is formatted with surrounding "  
