# Extract-Data-From-csv-files
Command in terminal which can extract data from a column in csv



awk -F"," '{print $1}' fault.csv | sort | uniq -c > list.csv
