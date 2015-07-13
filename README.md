BiNetflowToSIGs
======

BiNetflowToSIGs is short for converting BiNetflow file To Social Interaction Graphs.


Usage
=====
Assuming having set `binetflowtosigs_ROOT` path variable correctly, then type `./binetflowtosigs -h` to get the following help message:
```
usage: binetflowtosigs [-h] [-w W] [-p P] [-d D] [-s S]

optional arguments:
  -h, --help  show this help message and exit
  -w W        window size; default=0.01
  -p P        path to the raw data; default='./Data/capture20110816.binetflow'
  -d D        folder for saving the output SIGs file; default='./Data/'
  -s S        name of the standard output SIGs file; default='result.sig'
```

Example:

 `$ ./binetflowtosigs -w 1`


Author
=============
Jing Zhang

Jing Zhang currently is a PhD student in Division of Systems Engineering, Boston University, working with Professor [Yannis Paschalidis](http://ionia.bu.edu/).


Email: `jzh@bu.edu`

Homepage: http://people.bu.edu/jzh/


Copyright 2015 Jing Zhang. All rights reserved. TAHTMA is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software Foundation.