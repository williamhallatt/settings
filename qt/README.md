qtsettings
==========

My preferred Qt Creator theme, key mappings and code style.

## Qt Creator Zen Burn Theme

I cannot recall where I first encountered the Zen Burn theme (it might have been for vim), but it has been my favourite for quite a while now. 

This is my adaptation of it for Qt Creator.

![Alt text](zenburn.png?raw=true "Zen Burn") 

The QML bits need some work, so if you you make tweaks that you think are awesome, please feel free to share :)

### How to change the color scheme in Qt Creator

1. Copy "zenburn.xml" to:

Linux - /path/to/QtCreator/share/qtcreator/styles  (you might have to create the styles directory)

Windows - C:\Users\\**yourUserName**\AppData\Roaming\QtProject\qtcreator\styles

2. In "Qt Creator", go to Tools -> Options -> Text Editor -> Font & Colors
3. Under "Color Scheme", scroll down and select the new color scheme (ZenBurn in this case).
4. Press "Apply" or "OK"
5. You're done!

### Code Style

Code styles are very easy to tweak, but you can also import presets:

1. In "Qt Creator", go to Tools -> Options -> C++ -> Code Style
2. Hit the "Import" button, navigate to your settings file and select it
3. Press "Apply" or "OK"

### Key Mappings

Similar to code styles, Key Mappings can also be imported:

1. In "Qt Creator", go to Tools -> Options -> Environment -> Keyboard
2. Hit the "Import" button, navigate to your mappings file and select it
3. Press "Apply" or "OK"

