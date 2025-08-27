Readme for Struct files


This zipfile contains some *.struct files that can be read by LauePattern V2.1 (but not earlier versions) and StructFactor V1.0.  *.struct files contain unit cell data for these two programs.  The *.struct files are of semiconductor, ceramic and ionic crystal structures involving small molecules studied by x-ray topography and related techniques at X19-C.  To make them available to LauePt and StructFactor, extract the *.struct files into the LauePt and StructFactor directories on your hard drive.

The names of some of the *.struct files are appended with _pseudohexagonal.  This denotes that the file describes a close-packed crystal structure that is expressed as a hexagonal pseudocell, as in the 3C polytype of silicon carbide, which has a cubic symmetry, being expressed as a hexagonal cell with three molecular layers.  This is often done when the structures of the many polytypes of silicon carbide are compared (many of them have rhombohedral structures, denoted nR-SiC, which have trigonal unit cells).  It is important to note that LauePt will index the diffraction spots with hexagonal indices (hkil, omitting the "i" index) when a pseudohexagonal cell is entered.  This can be useful to compare the Laue patterns of two polytypes together, but if you need the spots indexed with regular Miller indices (hkl), you should use the cubic or rhombohedral *.struct files.

The *.struct filenames for potassium sulfate (Beta-K2SO4) are appended with _Pnma or _Pnam, to denote two separate settings of the orthorhombic unit cell where either the c-axis is the longest (major axis), or the b-axis is set as the longest.  The second setting is considered archaic, but persists in the literature of hourglass dye inclusions.


While LauePattern and StructFactor were written by XianRong Huang, I belong to the same research group as he and have either created or collected from other people the files included in this zipfile (all in our lab).  If you enter and use *.struct files for new materials (and you are sure the atom coordinates have been entered correctly) I would appreciate it if you would send them to me, so I can add them to my collection.  In return, I would send an updated zipfile containing all such files I have.


William M. Vetter
wvetter@ms.cc.sunysb.edu


Other inquiries about LauePattern and StructFactor should be addressed to the programs' author, XianRong Huang at xiahuang@ms.cc.sunysb.edu.







    