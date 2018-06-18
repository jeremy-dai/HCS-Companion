# HCS-Companion
This excel marco helps prepare data for Highway Capacity Analysis

## Function One
### Calculate the distance between segments
1. Create Line Diagram tab as the example.
2. Type in the interchange names in row 4 and 21
3. Type in the ramp names in row 3 and 22
4. Type in the station number in row 7 and 18 : in the same columns as the interchange/ramp names
5. Run the LineDiagram Macro. It will automatically calculate the distances between ramps and put the numbers in row 6 and 19
6. Based on the distance and other information, divide the whole segments into Basic/Merge,Diverge/Weaving areas and color the cells

## Function Two
### Calculate the density
1. Create Inputs tab as the example excel sheet.
2. Copy the Station Numbers generated by Function One and paste in the new tab as the example excel sheet.
3. Choose transpose.
4. In column P and Column Q, create vlookup formulas to get the station number based on the station number tab
5. Adjust the reference point based on segment types for density calculation.
6. Change the code to match the direction. NB? EB?
7. Run the density macro. It will automatically get densities and put the numbers in column U and V

## Function Three
### Extract and summarize the HCS results based on the txt files generated by HCS 2010
1. Choose Basic Macro for basic freeway segment
2. Choose Ramp Macro for ramps
3. Choose Weaving Macro for weaving segment
4. Run the Macro.
