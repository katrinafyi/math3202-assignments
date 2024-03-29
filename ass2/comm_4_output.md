Communication 4
==============================================================================

```
Academic license - for non-commercial use only
Optimize a model with 190 rows, 180 columns and 648 nonzeros
Coefficient statistics:
  Matrix range     [1e+00, 5e+00]
  Objective range  [6e+02, 3e+03]
  Bounds range     [0e+00, 0e+00]
  RHS range        [6e+00, 9e+01]
Presolve removed 156 rows and 150 columns
Presolve time: 0.01s
Presolved: 34 rows, 30 columns, 330 nonzeros

Iteration    Objective       Primal Inf.    Dual Inf.      Time
       0    0.0000000e+00   3.012500e+01   0.000000e+00      0s
      19    1.9878743e+05   0.000000e+00   0.000000e+00      0s

Solved in 19 iterations and 0.01 seconds
Optimal objective  1.987874290e+05
```

## -- GUROBI OUTPUT -- ##
### 198787.42902208204
```
Optimised for communication 4.
Objective value: 198787.42902208204
```




## == ANALYSIS NON-ZERO == ##
(variables not printed are 0)


```
Variable Analysis
 variable  =     x *  coeff |     rc | obj low obj high
X[DC2,S0]  =  18.0 *  807.0 |      0 |       0       0
X[DC0,S1]  =   7.0 * 1058.0 |      0 |       0       0
X[DC0,S2]  =  21.0 * 2014.0 |      0 |       0       0
X[DC1,S3]  =  15.0 * 1982.0 |      0 |       0       0
X[DC0,S4]  =  13.0 * 1952.0 |      0 |       0       0
X[DC2,S4]  =   4.0 * 1456.0 |      0 |       0       0
X[DC1,S5]  = 8.6225 * 2577.0 |      0 |       0       0
X[DC2,S5]  = 1.3775 * 1273.0 |      0 |       0       0
X[DC1,S6]  =   6.0 * 2063.0 |      0 |       0       0
X[DC1,S7]  = 4.5005 * 2807.0 |      0 |       0       0
X[DC2,S7]  = 3.4995 *  559.0 |      0 |       0       0
X[DC1,S8]  = 3.938 * 2924.0 |      0 |       0       0
X[DC2,S8]  = 3.062 * 1014.0 |      0 |       0       0
X[DC0,S9]  =   7.0 * 1153.0 |      0 |       0       0
```



## == CONSTRAINTS == ##

