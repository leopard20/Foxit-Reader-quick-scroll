# Foxit Reader quick scroll
Use the side mouse buttons (6+ button mouse) as page up and down when using Foxit Reader.
_____________

Not anything fancy. Pretty much anyone could do this. I've been using this for quite some time now but recently a friend of mine asked me for something similar. So I figured it might be of use to other people as well.

# Description:
I prefer to use the side buttons of my mouse as PageUp/PageDown to faster scroll through a PDF file. But I didn't want to modify the file FoxitReader.exe to acheive this. So instead I replaced the program FoxitUpdate.exe (because it runs on every launch, and I don't use auto updaters anyway) with this one. 

# **Features:**
1. Runs automatically when you open a PDF file.
2. The original button functions are restored if Foxit Reader is not on top (e.g. in Explorer the side buttons still function as Back/Forward).
3. The script closes automatically when you close Foxit Reader.

So far, this seems to be compatible with FoxitReader 9.0.x up to 9.5.0.x (latest as of now).

To use this, you need to install AutoHotkey first. https://www.autohotkey.com/
Note that the .ahk format must be registered as an executable format in Windows shell. This is done automatically if you use the AutoHotkey installer (as opposed to a 'portable' format or something)

# **How to install:**
1. Download the file PDF.ahk (autohotkey script) and place it in the root of your C drive. Alternatively, you can modify the CPP file and change the path to the autohotkey script.
2. Compile the CPP file to get FoxitUpdater.exe. You can use any CPP compiler (even simple IDEs such as DevCPP and CodeBlocks work). Alternatively, use the attached exe file.
3. Replace the file FoxitUpdater.exe in the FoxitReader's installation directory with the modified file.
4. Make sure the online features in FoxitReader are not disabled. (uncheck "Disable all features that requrie internet connection" in Preferences -> General)
