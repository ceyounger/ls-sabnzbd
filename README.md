# ls-sabnzbd
Patch for Linuxserver.io sabnzbd notifications

The wonderful team at Linuxserver.io created a SABNZBD image that I've used for a long time.  But somewhere notifications broke after the switch to python3.  It turns out the nzbget python module changed names or something or other, I dunno.  I did find out that simply adding the module to the container build fixed my issue.

I filed a issue request, but I'm not sure it's on the radar to fix since it's technically not broken.

I'm lazy, and don't want to fool around with it more than I need to, I just want my Discord notifications back.  :)  So here's a patched container that adds pynzbget to Linuxserver's image that will restore functionality until I can research if the inital problem has been fixed.

Enjoy!!
