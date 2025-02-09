Computer Science 306 - Assignment 1: Creating a Simple ALU
Chapter 13 / Lesson 1
Lesson
Help
Course
Instructor Matt McClintock
Matt has a Bachelor of Arts in English Literature.

In this course, you began by learning the abstract concepts of Boolean logic and binary number system and ended by using these concepts in order to implement advanced computer architectures such as CPUs, memory systems, and parallel computers.

Upon completion of this project, you will be able to:

Design and develop a simple ALU as a part of a CPU
Decide on the number of operands for the ALU and design its instruction set
Design and construct the control unit of the CPU
Write assembly language for the constructed CPU
Prompt
In this project, you will design and build a simple CPU on Logisim and write programs that can run on it. If you haven't yet, you can download Logisim by following this link: http://www.cburch.com/logisim/download.html

Your design will go through four phases. In the first phase, you will design and build the ALU using Logisim. In the second phase, you will design the instruction set that implements the instructions you designed in phase one. In the third phase, you will design and implement a control unit for this ALU using Logisim. By connecting the CU to the ALU, you will get a functional CPU. In phase four of the project, you will write assembly language programs for the CPU you built.

Phase One
Start by building an 8-bit ALU using Logisim. This ALU can implement 16 instructions on 8-bit operands. In previous lessons, you created a 4-bit ALU; this will be 8-bit, and you should adjust/add components accordingly.

We would suggest the following minimum list of instructions:

Arithmetic addition
Increment
Decrement
Comparison (with 3 outputs: one for equals, one for less than and one for greater than)
Logic bitwise Not
Logic bitwise And
Logic bitwise Or
Register right logic shift
Register left logic shift
In addition to these nine instructions, please suggest five more instructions that the ALU can implement for a total of 14 instructions (we are reserving 2 instructions for branching). Justify the importance of the five instructions you added in a Word doc to submit as part of this assignment. Label these instructions as 'Phase One.'

After you've suggested and justified your five suggested instructions, please build at least the nine above-mentioned operations as blocks in Logisim.

Phase Two
In phase two of the project, you are required to design the instruction set of the ALU/CPU as follows:

Create the opcode table for the ALU by giving a binary code and a name for each instruction you built in Logisim in phase one.
Decide how many operands you want your instructions to handle and justify your choice. We suggest either one operand with accumulator or two operands with the result stored in one of the input registers.
In Logisim, add a multiplexer to the circuit you built in phase one that chooses one of the available operations. The simplest way to create this part of the CPU is to connect the outputs of the multiplexer to the inputs of AND arrays connected to the output of the operation blocks.
Please record your answer to phase two in the same Word doc and label it 'Phase Two.'

Phase Three
In phase three, you are required to use Logisim to implement the control unit for at least the following three operations:

addition
logic bitwise AND
right logic shift
In order to finish this phase, you need to add operand registers according to the decision you took for the number of operands in phase two. Following the example in Building an ALU Using Logisim, you will need to adjust for 8 bits. Following is a completed 4-bit ALU as an example.



Step 10: Final ALU Testing
ALU Testing


Please record your answer to phase three in the same Word doc and label it 'Phase Three.'

Phase Four
In order to be able to write assembly language for the CPU we need to add two instructions (without implementation). Write the following programs:

Write a program that adds operands until the new value to be added is 0. You do not need to implement the input operations to modify the contents of the registers. Just assume that by the end of each iteration, the register content is modified.
Write a program that shifts the content of a register until the least significant bit is 0. Think of a way to stop shifting if the content of the register is 11111111 and add it to your program.
Please record your programs in the same Word doc and label them under the section 'Phase Four.'

Related Chapters and Lessons
This assignment covers material presented in the chapters:

Digital Circuit Theory: Combinational Logic Circuits
Instruction Set Architecture.
The following lessons, in particular, should help with the assignment:

Building an ALU Using Logisim
Creating an Assembly Language Using an Instruction Set
Practical Application for Computer Architecture: Instruction Set Architecture
Sources
In addition to lessons in these chapters, you may refer to external sources as well. Any sources you use for this project, whether external or on Study.com, should be cited on a reference page that follows APA format. If you are unsure about how to use the APA format to cite your sources, please see the following lessons:

What is APA Formatting
How to Format APA Citations
Grading Rubric
Your project will be graded based on the following rubric:


Category	Unacceptable (0-1)	Needs Improvement (2-3)	Acceptable (4-5)	Total Points
Addition of 5 instructions to the ALU	No additional instructions are suggested and/or no choice justification	Less than 5 additional instructions are suggested and/or the justification is not clear or not correct	The project contains 5 additional instructions with clear and correct choice justification	5
Build the 9 original instructions in Logisim (x2)	Not all 9 instructions are implemented in Logisim and/or there are major functional issues	All 9 instructions are implemented in Logisim with some minor functional issues	All 9 instructions are implemented in Logisim and functioning correctly	10
Create the opcode table for the ALU	All or most of the instructions are missing from the opcode table	Some instructions are missing from the opcode table	The project contains a complete opcode table	5
Build the instruction selection unit using a multiplexer (x2)	The instruction selection unit is missing or not functioning correctly	The instruction selection unit is built in Logisim with minor functional issues	the instruction selection unit is correctly built in Logisim with no functional issues	10
Add the operand registers	Registers are not added and/or not connected to the circuit	N/A	Registers are added and correctly connected to the circuit	5
Design and implement the control unit in Logisim (x2)	The control unit is not implemented in Logisim and/or has major issues	The control unit is implemented in Logisim with minor issues	The control unit is correctly implemented in Logisim	10
Write a program that shifts the content of a register until the least significant bit is 0, with a way to stop shifting if the content of the register is 11111111	The program is missing or contains major errors	The program is written but contains minor errors	The program is correctly written with no errors	5
Total Points				50
Before You Submit
When you complete your assignment, we suggest taking some time to check for any errors or to add any finishing touches. We also suggest that you use online plagiarism checkers such as PlagScan or DupliChecker to make sure that your assignment is not too similar to any existing materials. Plagiarized submissions will NOT be graded.

How to Submit Your Assignment
When you are ready to submit your assignment, please fill out the submission form and attach your assignment. Please make sure your submission includes all four phases and your Logisim file (.circ). After turning in your assignment, you may go ahead and take the proctored final exam. You do not need to wait for your written response to be graded. You should receive your assignment grade within one week.

If you are not satisfied with the score you receive on your assignment, you may revise or rewrite it, and resubmit them for grading using the same submission form above. Keep in mind that the grade you receive on your assignment is only a portion of your overall grade for the course, and you are free to retake the proctored final exam as well if you choose. Please see the course syllabus for a more detailed breakdown of the grading policy.
