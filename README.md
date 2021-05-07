```
Send: M503
Recv: echo:  G21    ; Units in mm (mm)
Recv: echo:  M149 C ; Units in Celsius
Recv: 
Recv: echo:; Filament settings: Disabled
Recv: echo:  M200 S0 D1.75
Recv: echo:; Steps per unit:
Recv: echo: M92 X80.00 Y80.00 Z400.00 E415.00
Recv: echo:; Maximum feedrates (units/s):
Recv: echo:  M203 X500.00 Y500.00 Z10.00 E50.00
Recv: echo:; Maximum Acceleration (units/s2):
Recv: echo:  M201 X500.00 Y500.00 Z100.00 E5000.00
Recv: echo:; Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P500.00 R1000.00 T500.00
Recv: echo:; Advanced: B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> X<max_x_jerk> Y<max_y_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 B20000.00 S0.00 T0.00 X8.00 Y8.00 Z0.40 E5.00
Recv: echo:; Home offset:
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:; Auto Bed Leveling:
Recv: echo:  M420 S1 Z2.00
Recv: echo:  G29 W I0 J0 Z0.19600
Recv: echo:  G29 W I1 J0 Z0.12300
Recv: echo:  G29 W I2 J0 Z0.15750
Recv: echo:  G29 W I3 J0 Z0.19750
Recv: echo:  G29 W I0 J1 Z0.16850
Recv: echo:  G29 W I1 J1 Z0.14700
Recv: echo:  G29 W I2 J1 Z0.18150
Recv: echo:  G29 W I3 J1 Z0.22350
Recv: echo:  G29 W I0 J2 Z0.13600
Recv: echo:  G29 W I1 J2 Z0.12000
Recv: echo:  G29 W I2 J2 Z0.16500
Recv: echo:  G29 W I3 J2 Z0.21000
Recv: echo:  G29 W I0 J3 Z0.13650
Recv: echo:  G29 W I1 J3 Z0.12700
Recv: echo:  G29 W I2 J3 Z0.17800
Recv: echo:  G29 W I3 J3 Z0.22900
Recv: echo:; Material heatup parameters:
Recv: echo:  M145 S0 H180 B70 F0
Recv: echo:  M145 S1 H240 B110 F0
Recv: echo:; PID settings:
Recv: echo:  M301 P15.72 I1.24 D49.77
Recv: echo:  M304 P66.39 I12.94 D227.14
Recv: echo:; Power-Loss Recovery:
Recv: echo:  M413 S1
Recv: echo:; Z-Probe Offset (mm):
Recv: echo:  M851 X41.00 Y0.00 Z-1.80
Recv: echo:; Filament load/unload lengths:
Recv: echo:  M603 L450.00 U450.00
Recv: echo:; Filament runout sensor:
Recv: echo:  M412 S0
Recv: ok
```