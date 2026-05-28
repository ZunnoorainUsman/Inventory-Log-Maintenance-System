# Inventory Log Maintenance System

This task was assigned to me to practice file handling in C++, especially working with CSV files, updating records, and keeping data consistent using temporary files.

## What I had to do:

I built a program that stores product information in a file called `inventory.csv`. Each record contains:

- ItemID  
- ItemName  
- Quantity  
- PricePerUnit  

The program shows a menu with these options:

1. Add New Item  
2. View All Items  
3. Search Item by ItemID  
4. Update Quantity or Price of an Item  
5. Delete an Item  
6. Exit  

## Requirements I had to follow:

- Use `getline(... , ..., ',')` to read CSV fields  
- Use C-style character arrays (`char arr[]`) instead of strings  
- Append new records to the file  
- Use a temporary file for modifications and deletions  
- Validate that Quantity and Price are numbers  
- Show proper messages for invalid input or missing records  
