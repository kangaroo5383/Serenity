# Serenity
An Xcode theme for people who needs their colors to match.  Everything was built on top of how well #8ED6FF and #26272C go together.

![image](https://user-images.githubusercontent.com/34344/44005891-aa93224c-9e2f-11e8-87eb-19266938b3c7.png)

To install a theme, copy the .dvtcolortheme file to:
`  ~/Library/Developer/Xcode/UserData/FontAndColorThemes`

(If FontAndColorthemes directory doesn't exist, just create it and place the file inside.)

Restart XCode, then you should see it in the list of available themes in the XCode preferences.


Detailed directions for creating the theme file.  Alternatively, just create one in Xcode -> Preferences -> Fonts & Colors, then replace the content.

#create folder
$ mkdir ~/Library/Developer/Xcode/UserData/FontAndColorThemes
#copy color theme file to this new folder
$ cp color_theme.dvtcolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes
#make file executable
$ chmod +x ~/Library/Developer/Xcode/UserData/FontAndColorThemes/color_theme.dvtcolortheme
