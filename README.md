# VHDL Counter Bug

This repository demonstrates a common off-by-one error in VHDL code and its solution.

## Bug Description

A simple counter is implemented in VHDL. However, there's a subtle error in the reset condition, causing the counter to potentially behave incorrectly when it reaches its maximum value.

## Bug Solution

The solution file provides a corrected version of the counter that addresses the off-by-one error. The fix ensures the counter correctly resets to 0 when reaching its maximum value.

## How to Reproduce the Bug

1.  Simulate `buggy_counter.vhdl` using your favorite VHDL simulator.
2.  Observe the counter's behavior when it reaches the maximum count (15 in this case).
3.  Compare the observed behavior with the expected behavior (resetting to 0).

## How to Fix the Bug

Refer to `fixed_counter.vhdl` for the corrected code.