I created a single awk script which takes the contents of a CSV file containing “calls for service” blotter data and produces a formatted reporting consisting of numbers representing statistics computed over this input data.
The input data is composed of records which consist of lines, with five fields delimited by commas present in each. 
These fields correspond to the following values:
Call ID, Timestamp, Problem Type, Address, Division
