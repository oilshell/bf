# bf.rb

A brainfuck interpreter written in pure Ruby

## Info

- The program is transpiled into Ruby then evaluated
- An array of 30,000 cells is initialized
	- Negative pointers refer to cells from the end of the array
- Output is ASCII-encoded

## bf2.rb Info

- `eval` is not used
- Negative pointers are allowed
