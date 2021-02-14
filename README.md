<!--![](page-gif.gif)-->
<!--![](page-gif-2.gif)-->
<!--![](page-gif-3.gif)-->
![](page-gif-4.gif)

<!--
I found that the ZamZar MKV to GIF converter works best to preserve page color:
https://www.zamzar.com/convert/mkv-to-gif/
-->

### Hi 👋
I'm just experimenting with my main page right now don't take it too seriously pls


<!--854x366 - Probably the biggest image I can use here that will take up the whole width of the README-->
<!--
ffmpeg -i file.avi -vf "scale=1080:-1,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse" out.gif
This keeps the GIF under GitHub's filesize limit, fixes color issues and "speckling", and executes in under 6 seconds
-->
