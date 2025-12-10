# PROJECT-NAND2TETRIS-PART-1-project-05
project -05

# **Project 5 – Computer Architecture (Nand2Tetris)**

## **Overview**

Project 5 involves building the **Hack Computer** using **HDL (Hardware Description Language)**.
You will implement all the **hardware modules/chips** required for the CPU and memory system.

**Main goals:**

* Design and test all required **HDL chips**.
* Simulate the Hack CPU using the **Hardware Simulator**.
* Prepare the project for submission as `.hdl` files.

---

## **Files Included**

| File                                                  | Description                            |
| ----------------------------------------------------- | -------------------------------------- |
| `ALU.hdl`                                             | 16-bit Arithmetic Logic Unit           |
| `CPU.hdl`                                             | Central Processing Unit implementation |
| `Register.hdl`                                        | 16-bit register                        |
| `PC.hdl`                                              | Program counter                        |
| `RAM8.hdl`, `RAM64.hdl`, `RAM512.hdl`, `RAM4K.hdl`    | Memory modules of increasing size      |
| `RAM16K.hdl`                                          | Main memory                            |
| `ROM32K.hdl`                                          | Program memory (ROM)                   |
| `HalfAdder.hdl`, `FullAdder.hdl`                      | Basic arithmetic chips                 |
| `And.hdl`, `Or.hdl`, `Not.hdl`, `Mux.hdl`, `DMux.hdl` | Logic chips                            |

> All `.hdl` files should be tested individually using the **Hardware Simulator test scripts** provided by Nand2Tetris.

---

## **Testing Instructions**

1. Open **Hardware Simulator** from Nand2Tetris tools.
2. Load each `.tst` test script corresponding to the chip (e.g., `ALU.tst`).
3. Run the test and verify output matches the `.cmp` file.
4. Fix any errors before submission.

---

## **Submission Instructions**

1. Collect all `.hdl` files in a **single folder** (no subfolders).
2. Compress the folder as:

```
project5.zip
```

3. Upload to the **course submission portal**.

* You can submit multiple times; **highest score counts**.

---

## **License (MIT License)**

```
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## **References**

* [Nand2Tetris Official Website](https://www.nand2tetris.org/)
* *The Elements of Computing Systems* – Noam Nisan & Shimon Schocken
* Nand2Tetris Hardware Simulator

