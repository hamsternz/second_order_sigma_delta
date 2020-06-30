# second_order_sigma_delta
A comparison of 1st and 2nd order sigma delta DAC for implementation in an FPGA.

This small project implements two 12-bit DACs, one being a first order, the second being a second order :D

A new sample is provided from a 48-entry lookup table every 1000 clock cycles, so with a 100MHz clock it generates a 2.083kHz signal.

External to the FPGA will need to be a passive low pass filter.