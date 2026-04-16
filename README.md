Do not check the releases. There are no releases. This is one of the rare times I'm asking you to check the master instead :)
This is Definitions.Rpy For MPT (By A DDLC **D E V**) which is a modification to DDLC's files for making DDLC mods

## How to use Definitions.Rpy For MPT
Go to any file other than this one in the master and copy its contents into definitions.rpy of your mod, replacing everything that looks like this:

image sayori 1 = im.Composite((960, 960), (0, 0), "sayori/1l.png", (0, 0), "sayori/1r.png", (0, 0), "sayori/a.png")
image sayori 1a = im.Composite((960, 960), (0, 0), "sayori/1l.png", (0, 0), "sayori/1r.png", (0, 0), "sayori/a.png")
image sayori 1b = im.Composite((960, 960), (0, 0), "sayori/1l.png", (0, 0), "sayori/1r.png", (0, 0), "sayori/b.png")
image sayori 1c = im.Composite((960, 960), (0, 0), "sayori/1l.png", (0, 0), "sayori/1r.png", (0, 0), "sayori/c.png")
...
image monika g2:
    block:
        choice:
            "monika/g2.png"
        choice:
            "monika/g3.png"
        choice:
            "monika/g4.png"
    block:
        choice:
            pause 0.05
        choice:
            pause 0.1
        choice:
            pause 0.15
        choice:
            pause 0.2
    repeat

Replace it with one of the master files' full contents *(comments in the files are by Bronyarand because I used their DDLC template)*. Then, import Chronos' Mod Posing Tool (MPT) into the DDLC mod (https://drive.google.com/drive/folders/136KBThnImX3qABRlMO8YKykM5gtLI_6x) using this tutorial by EqualsM3rc: https://www.youtube.com/watch?v=v65X-Gj5g3s. MPT is required otherwise Ren'Py will either error out or simply not display the characters.

**Why would I need to use this?** Because it lets you use the most 'common' MPT poses quickly and allows you to easily add more. Plus, it makes all expressions compatible with AAA (Autofocus-Automouth-Autozorder) and NBT (Natural Blinking Tool) so yay :)

## MAIN.txt

This is the original version of Definitions.Rpy For MPT, and the version I usually use for my DDLC mods. These are replications of the original DDLC expressions except for the following:

### Changes

Yuri's original 3# pose got moved to 4#, and her original 4# pose got moved to 5# (same with 3b# > 4b# and 4b# > 5b#). This is to fit in with the other three girls.

The 1, 2, 3, 4, and 5 poses (and 11, 21, 31, 41, 51, 12, 42 for Natsuki) with the numbers by themselves have been removed.

### Additions

**Sayori**

5b# pose: Casual tapping pose

#z expression: Angry expression

scream: Screaming expression
bscream: Casual screaming expression

**Natsuki**

22# pose: Turned-face right-on-hip pose
32# pose: Turned-face left-on-hip pose
52# pose: Turned-face crossed-arms pose
22b# pose: Turned-face casual right-on-hip pose
32b# pose: Turned-face casual left-on-hip pose
52b# pose: Turned-face casual crossed-arms pose

#2j expression: Fully turned expression (for turned-face poses like 12# 22# 32# 42# 52#)
#2bj expression: Fully turned casual expression (for turned-face poses like 12b# 22b# 32b# 42b# 52b#)

bscream: Casual screaming expression

**Yuri**

NEW 3# pose: Left-on-chest pose
NEW 3b# pose: Left-on-chest casual pose

#x expression: Sadly smiling expression
#y expression: Angry closed-mouth expression
#z expression: Very angry expression

#by# expressions: Casual yandere expressions (for example 1by1, 3by3, 4by5, etc.)

**Monika**

1b# pose: Casual hands-down pose
2b# pose: Casual right-on-hip pose
3b# pose: Casual left-pointing pose
4b# pose: Casual left-pointing right-on-hip pose
5b# pose: Casual leaning pose

#s expression: Surprised expression
#t expression: Surprised open-mouth expression
#u expression: Smirking expression
#v expression: Smirking open-mouth expression
#w expression: Angry expression
#x expression: Angry open-mouth expression
#y expression: Angry closed-eye expression
#z expression: Angry closed-eye open-mouth expression

5c expression: Leaning happy open-mouth expression
5d expression: Leaning angry closed-mouth expression
5bc expression: Leaning casual happy open-mouth expression
5bd expression: Leaning casual angry closed-mouth expression

**Overall, many fun new expressions/poses were added!**
