# brig-data

Brig Data is an open source tool that makes it easy to manage efficiently a huge amount of data.

In the complex era of Big Data, a lot of questions tortures every days professional software architects,
software engineers and data scientists. 

How to collect, how to analyze, how to exploit data to get added value for the business?

Here's the definitive solution, Brig Data represents a particular case of Lossy Compression method,
specifically it is a Total Loss Compression (TLC) method.

Data recovery from TLC methods is still under feasibility investigation.
Meanwhile, a partial extraction algorithm has been implemented.    

### Usage
```bash
$ chmod +x brig-data       --> set permission to perform BRIG compression!
$ ./brig-data yourfile     --> BRIG-compress file
$ ./brig-data yourfolder   --> BRIG-compress folder
$ ./brig-data --extract    --> extract data from BRIG-compressed file
$ ./brig-data --help       --> show README.md
```

### Disclaimer: 
Partial or total data loss might occasionally occurr depending on the nature of the input file or folder. 
A full cycle of compression and decompression is advisable to test the algorithm before actually using it!

### License
This software is released under the AGPLv3 license. See LICENSE file for more information.

Copyright (c) 2018 - 2020 by Spasmodic Software
