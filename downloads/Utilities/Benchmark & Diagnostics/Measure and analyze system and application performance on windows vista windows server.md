# Download: Measure and analyze system and application performance on Windows Vista, Windows Server 2008, and later.

**Program name:**

## Windows Performance Tools Kit 4.1.1

  
**Thumbshot:** ![](http://www.freewarefiles.com/screenshot/nopic.gif)   
  
**Download link:** [Download Measure and analyze system and application performance on Windows Vista, Windows Server 2008, and later.](http://freesoftwares.boysofts.com/Windows-Performance-Tools-Kit_program_39763.html)  
  


**Publisher's Description**  
  


The Windows Performance Tools (WPT) Kit contains performance analysis tools that are new to the Windows SDK for Windows Server 2008 and .NET Framework 3.5. The WPT Kit is useful to a broad audience, including system builders, hardware manufacturers, driver developers, and general application developers. These tools are designed for measuring and analyzing system and application performance on Windows Vista, Windows Server 2008, and later. 

The tools currently include an xperf trace capture tool, an xperfview visualization tool (also known as Performance Analyzer), and an xbootmgr boot trace capture tool. The tools are designed for the analysis of a wide range of performance problems including application start times, boot issues, deferred procedure calls and interrupt activity (DPCs and ISRs), system responsiveness issues, application resource usage, and interrupt storms. The MSIs containing these tools are available in the SDK bin directory (one per architecture).

The tools are built on top of the Event Tracing for Windows (ETW) infrastructure. ETW enables Windows and applications to efficiently generate events. Events can be enabled and disabled at any time without requiring system or process restarts. ETW collects requested kernel events and saves them to one or more files that are referred to as "trace files" or "traces."

These kernel events provide extensive details about the operation of the system. Some of the most important and useful kernel events that are available for capture and analysis are context switches, interrupts, DPCs, process and thread creation and destruction, disk I/Os, hard faults, processor P-state transitions, registry operations, and many others.

The tools use a trace capture and analysis model that follows this general flow:

  1. ETW tracing is enabled by using xperf. 
  2. Operations are performed. 
  3. ETW tracing is disabled by using xperf, and the data is saved to an ETL trace file. 
  4. Trace files can then be further processed by using xperf or viewed by using Performance Analyzer (xperfview). 
Traces can be processed on the machine on which they were taken or copied to another machine for analysis (including cross-architecture). Everything required for analysis is stored in the trace file. 

One of the great features of ETW, supported in WPT, is the support of symbol decoding, sample profiling, and capture of call stacks on kernel events. These features provide very detailed views into the system operation. WPT also supports automated testing. Specifically, xperf is designed for scripting from the command line and can be employed in automated performance gating infrastructures. xperf can also dump the trace data to an ANSI text file, which allows you to write your own trace processing tools that can look for performance problems and regressions from previous tests.

**WhatA's New in version 4.1.1:**

  * Windows Performance Analyzer does not start when double-clicking an ETL file. 
  * Windows Performance Analyzer does not perform power state transition analysis. 

  
  
Screenshot: ![](http://www.freewarefiles.com/screenshot/nopic.gif)   
**For more freeware softwares visit [Freeware software downloads.](http://freesoftwares.boysofts.com/)**   
**And [Free softwares and php script downloads.](http://www.boysofts.com/)**
