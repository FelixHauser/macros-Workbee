# Macros Workbee (Ooznest CNC)

A collection of macros for the Ooznest Workbee CNC router with a Duet 3D controller board.

Specially useful if using your machine with the PanelDue display.


## How it works

Just copy the contents into the "macros" folder on the Duet's microSD card. You can also do that via web interface.

## Macros included

### Go To (folder)

To move the tool to a pre-determined positions on your CNC. Change it to fit your needs and the size of your machine.

### WCS (folder)

Change among different WCS (work coordinate system).

### Auto Probing (folder)

Use the Ooznest touch probe to set the Work Coordinates. The macros will set it to the CURRENT WCS. Choose the appropriate WCS before running the probing.

### Manual Probing WCS 2 (folder)

Jog the tool to the desired position and set it to Zero manually.
The macros will set the WCS 2 automatically.

### Calibrate Steps (folder)

Use a digital calliper or dial indicator to measure 10mm of movement in each axis and calibrate the steps/mm of each axis.

### Machine Coordinates

Change to the machine coordinate system

### WCS 2

Change to the most usual Work Coordinate System

### Go to WCS 2 Zero

Move the tool to the origin of the WCS 2 (only on the X and Y axis)
