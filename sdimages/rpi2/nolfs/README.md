this directory is for temporary use, only one version of sd card image will be deployed here

to join the parts, example:
    $ cat rpi.img.bz2.* > rpi.img.bz2

to split a big file, example:
    $ split -b 50M -d rpi.img.bz2 "rpi.img.bz2.part"
