# fpga_cpfp
HLS Custom-Precision Floating-Point Library

The figures below show the resource utilization of the multiplier and adder for different settings of exponent width, mantissa width, and rounding modes. The library results were gathered using Vivado HLS 2016.3, while the native floating-point results were gathered with Vivado HLS 2017.1. To test the adder core a simple function was synthesized consisting of a single addition between two cpfp numbers. Likewise to test the multiplier core a simple function was synthesized consisting of a single multiplication between two cpfp numbers. 

An example use-case can be found at: https://github.com/dicecco1/fpga_caffe/blob/master/src/fpga_caffe/layers/crp_layer_hwcn_cpfp.cpp

![adder_round](https://github.com/dicecco1/fpga_cpfp/blob/master/adder_round.png)

![adder_round_off](https://github.com/dicecco1/fpga_cpfp/blob/master/adder_round_off.png)

![mul_round](https://github.com/dicecco1/fpga_cpfp/blob/master/mul_round.png)

![mul_round_off](https://github.com/dicecco1/fpga_cpfp/blob/master/mul_round_off.png)
