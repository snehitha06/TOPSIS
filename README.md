# TOPSIS
A python library implementing TOPSIS for MCDM
#What is Topsis?
TOPSIS is technique commonly used to solve decision-making problems. This technique is based on the comparison between all the alternatives included in the problem.

#Problem Statement
Example:
<img width="636" alt="image" src="https://user-images.githubusercontent.com/69567782/155388281-f3e6e94d-42f7-4fcc-9af0-5b9ba7747d55.png">

#Conditions:
• Correct number of parameters (inputFileName, Weights, Impacts, resultFileName).
• Show the appropriate message for wrong inputs.
• Handling of “File not Found” exception
• Input file must contain three or more columns.
• From 2nd to last columns must contain numeric values only (Handling of non-numeric values)
• Number of weights, number of impacts and number of columns (from 2nd to last columns) must be same.
• Impacts must be either +ve or -ve.
• Impacts and weights must be separated by ‘,’ (comma).

Run the program through command line as:
Usages: python <program.py> <InputDataFile> <Weights> <Impacts> <ResultFileName>
Example: python file.py data.csv “1,1,1,2” “+,+,-,+” result.csv
