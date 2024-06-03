# Using the Multiplier

In this last week-end, I manage to find the problem with the `MultiplierController`. There were some problem with the way with the multiplexer sensitivity list. I thought I just needed the `sel` signal, but in fact both `in0` and `in1` could change without the `sel` ever changing. Once the sensitivity list fixed, and some error in the test bench, the multiplier worked perfectly.

## Plan

1. Quick Introduction.
1. Draw Block Design from last week
   1. Explain the problem
   1. Explain the solution
1. AXI4-Lite Custom IP
1. Workflow - HDL Wrapper - Synthesize - Implement - Generate Bitstream - Export Hardware
1. `C`
   1. Listen to the terminal for 2 numbers
   1. Send the 2 numbers to the multiplier
   1. Wait for the interupt to be raise
   1. Read the product
   1. Send the value to the terminal

