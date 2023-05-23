# CODE_SHIFTER
The shifter and the rotator are used for shifting bits in a binary word one position either to the left or to the  right. The difference between the shifter and the rotator is in how the end bits are shifted in or out. The six different  operations for the shifter / rotator are summarized.
The shifter and the rotator are used for shifting bits in a binary word one position either to the left or to the 
right. The difference between the shifter and the rotator is in how the end bits are shifted in or out. The six different 
operations for the shifter / rotator are summarized in Figure 29. 
For each bit position, a multiplexer is used to move a bit from either the left or right to the current bit position. 
The size of the multiplexer will determine the number of operations that can be implemented. For example, we can 
use a 4-to-1 mux to implement the four operations as specified by the table in Figure 30 (a). Two select lines, s1 and 
s0, are needed to select between the four different operations. For a 4-bit operand, we will need to use four 4-to-1 
muxes as shown in Figure 30 (b). How the inputs to the muxes are connected will depend on the given operations.
