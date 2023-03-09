# dar-docker
Docker container for Dar intended for usage with UnRaid 

dar (http://dar.linux.free.fr/home.html), which stands for Disk ARchive, is a robust and rich featured archiving and backup software.      Cancel changes


It is composed of:
    a library called libdar that exposes both a C++ and a python API,
    a command line program called dar that leverages all the features of libdar.

If you have a need for differential archiving large amounts of files dar is a great tool.
You can create a isolated catalogue of your archived files and do differential backups based on this isolated catalogue,
without the need to have the files still in place on your machine.

There is also a dockerfile for dargui (https://dargui.sourceforge.io/) available.
dargui is an userinterface for UI for dar that allows easy usage.
