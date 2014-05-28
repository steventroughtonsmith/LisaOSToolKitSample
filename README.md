SAMPLETK - A SIMPLE LISA TOOLKIT QUICKDRAW PROGRAM
=============

Result of a day of learning about LisaOS and ToolKit app development. This is a combination of the first 'Boxer' lab from Lisa ToolKit Self-Paced Training, and the QuickDraw sample code included with Workshop 3.0.

Due to the complexity of converting file formats to/from Lisa, I imagine you will have to manually type this rather than transfer it from a Mac disk using MacCom. LisaEm will let you paste large sections of text as keystrokes, so that makes input pretty easy.

From the Lisa Workshop main prompt, assuming you have the ToolKit SDK installed, run the following, where '41' is the ID you want to give the output tool.

```
<TK/Make(SampleTK,41)
```

NOTE
=============

LisaEm currently has issues linking Pascal code with IF statements. If running in an emulator, there are a couple of IF lines in U1SampleTK.TEXT you will want to comment out. See note in file.

WHAT IS TOOLKIT?
=============

ToolKit is the [unsupported] integrated API for writing LisaOS apps, similar to the native apps. To be contrasted with QuickPort, which is more of a wrapper.

ICON
=============

Use IconEdit to give the Tool an appropriate icon.

SCREENSHOT
=============

[![](https://lh5.googleusercontent.com/-ls79IdApyo4/U4ZTDIadJFI/AAAAAAAABRo/bA8UuLMV3GY/w1440-h728-no/phrase.png)](https://lh5.googleusercontent.com/-ls79IdApyo4/U4ZTDIadJFI/AAAAAAAABRo/bA8UuLMV3GY/w1440-h728-no/phrase.png)
