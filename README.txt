disk:
	FORTRAN 77 program to calculate how many disks are needed
        

USAGE:
	1) set disk  size
		disk size enter '1' for a CD 650M
 
		   		'2' CD 700M
 
		   		'3' DVD 4.7G
        
		Most cds these days are 700MB. 650MB is for really old cds.
  		DVDS are usually 4.7GB.

	2) UNIT,COUNT

		UNIT:

		'B' BYTE

		'K' KB

		'G' GB

		'T' TB

		(TB is mostly for entertainment purposes as 1TB of data would require 218 DVDS,

		which would be insane).

	COUNT: total size of data written to disk(s) is COUNT * the unit.

NOTE: does not take into consideration the space reserved for ISO9660.

May require extra disk(s) than whats calculated
