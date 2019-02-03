Generate Spectra Logo For Printer
=================
Function
------------
Get hex code from c header file and reverse its bytes and save in file with prefix spectra. 
This code is for generate spectra compatible logo header

Steps To Generate
------------
For convert bitmap to printer spectra format:
 1. use LCDAssistant.exe by these settings :
	 - Byte orientation : Horizontal
	 - pixels/byte : 8
 2. Load image and save output.
 3. use reverseByteInArray program to convert saved output in previous section to spectra compatible logo header file.

> Written By H.assaran