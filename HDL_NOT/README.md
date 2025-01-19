# Problem Statement
- Create a module that implements a NOT gate.
![NOT](https://hdlbits.01xz.net/mw/images/9/9e/Notgate.png)

Verilog Code:
```
module top_module(
	input in,
	output out
);
	assign out = ~in;
endmodule
```
