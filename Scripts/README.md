# Music applet usage #

Copy the music applet in your script config directory and make it executable.
Create in your beshell config file one entry for each block you want to use. Possible choise are:

- mpc (show track info like artist, album etc.)
- command (show the music player control button)
- cover **EXPERIMENTAL** (show the cover of the album)
- progress (show a simply progressbar)
- time (show the current time and the total time for the current track)

cover images are locally stored, i'd use the default path of cantata music player (e.g. $HOME/music/$ARTIST/$ALBUM/cover.jpg) so to actually make it work you have to use cantata and set it to save locally the cover images or change the path at your discrection.
  
Progressbar is a very nasty workaround to create a progessbar without using java or similia. The lenght is set by using "-" in the PRG variable of the script and setting it transparent on your .css file. The height is set by changing the applet max-height on your .css file. You can also change the color of the progressbar by modify STOPB, STOPF and STOPL variables into the script.
