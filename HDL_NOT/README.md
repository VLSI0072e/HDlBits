# Problem Statement
- Create a module that implements a NOT gate.
![NOT](https://github.com/VLSI0072e/HDlBits/blob/main/image/Notgate.png)
- Verilog Code:
```
module top_module(
	input in,
	output out
);
	assign out = ~in;
endmodule
```
- Waveform:
![Waveform](https://github.com/VLSI0072e/HDlBits/blob/main/image/not_waveform.png)
