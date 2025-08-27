Readme for Struct files


This zipfile contains some *.struct files that can be read by LauePattern V2.1 (but not earlier versions) and StructFactor V1.0.


The *.struct files are of semiconductor, ceramic and ionic crystal structures involving small molecules studied by x-ray topography and related techniques at X19-C. They are all Wycoff data, but not necessarily the most current edition of the volumes in all cases.

Note that the format of *.struct files involve a full set of x,y,z coordinates of each atom in a unit cell, and not some of the other formats that similar programs have used, for example, the combination of an asymmetric unit and a spacegroup symbol.  This was intended to make LauePt and StructFactor accessible to materials science students who haven't been initiated to the mysteries.  As you may be thinking, this is both good and bad.

A trick to rapidly convert an asymmetric unit/spacegroup file prepared for another program:
A program for visualizing models of unit cells named XtalDraw inputs unit cell data in the asymmetric unit/spacegroup form as a file with the extension *.xtl.  After a *.xtl data file is opened with this program, selecting from the pulldown menu  Edit; Unit cell Content  will create and display a file named xtalunitcell.txt.  This *.txt file will contain the full set of x,y,z coordinates of each atom in the cell that is required in a *.struct file (but not in precisely the same format as a *.struct file).  *.struct files listing hundreds of atom positions can be prepared rapidly by pasting this list of coordinates into a *.struct file with notepad.
The author of XtalDraw is Kurt Bartelmehs, a minerologist.  The Windows version of XtalDraw is currently freeware.

The names of some of the *.struct files are appended with _pseudohexagonal.  This denotes that the file describes a close-packed crystal structure that is expressed as a pseudohexagonal cell, as in as the 3C polytype of silicon carbide, which has a cubic symmetry, being expressed as a hexagonal cell with three molecular layers.  This is often done when the structures of the many polytypes of silicon carbide are compared (many of them have rhombohedral structures, denoted nR-SiC, which have trigonal unit cells).  It is important to note that LauePt will index the diffraction spots with hexagonal indices (hkil, omitting the "i" index) when a pseudohexagonal cell is entered.  This can be useful to compare the Laue patterns of two polytypes together, but if you need the spots indexed with regular Miller indices (hkl), you should use the cubic or rhombohedral *.struct files. 


While LauePattern and StructFactor were written by XianRong Huang, I belong to the same research group as he and have either created or collected from other people the files included in this zipfile (all in our lab). If you enter and use *.struct files for new materials or *.Spectrum files for a different x-ray source (and you are sure the atom coordinates have been entered correctly) I would appreciate it if you would send them to me. In return, I would send an updated zipfile containing all such files I have.


William M. Vetter
wvetter@ms.cc.sunysb.edu


Other inquiries about LauePattern and StructFactor should be addressed to the programs' author, XianRong Huang at xiahuang@aps.anl.gov.







    