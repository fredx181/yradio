# yradio
Internet Radio Player  

**Update:** v0.0.6, added notification icon, shows popup (on songtitle change) and right-click menu    

Much inspired by PMRP from misko_2083, see:  
http://murga-linux.com/puppy/viewtopic.php?p=963382#963382  
Took as a base GUI concept for this from: Victor Ananjevsky's (yad author) "find frontend" example from here:  
https://sourceforge.net/p/yad-dialog/wiki/Frontend%20for%20find%2Bgrep%20commands/?limit=50  

Depends on **yad** (version 0.35 or higher), **xdotool**, and **mplayer** installed.  
**Update:** v0.0.5 and 0.0.6 depends on yad version 0.37 or higher.   

Search option has access to large database from "RadioSure" (commercial M$ app) converted to use with this app.
(need to click 'Update Index' first)    

**Options:**
- Load a Category or do a search
- Add (from Category list or search results) or remove to/from 'Favorites'      
- Save search results to a new 'Category'    
- Ability to rip the stream (requires "streamripper" installed)    
  
Forum thread:  
http://murga-linux.com/puppy/viewtopic.php?p=986591#986591

**Installation:**
```    
git clone https://github.com/fredx181/yradio.git  
```   
Make 'yradio' bash script executable:  
```  
chmod +x yradio  
```  
And run 'yradio' from inside directory  
  
**Or:**    Download ZIP  https://github.com/fredx181/yradio/archive/master.zip  
Extract and run 'yradio' from 'yradio-master' directory  
  
![yradio](yradio_v0.0.6.png)  
