# OMTREE
OMTREE shows you the names, mountpoints and permission schemes of all ZFS's currently mounted on the system. Their relationship is shown in a pseudo-graphic way to let you easily identify sisters, children, and the mother of a given ZFS.                                            

The only parm that OMTREE accepts is the displaymode. you may specify either!"GRAPHIC"{(needs ISPF 4.1 or better and a graphic terminal or an emulator that supports graphics and APL),!"CHAR"{that uses conventioal charactes or!"DEFAULT"{that uses the capabilities of the 3278-T characterset. If no parm is specified, OMTREE tries to elabotrate the "best fitting" one.                                                   

As an additional feature, you may branch into the ISPF-shell by typingeither an!S{or a!/{in front of the ISHELL-field. The mountpoint of the selected ZFS will become your working directory.                    

I would really like to credit the original author as this tools has been helpful over the years.
