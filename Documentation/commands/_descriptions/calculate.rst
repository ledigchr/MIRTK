.. Auto-generated by mirtk-help-rst from "mirtk calculate -h" output


This tool can be used for basic calculations from a sequence of data values read
either from an image or a VTK pointset. It can be used, for example, to add two
data sequences and to divide the result by a constant. The current sequence can
be written to an output file again using the -out option. Additionally, statistics
of the current data sequence can be computed such as the mean or variance.
The order of the data transformations and calculation of statistics is determined
by the order of the command-line arguments.

By default, data statistics are printed to STDOUT in a human readable format.
This output can be appended to a text file using the -append option instead.
For a more machine readable output, e.g., as comma separated values (CSV),
specify a delimiting string using the -d option. In this case, a header line
is also printed when the -header option is given with optional user specified
column names for the individual output values.