```
Constraint Analysis
           constr      rhs |  slack     pi | rhs low rhs high
      n_demand S0  >  18.0 |    0.0      0 |       0       0
      n_demand S1  >   7.0 |    0.0      0 |       0       0
      n_demand S2  >  21.0 |    0.0      0 |       0       0
      n_demand S3  >  15.0 |   -0.0      0 |       0       0
      n_demand S4  >  17.0 |   -0.0      0 |       0       0
      n_demand S5  >  10.0 |   -0.0      0 |       0       0
      n_demand S6  >   6.0 |    0.0      0 |       0       0
      n_demand S7  >   8.0 |    0.0      0 |       0       0
      n_demand S8  >   7.0 |    0.0      0 |       0       0
      n_demand S9  >   7.0 |    0.0      0 |       0       0
   n_capacity DC0  <  72.0 |   24.0      0 |       0       0
   n_capacity DC1  <  76.0 | 37.939      0 |       0       0
   n_capacity DC2  <  40.0 | 10.061      0 |       0       0
      n_northside  <  88.0 | 10.061      0 |       0       0
   U0 s_demand S3  >  29.0 |    0.0      0 |       0       0
U0 s_capacity DC0  <  72.0 |   24.0      0 |       0       0
U0 s_capacity DC1  <  76.0 | 23.939      0 |       0       0
U0 s_capacity DC2  <  40.0 | 10.061      0 |       0       0
   U0 s_northside  <  88.0 | 10.061      0 |       0       0
   U1 s_demand S7  >  31.0 |   -0.0      0 |       0       0
U1 s_capacity DC0  <  72.0 |   24.0      0 |       0       0
U1 s_capacity DC1  <  76.0 |   25.0      0 |       0       0
U1 s_capacity DC2  <  40.0 |    0.0      0 |       0       0
   U1 s_northside  <  88.0 |    0.0      0 |       0       0
   U2 s_demand S0  >  19.0 |   -0.0      0 |       0       0
U2 s_capacity DC0  <  72.0 |   24.0      0 |       0       0
U2 s_capacity DC1  <  76.0 | 37.939      0 |       0       0
U2 s_capacity DC2  <  40.0 |  9.061      0 |       0       0
   U2 s_northside  <  88.0 |  9.061      0 |       0       0
   U3 s_demand S8  >  30.0 |   -0.0      0 |       0       0
U3 s_capacity DC0  <  72.0 |   24.0      0 |       0       0
U3 s_capacity DC1  <  76.0 |   25.0      0 |       0       0
U3 s_capacity DC2  <  40.0 |    0.0      0 |       0       0
   U3 s_northside  <  88.0 |    0.0      0 |       0       0
   U4 s_demand S4  >  21.0 |    0.0      0 |       0       0
   U4 s_demand S5  >  54.0 |    0.0      0 |       0       0
U4 s_capacity DC0  <  72.0 | 20.9412      0 |       0       0
U4 s_capacity DC1  <  76.0 |    0.0      0 |       0       0
U4 s_capacity DC2  <  40.0 | 3.0588      0 |       0       0
   U4 s_northside  <  88.0 |    0.0      0 |       0       0
```


## == NORMAL DEMAND ANALYSIS == ##

```
X[DC2,S0] = 18.0
X[DC0,S1] = 7.0
X[DC0,S2] = 21.0
X[DC1,S3] = 15.0
X[DC0,S4] = 13.000000000000002
X[DC2,S4] = 3.9999999999999987
X[DC1,S5] = 8.622502628811777
X[DC2,S5] = 1.3774973711882228
X[DC1,S6] = 6.0
X[DC1,S7] = 4.500525762355415
X[DC2,S7] = 3.499474237644585
X[DC1,S8] = 3.937960042060988
X[DC2,S8] = 3.062039957939012
X[DC0,S9] = 7.0
Store sums: {'S0': 18.0, 'S1': 7.0, 'S2': 21.0, 'S3': 15.0, 'S4': 17.0, 'S5': 10.0, 'S6': 6.0, 'S7': 8.0, 'S8': 7.0, 'S9': 7.0}
DC sums: {'DC0': 48.0, 'DC1': 38.060988433228175, 'DC2': 29.939011566771818}
```

## == SURGE ANALYSIS == ##

Surge multipliers
```
{('U0', 'S0'): 1.0, ('U1', 'S0'): 1.0, ('U2', 'S0'): 1.0555555555555556, ('U3', 'S0'): 1.0, ('U4', 'S0'): 1.0, ('U0', 'S1'): 1.0, ('U1', 'S1'): 1.0, ('U2', 'S1'): 1.0, ('U3', 'S1'): 1.0, ('U4', 'S1'): 1.0, ('U0', 'S2'): 1.0, ('U1', 'S2'): 1.0, ('U2', 'S2'): 1.0, ('U3', 'S2'): 1.0, ('U4', 'S2'): 1.0, ('U0', 'S3'): 1.9333333333333333, ('U1', 'S3'): 1.0, ('U2', 'S3'): 1.0, ('U3', 'S3'): 1.0, ('U4', 'S3'): 1.0, ('U0', 'S4'): 1.0, ('U1', 'S4'): 1.0, ('U2', 'S4'): 1.0, ('U3', 'S4'): 1.0, ('U4', 'S4'): 1.2352941176470589, ('U0', 'S5'): 1.0, ('U1', 'S5'): 1.0, ('U2', 'S5'): 1.0, ('U3', 'S5'): 1.0, ('U4', 'S5'): 5.4, ('U0', 'S6'): 1.0, ('U1', 'S6'): 1.0, ('U2', 'S6'): 1.0, ('U3', 'S6'): 1.0, ('U4', 'S6'): 1.0, ('U0', 'S7'): 1.0, ('U1', 'S7'): 3.875, ('U2', 'S7'): 1.0, ('U3', 'S7'): 1.0, ('U4', 'S7'): 1.0, ('U0', 'S8'): 1.0, ('U1', 'S8'): 1.0, ('U2', 'S8'): 1.0, ('U3', 'S8'): 4.285714285714286, ('U4', 'S8'): 1.0, ('U0', 'S9'): 1.0, ('U1', 'S9'): 1.0, ('U2', 'S9'): 1.0, ('U3', 'S9'): 1.0, ('U4', 'S9'): 1.0}
```

