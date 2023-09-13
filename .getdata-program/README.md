# MODFLOW class McDonald Valley problem data program

The `get-data` program is used in the MODFLOW class to retireve new data for students to use during phase 3 of the McDonald Valley calibration exercise. The program can retrieve well data, aquifer test data, and seismic sections for the McDonald Valley domain.

## Compile get-data using:

```
gfortran getdata.f -o get-data
```

## Prepare for a new class

Copy `get-data`, the `data` subdirectory, and the `output` subdirectory to a working directory for the class.


To terminate a well data request type:

```
0 0 0 0
```