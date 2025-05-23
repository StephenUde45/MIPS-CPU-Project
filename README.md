# MIPS-CPU-Project
Collaborated with a colleague to create a MIPS CPU single cycle processor capable of executing R type, I type, and J type instructions. 

Running each instruction within the control unit works perfectly fine. An issue we encountered was running mulitple LDR statements. The first LDR statement works but the two others, from the script, do not load in the correct contents. This affects the jump and branch statement making the simulation loop forever. The issue may be because of a timing error with the IP catalog source files and the sother source files.  
