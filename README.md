```
Send: M503

G21; Units in mm (mm)

M149 C ; Units in Celsius

; Filament settings: Disabled
M200 S0 D1.75

; Steps per unit:
 M92 X80.00 Y80.00 Z400.00 E415.00

; Maximum feedrates (units/s):
M203 X500.00 Y500.00 Z10.00 E50.00

; Maximum Acceleration (units/s2):
M201 X500.00 Y500.00 Z100.00 E5000.00

; Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
M204 P500.00 R1000.00 T500.00

; Advanced: B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> X<max_x_jerk> Y<max_y_jerk> Z<max_z_jerk> E<max_e_jerk>
M205 B20000.00 S0.00 T0.00 X8.00 Y8.00 Z0.40 E5.00

; Home offset:
M206 X0.00 Y0.00 Z0.00

; Auto Bed Leveling:
M420 S1 Z2.00
G29 W I0 J0 Z0.19600
G29 W I1 J0 Z0.12300
G29 W I2 J0 Z0.15750
G29 W I3 J0 Z0.19750
G29 W I0 J1 Z0.16850
G29 W I1 J1 Z0.14700
G29 W I2 J1 Z0.18150
G29 W I3 J1 Z0.22350
G29 W I0 J2 Z0.13600
G29 W I1 J2 Z0.12000
G29 W I2 J2 Z0.16500
G29 W I3 J2 Z0.21000
G29 W I0 J3 Z0.13650
G29 W I1 J3 Z0.12700
G29 W I2 J3 Z0.17800
G29 W I3 J3 Z0.22900

; Material heatup parameters:
M145 S0 H180 B70 F0
M145 S1 H240 B110 F0

; PID settings:
M301 P15.72 I1.24 D49.77
M304 P66.39 I12.94 D227.14

; Power-Loss Recovery:
M413 S1

; Z-Probe Offset (mm):
M851 X41.00 Y0.00 Z-1.80

; Filament load/unload lengths:
M603 L450.00 U450.00

; Filament runout sensor:
M412 S0
```