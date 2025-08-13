# Gould 5200 printer files, 1976-1984 
This repository contains a set of files from 1976-1984 that constitute the source and related files of MIT-created logic programs to control and [spool](https://en.wikipedia.org/wiki/Spooling) printer requests from the ITS operating system to the Gould 5200 electrocstatic printer/plotter. The software was largely created and maintained by John Kulp (user JLK). The files available in this repo are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [plnr](../main/plnr)
The files within this directory are the Gould printer specific files from [30 different tape image files](../main/tapeimagelist.txt) in the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265) that make up multiple early versions. Files are from ITS backup tapes. Most code files are written in the Lisp programming language and were originally created on PDP-10 or PDP-11 timeshare computers running the ITS operating system. 

Files were extracted from the tape images using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, `INFO; GLP 1`, for example. All files have been placed into this artificial `gould5200printer` directory for organizational purposes. The files extracted from the tape images were put into sub-folders with a corresponding name to the tapes listed in the `tapeimagelist.txt` file.

[7 files are ITS archive files](../main/ITSarchivefilelist.txt) within this extracted set. Digital Archivist, Joe Carrano, extracted the contents of these files into directories of the same name, one level up from their location using the [itsarc](https://github.com/larsbrinkhoff/pdp10-its-disassembler/blob/master/itsarc.c) program.
### [codemeta.json](../main/codemeta.json)
This file is metadata about the Micro-Planner files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [LICENSE](../main/LICENSE)
This file describes the details about the rights to these files. See [Rights](#rights) for additional information.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [`planr`](../main/planr) directory showing the original file timestamps as extracted from the tape images.
### [tapeimagelist.txt](../main/tapeimagelist.txt)
A list of all the tape images and their paths in the ToTS collection that these files came from.
### [ITSarchivefilelist.txt](../main/ITSarchivefilelist.txt)
## Preferred Citation
[filename], Gould 5200 printer files, 1976-1984, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts.
## Rights
To the extent that MIT holds rights in these files, they are released under the terms of the [MIT License](https://opensource.org/licenses/MIT). See the `LICENSE` file for more information. Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Eric Swenson](https://github.com/eswenson1) for help with identifying these files.