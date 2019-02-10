# Pumping station control system using a Raspberry Pi as a PLC

This is a portfolio project that aims to construct a cheap control system for a wastewater pumping station using a Raspberry Pi as a PLC.
The goal is to have a functioning system with as many bells and whistles as possible.

# Intended functionality
The system is intended to have the following functionality:
 * Start and stop the pumps using contactors
 * Measure and log the functioning time of each pump
 * Use the an unltrasonic level sensor in addition to float switches
 * Run a web server for diagnostics
 * Send messages using GSM 
 * Send messages suing LORA
 * Integrate into a SCADA system
 * Control temperature of the cabinet it is placed in
 * Create a log of errors 
 * Use an alarm beacon
 * Detect pump clogging and run the pump in reverse
 * Generate reports in Excel or PDF format

# Isolating the control part
The idea is to have the ability to change the PLC brand with unplugging an Ethernet cable and connecting another PLC.

All I/O will be connected to an expandable remote I/O module.  