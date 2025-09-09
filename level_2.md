## Description:
The password for the next level is stored in a file called - located in the home directory

## Commands used:
cd '-'
cat /home/bandit1/-

## Explanation:
The file containing the password can’t be opened with a normal cat because the spaces in the filename make the shell treat it as multiple separate arguments. To access it, I used quotes around the filename (cat "spaces in this filename") so the shell would interpret it as a single file. This allowed me to directly open the file and read the password without issues caused by spacing.

## Password:
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
