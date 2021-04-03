# MKV-Chapter-Maker
Auto generate MKV chapters using FFmpeg BlackDetect filter   
Works best with TV Shows that have had commercials stripped out and leave a noticable black screen.   
1/2 hours shows typically produce 4 or 5 chapters marks. 1 hours shows maybe 8 or 9 chapters.   
   
   
Example without any options that uses the default blackdetect seconds value (.5)   
```FFchap "Blue Bloods - S06E02 - Absolute Power.mkv"```   
   
   Example using the -s option for custom blackdetect value   
   ```FFchap -s 1.5 "Blue Bloods - S06E02 - Absolute Power.mkv"```   
   
mkvpropedit & ffmpeg are required   
   
   If you have chapters in the mkv file they will be replaced.   
   Target files are NOT re-encoded and mkvpropedit is instantaneous.   
   720 files are processed resonably quick <1 min 1080p is noticeably longer.   
   
