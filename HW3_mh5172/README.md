# Homework
## Assignment 1: Delete data and its history from GitHub
[Screenshots](delete_file.md)
## Assignment 2: Read CSV files with pandas and use NYC open data portal
[Assignment2_mh5172](Assignment2_mh5172.ipynb)

p.s. I found there were some mistakes in this file by myself one day later than the DDL (I am in the morning session), I modified it and re-uploaded . The original file can still be found in the history. Thanks
## Part 1
Downloaded a csv format data from NYCOpenData, read, and plot 2 rows of it in jupyter notebook.

## Part 2: Extra Credit
Downloded a json format data by API, and plot 2 rows of it in jupyter notebook.

## Assignment 3: Tracking each vehicle for a line
### [show\_bus_locations.py](show_bus_locations_mh5172.py)
This script tracks a certain _Bus Line_, and displays the activate buses' current coordinate. The results shows in terminal. If you input a wrong _API KEY_, this script will print "API key is not authorized", If you input a wrong _BUS LINE_, this script will print "No such route". If you input more than 3 _argv_, it will print "wrong input".

## Assignment 4: next stop information
### [get\_bus_info.py](get_bus_info_mh5172.py)
This script tracks a certain _Bus Line_, and displays the activate buses' current status. The results will be stored as a csv file in current repository named as _bus\_line_. When the OnwardCalls field is empty,  the “Stop Name” and “Stop Status” fields will be dsiplayed as 'N/A'. If you input a wrong _API KEY_, this script will print "API key is not authorized", If you input a wrong _BUS LINE_, this script will print "No such route".If you input more than 4 _argv_, it will print "wrong input".

P.S I modified this script because in the former version, my code didn't allow input the fourth sys.argv and the name of csv file is same as the _bus line_, the second sys.argv. Still, the former version can be found in the history, thanks.

