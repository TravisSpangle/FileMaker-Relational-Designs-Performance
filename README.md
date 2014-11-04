FileMaker-Relational-Designs-Performance
========================================

Testing relational design impact on reporting performance.

30,000 records of: 
  + Incrementing Id
  + 20 Random Numbers
  + 20 Random Strings
  + 20 Random Paragraphs
  + Report Field

Test is to loop through every record. Concatenate the first number, string, and paragraph. Store the value to the report field and move to the next record.

- Single Table: All values are stored in a single record.
- Multi Table: Data Types are broken out into their own tables. Then related back to the main table with poly relationships.
- Multi Table Single Joins: Starts with Multi Table setup and goes a step further. Data Types are then broken out into their own region ie. Numbers1, Number2, Numbers3, etc.
- Mutable Data: Starts with Single Table then seperates the mutable data. 


