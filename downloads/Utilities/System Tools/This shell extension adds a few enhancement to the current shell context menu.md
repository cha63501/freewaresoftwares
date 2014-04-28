# Download: This shell extension adds a few enhancement to the current shell context menu.

**Program name:**

## HShellExtPack_StdAlone v0.3.0

  
**Thumbshot:** ![](http://www.freewarefiles.com/screenshot/HShellExtstnd_md.gif)   
  
**Download link:** [Download This shell extension adds a few enhancement to the current shell context menu.](http://freesoftwares.boysofts.com/HShellExtPackStdAlone-V_program_12071.html)  
  


**Publisher's Description**  
  


This little shell extension adds a few enhancement to the current shell context menu. Version postfixed with A'_StdAloneA' no requires runtime libraries (RTL50.BPL and VCL50.BPL)  
In this version these are the newly added functions. 

  * Menu A'**Launch Safer...**A'  
This function was inspired by the tool [DropMyRights](http://msdn.microsoft.com/security/securecode/columns/default.aspx?10=pull=/library/en-us/dncode/html/secure11152004.asp) by Michael Howard. If you are using windows as Administrator (not recomendded) then you can launching programs or itA's associated handler via HShellExtPack in a lower privileged context. (this way e.g. your browser and mailer would have less chance to run unwanted content of mails or web pages)  
The following sub menu items added. 
    * A'**Normal**A'  
Means run the application as a normal user. 
    * A'**Constrained**A'  
Means run the application as a constrained user. 
    * A'**Untrusted**A'  
Means run the application as an untrusted user. Chances are, this will cause some applications to fail. 
You can find a detailed description of the different run levels [here](http://msdn.microsoft.com/security/securecode/columns/default.aspx?10=pull=/library/en-us/dncode/html/secure11152004.asp). 
  * Menu A'**Launch At Priority...**A'  
You can launch a program or itA's associated handler at a desired start priority level. (Currently only extensions in PATHEXT environment variable can be started at a higher priority level, but no limitation on starting at a lower priority level.) 
Currently only single file selection works. (The context menu will NOT contain menu items of HShellExtPack if you selected more than one file!)  


  * v 0.1.0 
First release 
  * v 0.1.1 
\- Bug corrected, QueryContextMenu now filtering out more events that should not be handled by a user shell extension.  
\- Lunch -> Changed Launch :((( 
  * v 0.2.0 
\- Unicode support added  
\- handled extension types added/corrected  
\- lnk extension handling corrected  
\- directoy background handling added  
\- drive handling added  
\- launching directory handler failed, because of a bug in filename parsing 
  * v 0.2.1 
\- launching directory handler might have failed, because of PathIsDirectory does not handle quoted file path names 
  * v 0.3.0 
\- added launcher.exe instead of calling cmd for starting not A'runableA' files (files that extension not in PATHEXT environment variable)  
\- there is no limitation on starting a file at a given priority level  
\- enchanced error reporting in case of file starting error  
\- program stays more responsive while launching (e.g a long lasting DDE start could lock the program for which the context menu shown, thankA's for Valery Pryamikov for pointing out that using MsgWaitForMultipleObjects is much more effective)  
\- used BCB5 for building  
\- install.bat corrected 

  
  
Screenshot: ![](http://www.freewarefiles.com/screenshot/HShellExtstnd.gif)   
**For more freeware softwares visit [Freeware software downloads.](http://freesoftwares.boysofts.com/)**   
**And [Free softwares and php script downloads.](http://www.boysofts.com/)**
