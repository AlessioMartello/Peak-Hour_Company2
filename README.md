# Peak-Hour_Company2

A script to automate the calculation of the hour of the day with the largest traffic flow, fom traffic survey data.

This script works for COMPANY 2 surveys.

Download the script.

Ensure the all the Excel spreadsheed to be analysed is in the same folder as the script.

Run the script in Jupyter Notebook.

Copy the file name and paste it in when prompted.

You will be prompted for the number of intervals (AM peak, Inter peak, PM peak). If surveys were carried out over numerous days, enter the number of survey intervals irregardless. Enter this as an integer.

You will be prompted for the number of hours in all but the last interval, in order of appearance in the excel spreadsheet. Enter each as integers and press enter after each value.

The script will then compute the rolling hours per each 15 minute interval provided in the data. 

*Note this script assumes that the survey data is in 15 minute intervals.
