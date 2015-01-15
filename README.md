# port_reader_dlportio
copy of port_reader using dlportio.dll instead of inpout32.ddl for the smathot/OpenSesame project (https://github.com/smathot/OpenSesame)

# Install

Copy the folder "port_reader_dlportio" to the OpenSesame plugins folder (for Windows 7 x64 normally "C:\Program Files (x86)\OpenSesame\plugins" ).

# About

The port_reader_dlportio plug-in reads input from an arbitrary port, such as a parallel or serial port, and interprets the return value as a participant's response (i.e., a button press). It's basically a copy of the port_reader plug-in working with dlportio.ddl instead of inpout32.dll. Also an option to convert to a 'E-Prime compatible' lpt register numbers has been added.

Options

Dummy mode - If set to 'yes', the keyboard is used instead. Useful for testing purposes.

Port number - The number of the port that you want to use.

Resting state value - The value that should be interpreted as 'no button pressed'.

Correct response - The expected response.

Timeout - The maximum allowed response time, after which a timeout should be signaled.

Convert to 5 6 7 8 - This converts the decimal values 23, 39, 71 and 135 to 5, 6, 7 and 8. These are the numbers of the lpt register. When multiple buttons are pressed the lowest number overrules. 

