<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
A 4x4 multiplexer is a digital switch that selects one of four input signals and forwards the
 chosen input to a single output line based on two select lines. It utilizes combinational
 logic to route the input signals, where the select lines determine which of the four inputs 
is passed through. This multiplexer can be implemented using logic gates such as AND, OR, and 
NOT gates, allowing for efficient data management in digital circuits. Its primary application
 includes routing signals in communication systems, data acquisition, and in various digital
 systems where multiple inputs must be managed.

## How to test
To test a 4x4 multiplexer, apply different combinations of input signals (logic high and low) while 
varying the select lines to ensure the correct input is routed to the output. For a comprehensive 
test, all possible combinations of inputs (16 total, given 4 inputs) should be applied while 
systematically cycling through the select line configurations (00, 01, 10, 11). The output for
 each combination should be recorded and compared against the expected output based on the select 
line values. Any discrepancies will indicate a fault in the multiplexer design or implementation,
allowing for troubleshooting and refinement.
## External hardware
N/A 
