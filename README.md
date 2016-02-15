# ubuntu-skylake-i915-video-fix<br />

Skylake (intel hd530) video <br />

The problem :<br />
 * skype video calls become unusable.<br />
 * blue lines<br />
 * vlc, openshot, skype video always on top<br />
 * video does not resizable<br />
 * etc..<br />
 

Tested on:  <br />
     * ubuntu wily (15.10)  <br />

## installation
* Copy 20-intel.conf from repository to /usr/share/X11/xorg.conf.d/20-intel.conf
* Restart Xserver (logout/login)


## Kernel - 4.3.x issues
 * Very unstable driver when using opengl or playing games.
 
## Kernel - 4.4.x issues
 * Loading /lib/firmware/i915/skl_guc* firemware poblem
 * Monitor blinks at kernel boot time


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/linuxenko/ubuntu-skylake-i915-video-fix/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

