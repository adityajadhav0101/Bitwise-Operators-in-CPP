**💻 Bitwise Operators**

**🎯 Aim**

To perform bitwise operations and demonstrate how to set and reset a specific bit in an integer.

**📚 Theory**

🔹 Bitwise operators operate directly on the binary representation of integers. They are essential for tasks like flag manipulation, low-level programming, and performance optimization.

🔹 **Bitwise AND (&)** sets each bit to 1 only if both corresponding bits are 1.

**👉 Example:** _5 & 3_ → _0101 & 0011_ = _0001_ → **Result:** _1_

🔹 **Bitwise OR (|)** sets each bit to 1 if at least one of the corresponding bits is 1.

**👉 Example:** _5 | 3_ → _0101 | 0011_ = _0111_ → **Result:** _7_

**🔹 Bitwise XOR (^)** sets each bit to 1 only if the corresponding bits are different.

**👉 Example:** _5 ^ 3_ → _0101 ^ 0011_ = _0110_ → **Result:** _6_

**🔹 Bitwise NOT (~)** inverts all bits of an integer.

**👉 Example:** _~5_ → _~0101_ = _...1010_ → **Result:** _-6_ (in two's complement)

**🔹 Left Shift (<<)** shifts bits to the left, multiplying the number by powers of 2.

**👉 Example:** _5 << 1_ → _0101 << 1_ = _1010_ → **Result:** _10_

**🔹 Right Shift (>>)** shifts bits to the right, dividing the number by powers of 2.

**👉 Example:** _5 >> 1_ → _0101 >> 1_ = _0010_ → **Result:** _2_

🔹 These operators are used within control structures like if, while, and switch to manipulate data efficiently.

🔹 Bitwise operations are especially useful in scenarios where multiple flags or states are stored compactly in a single variable.
