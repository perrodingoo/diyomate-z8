# Radio #

Add your content here.


# Details #

Use _telnet_ (on your GNU/Linux Putty or Terminal or on MS Windows Putty):
  * go to radio station file _cd /usr/local/etc/RussiaRadio/scripts/mms\_radio.rss_ and open it using Vi command: _vi /usr/local/etc/RussiaRadio/scripts/mms\_radio.rss_ or _vi mms\_radio.rss_
  * Each radio station is described like this:
NAME Mystation 1
URL mms://217.168.64.61/BalticPlus-40K



&lt;script&gt;



itemTitleArray = pushBackStringArray(itemTitleArray, "Mystation 1");

focusiconArray = pushBackStringArray(focusiconArray, "image/check\_focus.jpg");

unfocusiconArray = pushBackStringArray(unfocusiconArray, "image/check\_unfocus.jpg");

itemLinkArray = pushBackStringArray(itemLinkArray, "mms://217.168.64.61/BalticPlus-40K");

itemSize = Add(itemSize, 1);
  * If you want to add custom station they might be described like on example.