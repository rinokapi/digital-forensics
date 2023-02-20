# Digital Forensics
As part of a course I've been taking, I recorded my screen while I worked with these tools, and I wanted to share the video with you all as an example of my experience and skills in this area. The tools I used include:

- Windows OS: systeminfo.exe, date & time, doskey, net, netstat
- Process Explorer
- Event Log Explorer
- Linux OS: uname, lshw, w, last, netstat, ifconfig, lsof, lsmod, aureport, ausearch, arp, ps, readelf
- FTK Imager
- Helix Tool
- Autopsy
- Foremost
- Volatility

Through this project, I was able to gain hands-on experience in using these tools to conduct digital investigations and extract evidence from various digital devices. I also learned a lot about the importance of proper documentation and preservation of evidence in the digital forensics process.

# Table of contents

- [Collecting Volatile Information in a Windows System](#Collecting-Volatile-Information-in-a-Windows-System)
- [Extracting Volatile Information Using Process Explorer](#Extracting-Volatile-Information-Using-Process-Explorer)
- [Viewing, Monitoring, and Analyzing Events in a Windows System](#Viewing-Monitoring-and-Analyzing-Events-in-a-Windows-System)
- [Viewing, Monitoring, and Analyzing Events in a Windows System](#Viewing-Monitoring-and-Analyzing-Events-in-a-Windows-System)
- [Acquiring Volatile Data in a Linux System](#Acquiring-Volatile-Data-in-a-Linux-System)
- [Creating a Disk Image File of a Hard Disk Partition Using the R-Drive Image](#Creating-a-Disk-Image-File-of-a-Hard-Disk-Partition-Using-the-R-Drive-Image)
- [Creating a Disk Image File of a Hard Disk Partition Using the R-Drive Image](#Creating-a-Disk-Image-File-of-a-Hard-Disk-Partition-Using-the-R-Drive-Image)
- [Creating a Disk Image using FTK Imager](#Creating-a-Disk-Image-using-FTK-Imager)
- [Discovering and Extracting Hidden Forensic Material on Computers Using OSForensics](#Discovering-and-Extracting-Hidden-Forensic-Material-on-Computers-Using-OSForensics)
- [Performing a Computer Forensic Investigation Using the Helix Tool](#Performing-a-Computer-Forensic-Investigation-Using-the-Helix-Tool)
- [Analyzing Nonvolatile Data in Linux System](#Analyzing-Nonvolatile-Data-in-Linux-System)
- [Data Carving from a Disk Image using Foremost](#Data-Carving-from-a-Disk-Image-using-Foremost)

Module 03 Forensic Readiness and First Response
## Collecting Volatile Information in a Windows System
Volatile memory, in contrast to non-volatile memory, is computer memory that requires power to maintain the stored information; it retains its contents while powered on, but when the power is interrupted, stored data are quickly lost. Volatile memory has several uses, including as main memory. In addition to usually being faster than forms of mass storage, such as a hard disk drive, volatility can protect sensitive information, as it becomes unavailable upon power-down. Most of a computer’s general-purpose random-access memory (RAM) is volatile.
Lab Objectives

This lab demonstrates how to collect volatile information from a live system running the Windows operating system.

## Extracting Volatile Information Using Process Explorer
The Process Explorer program can be used to check if a given process is malicious or suspicious. Process Explorer shows information about opened or loaded handles and DLLs. The Process Explorer display consists of two sub-windows. The top window always shows a list of the currently active processes, including the names of their owner accounts, whereas the information displayed in the bottom window depends on Process Explorer’s mode. If it is in handle mode, you will see the handles opened by the process selected in the top window. If Process Explorer is in DLL mode, you will see the DLLs and memory-mapped files that the process has loaded.
Lab Objectives

This lab demonstrates how to extract volatile information from running processes using Process Explorer.

## Viewing, Monitoring, and Analyzing Events in a Windows System
Event Log Explorer works with both local and remote event logs, as well as with event log files in EVT and EVTX format. It can read event log files directly (without Event Log API), allowing you to access even damaged log files. Event Log Explorer lists computers, event logs, and log files in the object tree. You can open or manage any event log in the tree with just a click.
## Viewing, Monitoring, and Analyzing Events in a Windows System
Event Log Explorer works with both local and remote event logs, as well as with event log files in EVT and EVTX format. It can read event log files directly (without Event Log API), allowing you to access even damaged log files. Event Log Explorer lists computers, event logs, and log files in the object tree. You can open or manage any event log in the tree with just a click.

## Acquiring Volatile Data in a Linux System
Most of Linux systems store data related to the current session in a temporary form across registries, cache, and RAM. These data are easily lost when the user switches the system off, resulting in loss of the session information. Therefore, incident responders need to prioritize extracting this information.
Lab Objectives

The objective of this lab is to help incident responders learn how to gather volatile data from a live Linux system and analyze it to find traces of attack to define the type, impact points, and path as well as the perpetrator.

## Creating a Disk Image File of a Hard Disk Partition Using the R-Drive Image
R-Drive Image is used to create disk image files for backup or duplication purposes. R-Drive Image recovers the images on the original disks and partitions and also on a hard drive's free space on the fly. A full disk can be copied to another one.
## Creating a Disk Image File of a Hard Disk Partition Using the R-Drive Image
R-Drive Image is used to create disk image files for backup or duplication purposes. R-Drive Image recovers the images on the original disks and partitions and also on a hard drive's free space on the fly. A full disk can be copied to another one.

## Creating a Disk Image using FTK Imager
FTK Imager is a data preview and imaging tool that enables you to analyze files and folders on local hard drives, CDs/DVDs, and network drives, as well as examining the content of forensic images or memory dumps. FTK Imager can also create MD5 or SHA1 hashes of files, review and recover files deleted from the Recycle Bin, export files and folders from forensic images to disk, and mount a forensic image to view its contents in Windows Explorer.
Lab Objectives

The objective of this lab is help incident responders learn how to create a disk image using FTK Imager.

## Discovering and Extracting Hidden Forensic Material on Computers Using OSForensics
OSForensics is a computer forensics application for locating and analyzing digital evidence found in computer systems and digital storage devices. Searching for evidence in a system is like searching for a needle in a haystack—unless you know what to look for and where. To simplify matters, you can use automated tools to uncover otherwise hidden files and potential evidence. A system stores event logs along with the identity of the programs used to perform every task on the computer. An incident handler should be able to locate and differentiate data and evidence. This lab will help you learn to use using OSForensics tools to find evidence hidden in large amounts of data.
Lab Objectives

The objective of this lab is to help incident responders learn how to investigate a suspect’s computer to locate evidence of a crime. In this lab, you will learn how to use the OSForensics tool to discover and extract forensic evidence on computers.

## Performing a Computer Forensic Investigation Using the Helix Tool
Helix is an easy-to-use cybersecurity solution that can be integrated into your network, giving you visibility across your entire infrastructure and revealing malicious activities such as internet abuse, data sharing violations, and harassment. It also allows incident handlers to isolate and respond to incidents or threats quickly and without user detection through a central administration tool. It allows responders to quickly detect, identify, analyze, preserve, and report on a range of activity, giving incident handlers the evidence needed to reveal the truth and protect an organization.
Lab Objectives

The objective of this lab is to teach incident handlers how to investigate a computer-based crime using the Helix tool.

## Analyzing Nonvolatile Data in Linux System
Autopsy is a digital forensics platform and graphical interface toused with The Sleuth Kit and other digital forensics tools. This tool helps incident handlers to view the file system, retrieve deleted data, perform timeline analysis, and web artifacts during an incident response effort.
Lab Objectives

The objective of this lab is to help incident handlers learn how to analyze an image of a Linux hard disk and gather required evidence from it using Autopsy.

 ## Data Carving from a Disk Image using Foremost
Foremost is a console program to recover files based on their headers, footers, and internal data structures. This process is commonly referred to as data carving. Foremost can work on image files, such as those generated by dd, Safeback, and Encase, or directly on a drive. The headers and footers can be specified by a configuration file or you can use command line switches to specify built-in file types. These built-in types look at the data structures of a given file format, allowing for a faster and more reliable recovery.
Lab Objectives

The objective of this lab is to help incident handlers understand how to extract files of different formats from a disk image using Foremost.
