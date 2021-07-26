# A Basic Gpredict .trsp Update
These are basic updates to the Gpredict ".trsp" files, which are the satellite transponder data files.
The updates address minor annoyances such as inconsistent naming, important selection location in the drop-down list, missing transponder files for satellites, etc.  

The NOAA-HRPT folder is for HRPT to be the first selection in "Radio Control" for NOAA-15, NOAA-18, and NOAA-19 for those that work with HRPT more often than APT.  
 
  
  
  
## Satellites to File Name List:  
#### Names are the satellites NORAD ID with '.trsp' (e.g. NOAA 15 is "25338.trsp").  
#### '~' denotes transponder file was created for that satellite.
  
##### WX:  
NOAA-15: 25338  
NOAA-18: 28654  
NOAA-19: 33591   

METEOR-M2: 40069  
METEOR-M2-2: 44387    

~GOES-16: 41866   
~GOES-17: 43226   
   

##### Ham:  
AO-7: 7530  
AO-73 (Funcube): 39444  
AO-91: 43017  
AO-92: 43137  
FO-29: 24278  
CO-58: 28895  


##### Sats that have good defaults:  
These are satellites I previously did updates to, but now no longer needed, because the default transponder files are the same as I would do.   
  
###### WX:  
METOP-A: 29499   
METOP-B: 38771   
METOP-C: 43689   

Fengyun-A: 32958   
Fengyun-B: 37214   
Fengyun-C: 39260   


###### Ham:
AO-95: 43770  
SO-50: 27607 
DIWATA 2B (PO-101): 43678  
UO-11: 14781 
  
## Where to put the files? 
These files are okay to use as drop and replace type files. You will need to do this after every transponder data update you do in Gpredict.   

Go to *C:\Users\(Username)\Gpredict\trsp*  
(As always, have a backup of this folder in case something were to go wrong.)  

After downloading and choosing what files you want to use, drop the files in the 'trsp' folder to replace the old ones and confirm the overwrite and your done!


## My comments about this Project
This project is more of me sharing minor annoyance fixes. However, this repo is the perfect way for making suggested file improvements and for new files to be added to the list.
The default transponder data is good and is updated all the time, but I prefer to organize it differently.
