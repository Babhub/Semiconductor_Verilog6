# Semiconductor_Verilog6

1a) Write a Verilog module for a 3-bit input Multiply/Accumulator (MAC) with a clear input, and 8-bit output. When the clear input is high, the accumulator output clears back to zero. When the clear input is low, the MAC multiplies it's two inputs ain and bin, and sums the result of the previous cycles multiply operation. 

1b) Construct a testbench for our design module that displays the stimulus results and generates a waveform to review the results.

1b) Construct a testbench for our design module that displays the stimulus results and generates a waveform to review the results.

2a) Write a Verilog module for an 8-bit data scrambler and 8-bit data unscrambler, that uses 16-bit polynomial G(x) = x^16 + x^5 + x^4 + x^3 + 1.

The polynomial's initial seed is FFFFh. The expected LFSR pattern was as the attached 2a1.png and A scrambler output pattern for an input of 8'h00 was as attached 2a2 and The scrambler/unscrambler should have a sync input that can be used to reseed the scrambler when asserted, and a bypass input that allows the input data to bypass the scrambling operation and direction pass to the output as attached 2a3. 

2b) Constructed a testbench for our two design modules connected a a complete system, that displays the stimulus results and generates a waveform to review the results. NOTE: The data scrambler and data unscrambler can leverage the same design module.

