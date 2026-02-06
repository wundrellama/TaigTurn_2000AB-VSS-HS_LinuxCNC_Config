# TaigTurn_2000AB-VSS-HS_LinuxCNC_Config

LinuxCNC configs for a stock MicroProto (Taig) VSS TaigTurn 2000AB Lathe using a parallel port. May not be perfect (suggestions/corrections/gripes/complaints welcome). Started with the provided Mach3 config and built out from there.

GMOCCAPY step sizes are non-standard (our preference), but can be altered in the .ini file.

Actual spindle RPM is working in the GMOCCAPY bar. Threading should work, but I haven't actually tested it yet.

You may want to invert the X and Z direction pins depending on your setup.
