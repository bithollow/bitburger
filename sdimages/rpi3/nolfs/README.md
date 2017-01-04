this directory is for temporary use, only one version of sd card image will be deployed here

to join the parts, example:
    $ cat rpi.img.xz.* > rpi.img.xz

to split a big file, example:
    $ split -b 64M -d rpi.img.xz "rpi.img.xz.part"
