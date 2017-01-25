# link_handler
dmenu/rofi based link handler, which gives option to open link with... (link grabed from primary/clipboard)


![image](https://github.com/Docbroke/link_handler/blob/master/image.jpg)


USE: put lariza- external-handler in your path and make it executable.

input `chromium` in rofi field, to open your link (in clipboard) with chromium.

If you are on low bandwidth connection you can also put w3mpv and w3ytdl in your path (execuatable) to open/download videos in lower resolution

copy any link, open lariza-external-handler and choose option of open the link with, you can choose from give option or write your own for example input "chromium" to open link with chromium.

If you are using lariza, you can hit `alt+x` to open page url with lariza-external-handler

DEPENDS on: curl, wget, mpv, youtube-dl

NOTE: lariza-external-handler is specifically created for https://github.com/vain/lariza, (new upcoming feature of lariza allows external program to open url with, currently this feature is available in dev-external-handler branch)
