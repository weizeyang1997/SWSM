I’ve drafted a standalone Python script (read_nc.py) that:

Scans a directory for your NetCDF files

Opens each file using netCDF4

Reads and stores the time, Latitude, Longitude, and layer (L1, L2, L3) variables

Prints out data dimensions for quick inspection
