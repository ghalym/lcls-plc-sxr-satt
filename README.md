# lcls-plc-sxr-satt

SXR Solid Attenuator TwinCAT Project

## Devices

| Name        | Instrument | Area | Z [m] |
|-------------|------------|------|-------|
| AT1K4-SOLID | TMO        | FEE  | 748   |
| AT1K2-SOLID | NEH 2.2    | H2.2 | 784   |
| AT2K2-SOLID | NEH 2.2    | H2.2 | 788.8 |
| AT1K3-SOLID | TXI        | H1.1 | ~763  |

## Factory Acceptance Test Open-loop Motion Results

| Attenuator | Axis | Encoder readout at CW/negative limit | Encoder readout at CCW/positive limit | Range measured with encoder | Range measured with motor controller | Reversal Error  | Unidirectional Positioning Repeatability  | RMS Accuracy  | Actuator speed  |
|------------|------|--------------------------------------|---------------------------------------|-----------------------------|--------------------------------------|-----------------|-------------------------------------------|---------------|-----------------|
|            |      | [mm]                                 | [mm]                                  | [mm]                        | [mm]                                 | [µm]            | [µm]                                      | [µm]          | [mm/s]          |
| SPARE      | 1071 |                                      |                                       |                             |                                      | 17.0            | 1.9                                       | 8.0           | 20              |
| SPARE      | 1073 |                                      |                                       |                             |                                      | 20.0            | 2.1                                       | 4.0           | 20              |
| SPARE      | 1074 |                                      |                                       |                             |                                      | 15.0            | 1.2                                       | 1.4           | 20              |
| SPARE      | 1076 |                                      |                                       |                             |                                      | 12.0            | 1.5                                       | 1.4           | 20              |
| SN-11343   | 1086 | 150.60                               | 17.37                                 | 133.2                       | 133.3                                | 13.0            | 1.2                                       | 1.0           | 20              |
| SN-11343   | 1087 | 151.30                               | 17.72                                 | 133.6                       | 133.7                                | 12.0            | 1.5                                       | 2.4           | 20              |
| SN-11343   | 1088 | 151.80                               | 18.32                                 | 133.5                       | 133.5                                | 13.0            | 0.9                                       | 1.3           | 20              |
| SN-11343   | 1089 | 151.95                               | 18.24                                 | 133.7                       | 133.9                                | 13.0            | 1.6                                       | 1.8           | 20              |
| SN-11344   | 1075 | 152.00                               | 18.73                                 | 133.3                       | 133.4                                | 13.0            | 0.7                                       | 1.7           | 20              |
| SN-11344   | 1077 | 150.99                               | 17.22                                 | 133.8                       | 134.0                                | 14.0            | 1.6                                       | 1.6           | 20              |
| SN-11344   | 1078 | 151.01                               | 17.61                                 | 133.4                       | 133.5                                | 8.9             | 1.0                                       | 2.2           | 20              |
| SN-11344   | 1079 | 151.03                               | 17.66                                 | 133.4                       | 133.3                                | 11.0            | 1.6                                       | 2.0           | 20              |
| SN-11345   | 1070 | 152.25                               | 18.79                                 | 133.5                       | 133.5                                | 16.0            | 0.5                                       | 1.8           | 20              |
| SN-11345   | 1072 | 151.20                               | 17.69                                 | 133.5                       | 133.6                                | 11.0            | 1.0                                       | 1.4           | 20              |
| SN-11345   | 1084 | 152.20                               | 18.83                                 | 133.4                       | 133.4                                | 11.0            | 0.7                                       | 1.4           | 20              |
| SN-11345   | 1085 | 150.30                               | 16.64                                 | 133.7                       | 133.6                                | 13.0            | 1.7                                       | 2.1           | 20              |
