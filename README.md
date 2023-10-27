# **RealtimeTranslation**

# Getting Started
Below is a list of what you need to set up:
1. Step 1: Create a new script at https://script.google.com/
- Delete the default code
- paste code & deploy the code with Web app (Who has access: anyone)
- Save your Deployment ID (xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)
2. Step 2: Copy the following URL: 
```
https://sayonari.coresv.com/ninshikiChan/text.html?recog=id&trans=en&bgcolor=green&size=20&weight=900&color=white&st_color=blue&st_width=3&v_align=bottom&gas_key=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)
```
- replace the gas_key=xxxx with the deployment id you saved
3. Add to your OBS
- Select source
- Choose windows capture
- add filter chroma key
- done

# HOW TO CHANGE SETTINGS
Speech recognition language        : recog = id
Translation destination language   : trans = en
font                               : Meiryo
Background color                   : bgcolor = green (specify by color name)
font size                          : size = 20 (specified by pt)
Character thickness                : weight 900 (specified by 100-900)
Letter color                       : color= white
Border color                       : st_color = blue
Border thickness                   : st_width = 3
Character position                 : v_align=bottom (superscript: top, subscript: bottom)

Color specifications are color names such as "red" and "light green". Please specify with.
Color name: https://www.colordic.org/
