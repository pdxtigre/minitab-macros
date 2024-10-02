#    Macro:  STANDARD2.MAC
#   Author:  Cathy Akritas; Anthony N.
#  Version:  Minitab 19
#			 9/16/2024 Ver2 with control limits from a subset specified by C3 C4 columns
#
#  This macro creates a standardized control chart for the fraction of 
#  non-conforming units.  
#
#  Suppose C1 contains the number of defects (or defectives) and C2 is the total
#  number of items that were tested.  
#  C3 C4 columns contains the subset of the data that determine the control limits to be calculated from
#
#  Go to View > Show Command Line/History
#  In the Command Line pane, type the command
#
#    %Standard2 C1 C2 C3 C4
#
#  Click Run.  
#
#  Using an optional subcommand, you can use a column of dates to label the X axis.  
#  Suppose the dates are in C3.  In the Command Line pane, type
#
#    %Standard2 C1 C2 C3 C4;
#    Labels C5.
#
#  Click Run.

See example
![Standard2 Macro Example](/docs/standard2-macro-example.png)
