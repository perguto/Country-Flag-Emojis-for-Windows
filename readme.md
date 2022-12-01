# Country Flag Emojis for Windows

Get country flags like 🇺🇸 🇬🇧 🇪🇸 🇲🇽 🇵🇹 🇧🇷 🇫🇷 🇩🇪 🇯🇵 🇨🇳 🇰🇷 🇮🇳 to display properly on windows instead of just seeing placeholders like `US`, `GB`, `ES`!

The file [google_emoji_font_for_windows.ttf](https://github.com/perguto/Country-Flag-Emojis-for-Windows/blob/master/google_emoji_font_for_windows.ttf?raw=true) is all you need.
Installing it overwrites the Windows Emoji font and replaces it with Google's Emoji font (the same one as on Android), which has all country flags and looks better anyway.
(Make a copy of the original Windows emoji font [`C:\Windows\Fonts\seguiemj.ttf`](C:\Windows\Fonts\seguiemj.ttf), so you can always revert.)

Restart your computer to make the new font appear everywhere!

## Detailed Instructions

(This is just the same steps as described above, but in more detail)

(Tutorial Video: https://youtu.be/jrs3Y7SIQL0)

1. Open the windows fonts folder by typing `C:\Windows\Fonts` into the explorer address bar. Find the font `Segoe UI Emoji Regular` copy it and save it as a backup in a different folder.

![](./screenshots/backup_font.png)

2. [Click here to download `google_emoji_font_for_windows.ttf`](https://github.com/perguto/Country-Flag-Emojis-for-Windows/blob/master/google_emoji_font_for_windows.ttf?raw=true).

3. Open in another window the folder where you saved `google_emoji_font_for_windows.ttf` and drag it into the font folder.

<p float="left">
<img src="./screenshots/move_font.png" width="53.6%" />
&nbsp; &nbsp; &nbsp; &nbsp;
<img src="./screenshots/copy_font.png" width="36.4%" style="align: right" />
</p>

4. You're asked if you want to replace the Segoe UI Emoji font. Choose yes.

![](./screenshots/replace_font.png)

5. You're done! Restart your computer to make the new emojis appear.


## How I did it

Google's Emoji Font
[Noto Color Emoji](https://fonts.google.com/download?family=Noto%20Color%20Emoji) is free for anyone to download and modify. For Windows, you need their converted version [Noto Color Emoji WindowsCompatible](./resources/NotoColorEmoji_WindowsCompatible.ttf) as the original font uses Google's own extension of the ttf font format for colors, which differs from Microsoft's.

All I did was changing the font names to that of Microsoft's emoji font "Segoe UI Emoji"

I did this with `ttx`, a program belonging to the fonttools suite.

## Other Emoji Fonts

Apparently, it's also possible to get Twitter's emojis on Windows:

[https://fonts.google.com/download?family=Noto%20Color%20Emoji](https://github.com/13rac1/twemoji-color-font#install-on-windows) 
