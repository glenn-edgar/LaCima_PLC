Welcome to the CLICK PLC Programming Software
Version 1.40 Jun 12 2013
------------------------------------------------------------------------------------
This document describes some of the changes in this release of the CLICK PLC Programming Software. It also includes known issues as well as updated information for the documentation provided with the software. The information in this file and in the help file is more up-to-date than the information in the printed software installation and hardware user manuals.


Contents

1. Welcome
2. Getting Started
3. What's New?
4. Known Issues
5. Documentation and Help File Changes
6. Known Problems and Conditions
7. Uninstalling the CLICK PLC Programming Software
8. Technical Support Procedures and Contact Information


Part 1: Welcome

AutomationDirect.com would like to thank you for using the CLICK PLC Programming Software. We have included many powerful and exciting features in the software; however, we know that our customers sometimes have great ideas for features. Please feel free to give us input on the CLICK PLC product line and you may even request features that you feel would improve the software for your application.


Part 2: Getting Started

See the CLICK PLC Programming Software Installation Manual for help with installing the software on your PC. Also see the CLICK PLC Hardware User Manual. The chapter 1 of the Hardware User Manual features a step-by-step instruction for the first time CLICK PLC users.


Part 3: What's New?

Jun/12/2013 - Version 1.40

- Supported new analog I/O modules.
- Supported new discrete combo I/O modules.
- Supported new System Monitor window.
- Improved the System Configuration window to display the DF addresses assigned to analog I/O points.
- Fixed the problem that only 6 paper sizes were available in the Print window.

Nov/02/2011 - Version 1.33

- This version includes new CPU firmware V1.33. It fixed a bug that Analog CPU modules read a wrong analog input value occasionally. The CPU firmware V1.30 and V1.31 had this bug.

Aug/23/2011 - Version 1.32

- Fixed the problem that the CLICK Programming Software tried to include old firmware V1.30 into the CLICK Loader file instead of the correct firmware V1.31 when the CLICK Loader file was exported.

Jul/6/2011 - Version 1.31

- This version includes new CPU firmware V1.31 that fixed some major bugs found in firmware V1.30.

May/6/2011 - Version 1.30

- Improved the Send instruction (ASCII) by supporting the NULL code as an embedded ASCII character.
- Modified the Receive/Send instructions and their setup windows no longer display the setup parameters that are not supported by the selected protocol. 
- Fixed the problem that unnecessary warning messages were displayed even if the analog I/O setup was correct.

Dec/16/2010 - Version 1.21

- Improved Find, now supports searching by Instruction type.
- Improved Address Picker, now opens at address used in the current instruction.
- Improved Error flag (Port2=SC101, Port3=SC103) now shown in Receive instruction of ASCII mode.
- Fixed the problem that Cross Reference only shows start and end addresses used in Math instruction (SUM operation).
- Fixed the problem that Cross Reference does not show DF addresses assigned to Analog I/O.
- Fixed the problem that Math instruction sometimes does not work correctly with constant values.
- Fixed the problem that CPU Built-in I/O Setup shows unclear error message when deselecting "Continuous Address".

Nov/17/2010 - Version 1.20

- Supported new Standard CPU modules.
- Supported new 24VAC/DC input modules.
- Improved the Rung Comment feature to support Arabic.
- Fixed the problem that the Print dialog output the PDF file without allowing the user to rename the file and select the save location.

May/13/2010 - Version 1.12

- When there are three branches in a rung, Coil and/or Box instructions could be energized unexpectedly.
- When two OR circuits were connected to the same vertical line (master line), there was a syntax error. (OR circuit = Two or more Contact instructions are connected in parallel.)
- The syntax error check algorithm was improved to prevent any incorrect ladder programs from downloading into the CLICK PLC.
- The Drum instruction no longer consumes a TD address in the Event Base mode.

Nov/23/2009 - Version 1.11

