# Download: Simple utility to identify duplicate photos.

**Program name:**

## Duplicate Picture Finder 1.1

  
**Thumbshot:** ![](http://www.freewarefiles.com/screenshot/dup_pic_fndr11_md.jpg)   
  
**Download link:** [Download Simple utility to identify duplicate photos.](http://freesoftwares.boysofts.com/Duplicate-Picture-Finder_program_55063.html)  
  


**Publisher's Description**  
  


The Duplicate Picture Finder is a small utility which is designed to do exactly what it says on the tin. 

The Duplicate Picture Finder (DPF) is entirely free (as in costs nothing) and can be freely distributed as long as the ReadMe.htm file goes along with it. 

**Instructions**

When given a valid source folder DPF will list the extensions of all files in that folder and all its sub-folders.

You can then choose which file types to process.

When satisfied, click the "Process" button to identify the unique files in the source folder and COPY them to the target folder. This will eliminate all your duplicate pictures and leave you with a unique set that can be archived off to DVD or wherever. 

The DPF will ONLY read the files in the source folders. It will NOT intentionally write to them, delete them, or change them in any way. 

Each file type is classified and written to a separate folder within the target folder. The only two classifications are "Photo" and "Other". 

Each file is written to a sub folder hierarchy based on the fileA's creation date. If a file already exists of the same size, creation date and name, but with a different time, then a new one will be created with a suffix to distinguish it. 

###  Caveats 

The DPF is NOT infallible. It can only go so far. The algorithm used to identify duplicates is extremely simple. Each file name found is sorted (regardless of its folder name) in order of the 

  * File length (in bytes) 
  * The EXIF Date/Time taken. If the file is not a photo or the EXIF data canA't be read then the last time the file was written to is used, which "usually" equates to its creation date and time. 
  * The name of the file. 

One of each unique file is then copied into a target folder hierarchy based on the creation date. If, like me, you have the habit of copying images on your hard drive into various different places then this algorithm should spot the duplicates. If there is no readable EXIF data, or you process any of the images in any way so as to alter the last write date and time, then it wonA't spot them as duplicates. If the creation date is the same on two files of the same name and size, but the time is different then the DPF will store them in the same target folder. It has enough sense to NOT overwrite one with the other, just in case they arenA't the same image. 

The DPF has very little error checking. It will fail inelegantly if it cannot read any of the source data, or cannot write to the target folder. Hopefully, the operating system will do its job properly and will not damage the file being read at the time. Because of this, do NOT point it at the root of a drive. Copy your images into a specifically created folder instead. 

**There is no warranty with this program AT ALL. You use it entirely at your own risk and there is no comeback if it damages any of your data or hardware. If, like me, you regard each and every image as extremely valuable, it makes sense to only work with copies of your data. That way, if anything goes wrong, nothing gets damaged.**

I have written this to be extremely simple, but it works quite well and has been tested on my 31GB collection of 15,000 odd images. The result was 18GB of unique files. There is no installer. You just copy the .exe file, exe.config file and ReadMe.htm to a convenient folder and run it. 

I hope you enjoy it and that it does what you need. 

The program and its content are copyright MTBGG Systems Ltd 2010. 

Feedback and bug reports gratefully received. Please [contact us](http://www.mtbgg.co.uk/contactus.htm)

  
  
Screenshot: ![](http://www.freewarefiles.com/screenshot/dup_pic_fndr11.jpg)   
**For more freeware softwares visit [Freeware software downloads.](http://freesoftwares.boysofts.com/)**   
**And [Free softwares and php script downloads.](http://www.boysofts.com/)**
