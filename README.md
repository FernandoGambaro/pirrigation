# pirrigation

<strong>Simple irrigation management system with Raspberry PI</strong>

Project: Irrigation automation through a 1HP submersible pump installed at a depth of 50 meters.

Known scenario:
The well has a low water flow, so the pump operation cannot exceed 15 minutes, having at least 40 minutes of flow recovery. That is, the pump works for 15 minutes and rests for at least 40.

Materials:
Irrigation: 1HP submersible pump
Black plastiduct hose the necessary meters.
Irrigation sprinklers, the necessary ones. (keep in mind that due to the low flow rate it is recommended not to use more than 4 large ones simultaneously)

Automation and control:
Raspberry Pi 3 Device
Power supply for the Raspberry 5v 2.5amp
6 5v relays, (SRD-05VCD-SL-C) are only used simultaneously.
Transformer 220v to 24v (To power the solenoids that divide the irrigation, tank and pump sectors)
LCD1602 module (to display the status of the pump)
