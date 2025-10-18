# Malware-Simulation-Analysis
# Reverse-ex Malware Analysis Assignment

A simulated malware analysis project focused on discovering a hidden password within the provided executable file **reverse-ex**.
This project demonstrates fundamental reverse-engineering and malware analysis techniques in a safe environment.


## How It Works

The executable reverse-ex simulates basic malware behaviour.
Your objective is to **discover the embedded password** by analyzing how the program handles and compares user input.

You’ll use both **static** and **dynamic analysis** methods to identify where and how the password is stored or generated.


## How to Analyze

1. **Set up a safe environment**

   * Use a virtual machine (e.g., VirtualBox).
   * Copy the reverse-ex file inside your analysis folder.

2. **Perform static analysis**

   * Run reverse-ex to gather basic info.
   * Disassemble with **IDA** to inspect code flow.
   * Look for comparison functions like cmp or loops checking input.

3. **Perform dynamic analysis**

   * Run inside a debugger (GDB) to observe program behaviour.
   * Set breakpoints near input and comparison logic.
   * Watch for values being compared or computed in registers or memory.

4. **Verify your findings**

   * Once a possible password is found, test it in your VM.
   * Document how you confirmed it works.


## Features

* Demonstrates **reverse-engineering workflow**: static + dynamic analysis.
* Traces binary logic to find hidden values.
* Emphasizes safe lab practices and ethical malware research.
* Includes detailed **report**, screenshots, and analysis documentation.


## Tools Used

* **IDA Free** — for disassembly/decompilation
* **GDB**— for runtime observation
* **VirtualBox** — for isolated analysis


## Deliverables

* **16-page written report** including:

  * Overview of analysis plan and techniques used
  * Step-by-step discovery of the password
  * Challenges faced and how they were solved
  * What was learned and the conclusions
* **Screenshots and diagrams** to support findings