- Added the CLICK Project Loader tool. This tool is available from the Start menu. See the CLICK Project Loader User Guide for details. (This is also available from the Start menu.)
- Added the Override View.
- Added the Exact Match option to the Address Picker, Cross Reference View and Find windows.
- Included the CLICK Hardware user Manual.
- Improved the communication between the CLICK Programming Software and the CLICK PLC. This improvement would reduce the risk of the software crash that some customers had experienced.
- Changed the icons for the interrupt programs.
- Fixed the problem that the CLICK Programming software opened on the Windows with a European language setup didn't accept the comma as the decimal point.
- Fixed the problem that the Timer instruction was set to retain the current timer value and there were 2 contacts in parallel (OR connection) connected to the enable input of the Timer instruction, the Timer was enabled from the beginning even though the both contacts were off.


May/29/2009 - Version 1.10

- Supported new Analog CPU modules.
- Added the Battery Backup Setup dialog for the Analog CPU modules.
- Added the Calendar/Clock Setup dialog for the Analog CPU modules.
- Added the Com Port 3 Setup dialog for the Analog CPU modules.
- Improved the CPU Built-in I/O Setup dialog to support the Analog CPU modules.
- Added the Text View.
- Added the ASCII data type.
- Supported 2400 and 4800 bps on Com Port 2 and 3.
- Added the new System Data Registers to store the no communication time period on the Com Ports. (SD41, SD51 and SD61).
- Added the two Fill Down buttons to the Drum instruction.
- Improved the Copy instruction (Single Copy mode) to support the Pointer addressing as the Destination parameter.
- Improved the Receive instruction (ASCII mode) to store the length of the received text message.
- Improved the Send instruction (ASCII mode) to embed the ASCII codes and Memory Addresses in the text message.

Oct/15/2008 - Original Release CLICK PLC Programming Software Version 1.00


Part 4: Known Issues

Issue #1. Screen DPI settings: It is recommended that when using CLICK PLC Programming Software, the DPI setting should be one of the followings:
	 72 dpi (75%)
	 96 dpi (100%)
	120 dpi (125%)
	144 dpi (150%)
	192 dpi (200%)

Failure to use the correct DPI setting will cause text in a project to display incorrectly.

Issue #2. USB-to-Serial Drivers: It is recommended that you disconnect any USB devices except the mouse and keyboard during installation. Some USB devices can interfere with the installation and uninstallation of the Koyo USB-to-serial driver.

Please contact us with any other issues that you might find via fax at 1-770-886-3199 or e-mail inquiry at http://support.automationdirect.com/techinquiry.html


Part 5: Documentation and Help File Changes

Please contact us with any corrections, enhancements, or changes that you would like to see in the documentation or help file via fax at 1-770-886-3199 or e-mail inquiry at http://support.automationdirect.com/techinquiry.html


Part 6: Known Problems and Conditions

If you cannot install the software on your PC, check to make sure that your computer is running a compatible operating system: CLICK PLC Programming Software runs on the following Windows operating systems: Windows Vista(32bit)/ XP Pro/XP Home/2000 with SP4.

Please report any other problems to Automationdirect via http://support.automationdirect.com/techinquiry.html  or by calling technical support at 1-770-844-4200.


Part 7: Uninstalling of CLICK PLC Programming Software

It is very important that before uninstalling the software that you make a backup of any important project or library files.


Part 8: Technical Support Procedures and Contact Information

Here are some options if you need technical assistance:

1. You may find the information you need on our web site at http://support.automationdirect.com/

2. You can send us an e-mail inquiry at http://support.automationdirect.com/techinquiry.html

3. You can fax the information to us at 1-770-886-3199 any time of day.

4. You can access our AutomationDirect Customer Forum at http://forum.automationdirect.com/

5. You may also call our Technical Support Team from 9 AM to 6 PM EST Monday through Friday.

Please provide your software version when requesting technical support. The software title bar displays the software version number.

------------------------------------------------------------------------------------
Copyright (C) 2008 - 2013 AutomationDirect and KOYO ELECTRONICS INDUSTRIES CO., LTD.
and WinSystem Co., Ltd. All Rights Reserved.
