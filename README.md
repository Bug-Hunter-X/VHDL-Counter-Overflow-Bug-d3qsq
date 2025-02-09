# VHDL Counter Bug and Solution

This repository demonstrates a common error in VHDL code involving counters and provides a solution. The bug is related to potential overflow and edge case handling within the counter's logic.

## Bug Description

The `buggy_counter.vhdl` file contains a VHDL counter with a potential overflow issue.  Under certain circumstances, the counter's behavior may be unpredictable, especially when transitioning from the maximum count value back to zero.

## Solution

The `fixed_counter.vhdl` file presents a corrected version that addresses the overflow problem using a more robust approach.  It clearly handles all potential scenarios and ensures predictable counter operation.

## How to Use

1. Open `buggy_counter.vhdl` to see the code with the bug.
2. Open `fixed_counter.vhdl` to see the corrected code.
3. Simulate the code in your preferred VHDL simulator to observe the behavior of each counter and compare their differences.

This example highlights the importance of careful edge case handling in VHDL designs to prevent subtle but potentially catastrophic bugs.