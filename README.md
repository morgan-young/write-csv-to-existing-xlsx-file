# write-csv-to-existing-xlsx-file
A python utility for writing the contents of a csv file to an existing sheet in an existing xlsx workbook.
## Why did I build this?
- I ran into problems trying to dump a csv into an existing sheet in an existing xlsx workbook. Most existing solutions expect you to be putting the data in a new workbook or sheet.
- To handle csv's with an improper amount of headers (not one on every column)
## What's the use case?
1. You download a csv file from a website and need to get this into an existing tab in an existing xlsx workbook.
2. You try to use pandas, but it's throwing an error because the crappy csv you downloaded doesn't have a header for every row.
3. You try to use xlsxwriter, but realise that it won't let you write to existing xlsx files.
4. You just want to replicate the human action of copying everything in a csv file and pasting it into an Excel sheet...

Hope it helps!

