The insiders.csv file is the master file of true positives. It gives
the dataset/release, the number of the red team scenario, the filename
of the file containing the incident observables, the username, and
start and end times.

There is one detailed observables file per incident. These files are
*not* proper CSV because the rows are variable-length. The data types
are interleaved in chronological order with an additional first column
indicating the data type of the current row.

Most datasets had one instance of each scenario, for the scenarios
that existed at the time that dataset was created. Dataset 4.2 was a
"dense needle" dataset and had many instances of each scenario. Those
instances are collected in separate subdirectories.

Brief descriptions of the red team scenarios can be found in scenarios.txt.