### Surge U0
```
Y[DC2,S0,U0] = 18.0
Y[DC0,S1,U0] = 7.0
Y[DC0,S2,U0] = 21.0
Y[DC1,S3,U0] = 29.0
Y[DC0,S4,U0] = 13.000000000000002
Y[DC2,S4,U0] = 3.9999999999999987
Y[DC1,S5,U0] = 8.622502628811777
Y[DC2,S5,U0] = 1.3774973711882228
Y[DC1,S6,U0] = 6.0
Y[DC1,S7,U0] = 4.500525762355415
Y[DC2,S7,U0] = 3.499474237644585
Y[DC1,S8,U0] = 3.937960042060988
Y[DC2,S8,U0] = 3.062039957939012
Y[DC0,S9,U0] = 7.0
Store sums: {'S0': 18.0, 'S1': 7.0, 'S2': 21.0, 'S3': 29.0, 'S4': 17.0, 'S5': 10.0, 'S6': 6.0, 'S7': 8.0, 'S8': 7.0, 'S9': 7.0}
DC sums: {'DC0': 48.0, 'DC1': 52.060988433228175, 'DC2': 29.939011566771818}
Cost (weekly, no labour): 226535.42902208204
```

### Surge U1
```
Y[DC2,S0,U1] = 18.0
Y[DC0,S1,U1] = 7.0
Y[DC0,S2,U1] = 21.0
Y[DC1,S3,U1] = 15.000000000000002
Y[DC0,S4,U1] = 13.000000000000002
Y[DC2,S4,U1] = 3.9999999999999987
Y[DC1,S5,U1] = 8.622502628811777
Y[DC2,S5,U1] = 1.3774973711882228
Y[DC1,S6,U1] = 6.0
Y[DC1,S7,U1] = 17.439537329127234
Y[DC2,S7,U1] = 13.560462670872766
Y[DC1,S8,U1] = 3.937960042060988
Y[DC2,S8,U1] = 3.062039957939012
Y[DC0,S9,U1] = 7.0
Store sums: {'S0': 18.0, 'S1': 7.0, 'S2': 21.0, 'S3': 15.000000000000002, 'S4': 17.0, 'S5': 10.0, 'S6': 6.0, 'S7': 31.0, 'S8': 7.0, 'S9': 7.0}
DC sums: {'DC0': 48.0, 'DC1': 51.0, 'DC2': 40.00000000000001}
Cost (weekly, no labour): 240731.32702418504
```

### Surge U2
```
Y[DC2,S0,U2] = 19.0
Y[DC0,S1,U2] = 7.0
Y[DC0,S2,U2] = 21.0
Y[DC1,S3,U2] = 15.000000000000002
Y[DC0,S4,U2] = 13.000000000000002
Y[DC2,S4,U2] = 3.9999999999999987
Y[DC1,S5,U2] = 8.622502628811777
Y[DC2,S5,U2] = 1.3774973711882228
Y[DC1,S6,U2] = 6.0
Y[DC1,S7,U2] = 4.500525762355415
Y[DC2,S7,U2] = 3.499474237644585
Y[DC1,S8,U2] = 3.937960042060988
Y[DC2,S8,U2] = 3.062039957939012
Y[DC0,S9,U2] = 7.0
Store sums: {'S0': 19.0, 'S1': 7.0, 'S2': 21.0, 'S3': 15.000000000000002, 'S4': 17.0, 'S5': 10.0, 'S6': 6.0, 'S7': 8.0, 'S8': 7.0, 'S9': 7.0}
DC sums: {'DC0': 48.0, 'DC1': 38.06098843322818, 'DC2': 30.939011566771818}
Cost (weekly, no labour): 199594.42902208204
```

