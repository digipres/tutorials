You should now be able to run some simple commands.

To make sure the format signature files you are using are up to date, you can run:

`sf -update`

To see what the format of a file is, you can run something like:

`sf /usr/share/fonts/truetype/dejavu/DejaVuSans.ttf`

or

`sf /usr/share/icons/locolor/32x32/apps/gvim.png`

This will give you more detail about the format, and the factors the tool used to decide the format. For example, this may just be the file extension, or it may match patterns of bytes of data within the file.

You can also analyse a whole directory:

`sf /usr/share/fonts/`

The detailed default output format can be quite difficult to deal with, so it can also make sense to ask for the output in CSV format:

`sf -csv /usr/share/fonts/`

