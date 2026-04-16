Do not check the releases. There are no releases. This is one of the rare times I'm asking you to check the master instead :)

## How to use Definitions.Rpy MPT
Go to any file other than this one in the master and copy its contents into definitions.rpy, replacing everything that looks like this:

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

## MAIN.txt

This is the original version of Definitions.Rpy MPT. 