### Surge U3
```
Y[DC2,S0,U3] = 18.0
Y[DC0,S1,U3] = 7.0
Y[DC0,S2,U3] = 21.0
Y[DC1,S3,U3] = 15.000000000000002
Y[DC0,S4,U3] = 13.000000000000002
Y[DC2,S4,U3] = 3.9999999999999987
Y[DC1,S5,U3] = 8.622502628811777
Y[DC2,S5,U3] = 1.3774973711882228
Y[DC1,S6,U3] = 6.0
Y[DC1,S7,U3] = 4.500525762355415
Y[DC2,S7,U3] = 3.499474237644585
Y[DC1,S8,U3] = 16.876971608832804
Y[DC2,S8,U3] = 13.123028391167194
Y[DC0,S9,U3] = 7.0
Store sums: {'S0': 18.0, 'S1': 7.0, 'S2': 21.0, 'S3': 15.000000000000002, 'S4': 17.0, 'S5': 10.0, 'S6': 6.0, 'S7': 8.0, 'S8': 30.0, 'S9': 7.0}
DC sums: {'DC0': 48.0, 'DC1': 51.0, 'DC2': 40.0}
Cost (weekly, no labour): 246822.94111461617
```

### Surge U4
```
Y[DC2,S0,U4] = 18.0
Y[DC0,S1,U4] = 7.0
Y[DC0,S2,U4] = 21.0
Y[DC1,S3,U4] = 15.000000000000002
Y[DC0,S4,U4] = 16.058823529411768
Y[DC2,S4,U4] = 4.941176470588232
Y[DC1,S5,U4] = 46.5615141955836
Y[DC2,S5,U4] = 7.438485804416404
Y[DC1,S6,U4] = 6.0
Y[DC1,S7,U4] = 4.500525762355415
Y[DC2,S7,U4] = 3.499474237644585
Y[DC1,S8,U4] = 3.937960042060988
Y[DC2,S8,U4] = 3.062039957939012
Y[DC0,S9,U4] = 7.0
Store sums: {'S0': 18.0, 'S1': 7.0, 'S2': 21.0, 'S3': 15.000000000000002, 'S4': 21.0, 'S5': 54.0, 'S6': 6.0, 'S7': 8.0, 'S8': 7.0, 'S9': 7.0}
DC sums: {'DC0': 51.05882352941177, 'DC1': 76.0, 'DC2': 36.94117647058823}
Cost (weekly, no labour): 311613.0765757407
```

## == STORE ASSIGNMENTS == ##
```
Store Assignments
store |    DC0    DC1    DC2
   S0 |                  1.0
   S1 |    1.0              
   S2 |    1.0              
   S3 |           1.0       
   S4 | 0.7647        0.2353
   S5 |        0.8623 0.1377
   S6 |           1.0       
   S7 |        0.5626 0.4374
   S8 |        0.5626 0.4374
   S9 |    1.0              
```

```
Store & DC0 & DC1 & DC2 \\
S0 &  &  & 100.0\% \\
S1 & 100.0\% &  &  \\
S2 & 100.0\% &  &  \\
S3 &  & 100.0\% &  \\
S4 & 76.47\% &  & 23.53\% \\
S5 &  & 86.23\% & 13.77\% \\
S6 &  & 100.0\% &  \\
S7 &  & 56.26\% & 43.74\% \\
S8 &  & 56.26\% & 43.74\% \\
S9 & 100.0\% &  &  \\
```

This was communication 4 with value 198787.42902208204
