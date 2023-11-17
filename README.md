# LibreCAD_Traditional-Chinese_Font
 Use ttf2lff tool to convert NotoSansTC-Thin.ttf to notosantc-thin.lff

# Install font
```
 Unzip notosanstc-thin.zip
 Copy notosantc-thin.lff to C:\Program Files (x86)\LibreCAD\resources\fonts
```

# Tip
 Set the Word Attributes Pen Width 0.13mm or up to you

# ttf2lff command
```
 Usage: ttf2lff <options> <ttf file> <lff file>
   ttf file: An existing True Type Font file
   lff file: The LFF font file to create
 options are:
   -n nodes                 Number of nodes for quadratic and cubic splines (int)
   -a author                Author of the font. Preferably full name and e-mail address
   -l letter spacing        Letter spacing (float)
   -w word spacing          Word spacing (float)
   -f line spacing factor   Default is 1.0 (float)
   -d precision             Number of decimal digits (int)
   -L license               license of the font.
```