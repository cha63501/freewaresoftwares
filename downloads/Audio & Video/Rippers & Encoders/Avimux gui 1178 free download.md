# Download: AVIMux GUI 1.17.8

**Short description: **

## Easily convert audio and video files of various formats.

  
**Thumbshot: **![](http://www.freewarefiles.com/screenshot/avimuxgui_md.gif)   
  
**Download link:** [Download AVIMux GUI 1.17.8](http://freesoftwares.boysofts.com/AVIMux-GUI_program_22188.html)  
  

**Publisher's Description**  
  

Easily convert audio and video files of various formats.

**Supported input file types:**

  * AVI, MKV 
  * WAV, MPA/MP3, AC3, DTS, AAC, OGG/Vorbis 
  * SRT, SSA 

**Supported output formats:**

  * AVI, MKV 
  * raw (MPx, AC3, DTS...) 
  * ATDS-AAC, OGG/Vorbis 

**Features:**

  * supports Open-DML AVI files 
  * supports creating rec list 
  * join AVI/MKV files with SSA subtitles 
  * easy splitting 
  * handles MPx/AAC-in-AVI 
  * extracting most stream types 
  * repair files 
  * Mode 2 - Form 2 reading 
  * Vorbis-in-AVI reading 
  * real file type identification 

**What's New in version 1.17.8:**

**New:**

  * The CTextFile class is redone. Text files can now be handled in UTF-16 big and little endian (with BOM only), UTF 8 (with BOM only) and the local charset of your windows installation 
  * Added highlighting for streams that are default and for streams that AVI-Mux GUI cannot put into AVI files (this visual feature can be disabled) 
  * When creating XML files, now STL is used 
  * Matroska tags can be used to create several titles for one matroska stream. Note that this is, as far as I know, not yet supported by players or filters. 
  * The BitStream class is redone. Reading AAC audio is now faster. 
  * The widht and height of the settings window is increased if the right-bottom-most button is cropped. 
  * There is now a setting to enable, disable or leave unchanged the cleartype font setting 

**Fixed Bugs:**

* When opening Matroska files containing Vorbis audio streams, the vorbis audio streams' titles were not imported 
* A crash occurred when opening a matroska file containing Tags with no target 
* The windows size should not be restored correctly and on the correct screen when restarting AVI-Mux GUI 
* The delay setting was printed in the wrong place for A_MS/ACM audio tracks in matroska files 
* DTS streams with frames of 2012 bytes got a wrong duration because the PCMSampleCount header field was not used. This made the audio go out of sync 
* When the size estimation of a Vorbis audio track failed, a crash occurred 
* AC3 and DTS: The LFE channel was ignored. This caused incorrect channel information to be written in headers. This did not affect replay on most players, but I got a report that a Nero AVI file parser interpreted this difference between header and real stream data as a broken file. 
* AC3: Due to some rounding that (erroneously) occurred when reading AC3 audio files with 44.1 kHz, such streams were muxed incorrectly. 
* Nowadays, there is no long double anymore in Visual Studio. Due to this, when trying to write 80 bit floats into matroska file, a 64 bit float was written instead and padded with 2 zero bytes. This is fixed. IMPORTANT: 80 bit floats are no longer allowed in the matroska specification. 80 bit floats can only be selected when matroska v1/v2 enforcement is disabled. 
* the file name in the START command in scripts was converted to UTF-8, then it was interpreted as 8859-1 and again converted to UTF-8, which led to disrupted file names 
* a crash occurred when dropping an XML chapter file onto an edition in the chapter editor 

  
  
Screenshot: ![](http://www.freewarefiles.com/screenshot/avimuxgui.gif)  
**For more freeware softwares visit [Freeware software downloads.](http://freesoftwares.boysofts.com/)**   
**And [Free softwares and php script downloads.](http://www.boysofts.com/)**

