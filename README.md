# dwave
run with "python train.py"

result:

Method Dataset 10 min 20 min 30 min 60 min
RMSE MAPE MAE RMSE MAPE MAE RMSE MAPE MAE RMSE MAPE MAE
XA:
FC-LSTM 5.61 0.1148 3.20 5.76 0.1196 3.32 5.87 0.1229 3.41 6.41 0.1355 3.74
DCRNN 5.38 0.1073 2.99 5.62 0.1140 3.17 5.79 0.1195 3.31 6.38 0.1376 3.78
STGCN 5.02 0.1029 2.86 5.36 0.1137 3.13 5.54 0.1213 3.30 5.94 0.1348 3.63
ASTGCN 4.94 0.0923 2.53 5.37 0.1098 3.01 5.61 0.1209 3.21 6.20 0.1364 3.77
GMAN 5.24 0.1029 2.76 5.41 0.1068 2.87 5.52 0.1100 2.95 5.91 0.1231 3.30
Graph WaveNet 4.56 0.0869 2.51 5.19 0.1049 2.96 5.44 0.1141 3.17 6.05 0.1372 3.71
HetETA* 4.87 0.0926 2.62 5.27 0.1073 2.98 5.47 0.1142 3.22 6.04 0.1244 3.55
T-wave 4.13 0.0805 2.31 4.59 0.0955 2.69 4.76 0.1011 2.82 5.06 0.1122 3.11

CD:
FC-LSTM 5.81 0.1652 3.88 6.11 0.1738 4.11 6.22 0.1790 4.19 6.76 0.1869 4.39
DCRNN 5.62 0.1332 3.40 5.83 0.1395 3.54 6.01 0.144 3.65 6.64 0.1635 4.15
STGCN 5.33 0.1236 3.21 5.65 0.1348 3.44 5.78 0.1399 3.54 6.09 0.1518 3.97
ASTGCN 5.15 0.1119 2.92 5.72 0.1341 3.39 5.95 0.1432 3.58 6.45 0.1623 4.03
GMAN 5.34 0.1288 3.13 5.55 0.1348 3.28 5.66 0.1385 3.36 6.03 0.1500 3.65
Graph WaveNet 4.71 0.1121 2.84 5.35 0.1337 3.36 5.62 0.1412 3.56 6.04 0.1574 3.83
HetETA* 5.12 0.1137 2.95 5.66 0.1324 3.35 5.91 0.1403 3.54 6.16 0.1544 3.85
T-wave 4.22 0.1053 2.63 4.64 0.1202 2.92 4.75 0.1241 3.00 4.97 0.1311 3.15
