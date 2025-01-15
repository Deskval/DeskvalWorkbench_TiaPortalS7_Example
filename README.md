All product names, logos, and brands are property of their respective owners.

# DeskvalWorkbench_TiaPortalS7_Example
PLC Project Sample - S7 Communication with Deskval Workbench

# S7 Communications
Deskval Workbench S7 Communications allows you to exchange predefined data with Siemens S7 type Plc. S7 Communications is compatible with S7-200, S7300, S7-400, S7-200, S7-1500. 
In order for this exchange, S7 Plc program should have 2 Datablocks that are related to Boolean and Num Tags.
Note that, as the exchange mechanism uses the datablock numbers and array sizes, watch for array sizes and datablock numbers.

# Setting up an S7 Communication
In order to setup S7 communication, there are things to do, both in Deskval Workbench and S7 Plc side.

## Setting Up Deskval Workbench 
o Go to Settings > S7, Enter Ip Address, Select Cpu type, Fill the fields Rack, Slot, Bool Datablock Nr, Double Block Nr and Put Enable tick

## Setting Up S7 Plc Side
o S7 Plc program should have 2 Datablocks that are related to Boolean and Num (Double typed) Tags.
o Make sure, In the attributes section, "Optimized block access" item is unchecked both for DB_BOOLEANs and DB_NUMs
o Make sure, In the Protection&Security section, "Permit access PUTGET communications from remote partner" is checked and "Full access" is checked
