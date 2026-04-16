Do not check the releases. There are no releases. This is one of the rare times I'm asking you to check the master instead :)<br>
This is Definitions.Rpy For MPT (By A DDLC **D E V**) which is a modification to DDLC's files for making DDLC mods.<br>

## How to use Definitions.Rpy For MPT

Go to any file other than this one in the master and copy its contents into definitions.rpy of your mod, replacing everything that looks like this:<br>

image sayori 1 = im.Composite((960, 960), (0, 0), "sayori/1l.png", (0, 0), "sayori/1r.png", (0, 0), "sayori/a.png")<br>
image sayori 1a = im.Composite((960, 960), (0, 0), "sayori/1l.png", (0, 0), "sayori/1r.png", (0, 0), "sayori/a.png")<br>
image sayori 1b = im.Composite((960, 960), (0, 0), "sayori/1l.png", (0, 0), "sayori/1r.png", (0, 0), "sayori/b.png")<br>
image sayori 1c = im.Composite((960, 960), (0, 0), "sayori/1l.png", (0, 0), "sayori/1r.png", (0, 0), "sayori/c.png")<br>
...<br>
image monika g2:<br>
    block:<br>
        choice:<br>
            "monika/g2.png"<br>
        choice:<br>
            "monika/g3.png"<br>
        choice:<br>
            "monika/g4.png"<br>
    block:<br>
        choice:<br>
            pause 0.05<br>
        choice:<br>
            pause 0.1<br>
        choice:<br>
            pause 0.15<br>
        choice:<br>
            pause 0.2<br>
    repeat<br>

Replace it with one of the master files' full contents *(comments in the files are by Bronya-Rand because I used their DDLC template)*. Then, import Chronos' Mod Posing Tool (MPT) into the DDLC mod (https://drive.google.com/drive/folders/136KBThnImX3qABRlMO8YKykM5gtLI_6x) using this tutorial by EqualsM3rc: https://www.youtube.com/watch?v=v65X-Gj5g3s. MPT is required otherwise Ren'Py will either error out or simply not display the characters.<br>

**Why would I need to use this?** Because it lets you use the most 'common' MPT poses quickly and allows you to easily add more. Plus, it makes all expressions compatible with AAA (Autofocus-Automouth-Autozorder) and NBT (Natural Blinking Tool) so yay :)

## MAIN.txt

This is the original version of Definitions.Rpy For MPT, and the version I usually use for my DDLC mods. These are replications of the original DDLC expressions except for the following:<br>

### Changes

Yuri's original 3# pose got moved to 4#, and her original 4# pose got moved to 5# (same with 3b# > 4b# and 4b# > 5b#). This is to fit in with the other three girls.<br>

The 1, 2, 3, 4, and 5 poses (and 11, 21, 31, 41, 51, 12, 42 for Natsuki) with the numbers by themselves have been removed.<br>

### Additions

**Sayori**

5b# pose: Casual tapping pose<br>

#z expression: Angry expression<br>

scream: Screaming expression<br>
bscream: Casual screaming expression<br>

**Natsuki**

22# pose: Turned-face right-on-hip pose<br>
32# pose: Turned-face left-on-hip pose<br>
52# pose: Turned-face crossed-arms pose<br>
22b# pose: Turned-face casual right-on-hip pose<br>
32b# pose: Turned-face casual left-on-hip pose<br>
52b# pose: Turned-face casual crossed-arms pose<br>

#2j expression: Fully turned expression (for turned-face poses like 12# 22# 32# 42# 52#)<br>
#2bj expression: Fully turned casual expression (for turned-face poses like 12b# 22b# 32b# 42b# 52b#)<br>

bscream: Casual screaming expression<br>

**Yuri**

NEW 3# pose: Left-on-chest pose<br>
NEW 3b# pose: Left-on-chest casual pose<br>
6# pose: Right-cut pose<br>
7# pose: Right-cut left-on-chest pose<br>

#x expression: Sadly smiling expression<br>
#y expression: Angry closed-mouth expression<br>
#z expression: Very angry expression<br>

#by# expressions: Casual yandere expressions (for example 1by1, 3by3, 4by5, etc.)<br>

**Monika**

1b# pose: Casual hands-down pose<br>
2b# pose: Casual right-on-hip pose<br>
3b# pose: Casual left-pointing pose<br>
4b# pose: Casual left-pointing right-on-hip pose<br>
5b# pose: Casual leaning pose<br>

#s expression: Surprised expression<br>
#t expression: Surprised open-mouth expression<br>
#u expression: Smirking expression<br>
#v expression: Smirking open-mouth expression<br>
#w expression: Angry expression<br>
#x expression: Angry open-mouth expression<br>
#y expression: Angry closed-eye expression<br>
#z expression: Angry closed-eye open-mouth expression<br>

5c expression: Leaning happy open-mouth expression<br>
5d expression: Leaning angry closed-mouth expression<br>
5bc expression: Leaning casual happy open-mouth expression<br>
5bd expression: Leaning casual angry closed-mouth expression<br>

**Overall, many fun new expressions/poses were added!**

## YuriOriginalPoses.txt

This has everything MAIN.txt has except for the following:<br>

### Changes

Yuri's 4# and 5# expressions have been moved back to 3# and 4#, and the 3# has been moved to 5#. This is for compatibility with older scripts that your mod may be borrowing from (such as the original DDLC game).
