# crashdata-intersection-linker
Finds the nearest intersection (x/y) for each crash in a dataset

fya_write_file = the file that contains the crash numbers and x/y coordinates
fya_signals = the file that contains the intersections and their x/y
linker_write = the file that it writes the result to

uses the haversine library to select the minimum distance to the intersection for each crash
