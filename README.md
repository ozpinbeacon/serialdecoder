# Serial Decoder
Bash script to provide information based on the serial number of an Apple device

The number of devices is limited to the ones I've encountered at my job, if you have others to add please do let me know

Usage: serialdecoder -b [-i] INPUTFILE [-o] OUTPUTFILE | [-s] SERIAL

Optional arguments:

-h      Show this message and then exit

-b      Use bulk mode

-i      Input csv with serials, used in conjunction with -b mode

-o      Print output to a file, if not specified with -b it will print to the working directory

-s      Individual serial
