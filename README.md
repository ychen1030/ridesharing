# How to run the code
Run the code with Jupyter notebook

The first few lines are for data import, including Yellow Cab demand data and Manhattan Open Street Map. Download the demand file from TLC, and change the relevant lines to your local path.
Run all cells except those marked as DO NOT RUN - these cells are an integral part of this project but are designed for special purposes only.
The code allows you choose data of different time periods, set your own parameters, etc., by changing the relevant codes.
len(demand_station) is the number of valid requests and len(pairs) is the number of matches.
Function data_process gives a breakdown of matched trips into by use of meeting points, and returns total incentives and total time saved.
