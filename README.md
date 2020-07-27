#BLACK_SCHOLES

## Simple Approaches to the Black-Scholes Equation
BLACK_SCHOLES is a FORTRAN77 library which demonstrates several approaches to the valuation of a European call, by Desmond Higham.

## Licensing:
The computer code and data files described and made available on this web page are distributed under the MIT license.


## Author:
Original MATLAB version by Desmond Higham;
FORTRAN77 version by Sourangshu Ghosh.

## Reference:
Desmond Higham,
Black-Scholes for Scientific Computing Students,
Computing in Science and Engineering,
Volume 6, Number 6, November/December 2004, pages 72-79.

## Source Code:

- black_scholes.f, the source code.
- black_scholes.sh, BASH commands to compile the source code.

## Examples and Tests:
- black_scholes_prb.f, a sample calling program.
- black_scholes_prb.sh, BASH commands to compile and run the sample program.
- black_scholes_prb_output.txt, the output file.
- asset_path.txt, the output data file from the asset path test.

## List of Routines:
- ASSET_PATH simulates the behavior of an asset price over time.
- BINOMIAL uses the binomial method for a European call.
- BSF evaluates the Black-Scholes formula for a European call.
- FORWARD uses the forward difference method to value a European call option.
- GET_UNIT returns a free FORTRAN unit number.
- MC uses Monte Carlo valuation on a European call.
- R8_NORMAL_01 returns a unit pseudonormal R8.
- R8_UNIFORM_01 returns a unit pseudorandom R8.
- R8VEC_NORMAL_01 returns a unit pseudonormal R8VEC.
- R8VEC_PRINT_PART prints "part" of an R8VEC.
- R8VEC_UNIFORM_01 returns a unit pseudorandom R8VEC.
- R8VEC_WRITE writes an R8VEC file.
- TIMESTAMP prints the current YMDHMS date as a time stamp.
- You can go up one level to the FORTRAN77 source codes.

