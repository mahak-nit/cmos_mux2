2:1 Multiplexer Using Tanner EDA Tools

Aim:
To design a 2:1 Multiplexer (MUX) circuit and study its output using Tanner EDA tools.

Description:
A 2:1 Multiplexer is a combinational logic circuit that selects one of two input signals and forwards it to a single output based on the select line (S).
It has:
       Data Inputs: A, B
       Select Line: S
       Output: Y

Boolean Expression:
                   Y = A·S' + B·S

Where:
      * S' represents the NOT operation of S.
      * When S = 0, output Y = A.
      * When S = 1, output Y = B.

Truth Table:
             |  A  |  B  |  S  |  Y  |
             
             |  0  |  0  |  0  |  0  |
             |  0  |  1  |  0  |  0  | 
             |  1  |  0  |  0  |  1  |
             |  1  |  1  |  0  |  1  |
             |  0  |  0  |  1  |  0  |
             |  0  |  1  |  1  |  1  |
             |  1  |  0  |  1  |  0  |
             |  1  |  1  |  1  |  1  |

Tools Used:
           S-Edit: Circuit design
           T-Edit: Netlist preparation
           W-Edit: Waveform observation

Implementation:
1. Designed the 2:1 MUX circuit in S-Edit.
2. Prepared the circuit netlist in T-Edit.
3. Applied different combinations of inputs A, B, and select line S.
4. Observed the output waveform in W-Edit.
5. Compared the output with the truth table.

Examples of Input and Output
* Example 1: A = 1, B = 0, S = 0 → Y = 1
* Example 2: A = 0, B = 1, S = 1 → Y = 1
* Example 3: A = 1, B = 0, S = 1 → Y = 0

Result:
The 2:1 Multiplexer is designed to select one of two input signals based on the select line.

Applications:
* Data selection
* Digital communication systems
* Processor data paths
* Switching circuits
