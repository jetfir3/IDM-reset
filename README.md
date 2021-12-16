# IDM-reset

Resets IDM trial period.

Forked from [/Jackpison/IDM-reset/](https://github.com/Jackpison/IDM-reset/). 
* Swapped out subinacl for SetACL
* Checks for Admin permissions before running
* Runs commands based on 32/64-bit OS  

If running 32-bit Windows, SetACL is not required and skipped... along with all Wow6432Node reg key commands.  
If running 64-bit Windows, script checks if SetACL.exe is located in same directory and downloads via curl if not. 

## Credits
[/Jackpison/](https://github.com/Jackpison/IDM-reset/) for original script  
[Helge Klein](https://helgeklein.com/) for SetACL
