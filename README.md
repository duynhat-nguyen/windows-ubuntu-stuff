# windows-ubuntu-stuff
This is to note my modifications to Windows and Ubuntu when using them

### 6:53 Feb 12, 2020
Changing Linux to use local time. 
I did change Windows to use UTC. However, I sign in my Google account on Chrome both Ubuntu and Windows and my Google Account keep "pending". 
https://help.ubuntu.com/community/UbuntuTime#Multiple_Boot_Systems_Time_Conflicts

### 14:51 Feb 27, 2020
Download YouTube Videos in terminal using youtube-dl command
https://itsfoss.com/download-youtube-linux/

### 20:51 Feb 29, 2020
Scale all *.png images in a folder to 1270x720  
```bash
!for f in *.png; do ffmpeg -i "$f" -vf scale=1280:720 "./xxx/${f%%.png}.png"; done  
```
https://superuser.com/questions/839751/resize-more-than-one-image-using-ffmpeg
