Circuits implemented in logisim for my Computer Architecture's class. 154A

Download logisim and open files to run, circuits have built in testers that cycle thoughs test cases.

################
#  fun   #
################
Logisim circuit that implements the function: (x1 * x2 * ~x3) + (x3 * x4) + (x1 * x2 * ~x4) using only AND OR NOT XOR Gates

################
#  grey        #
################
Implements mapping of thee bits to their grey code representation using only AND OR NOT XOR Gates

################
#  bcd        #
################
Implements mapping of four bits to seven segment display in decimal using only AND OR NOT XOR Gates

################
#  shift3      #
################
Implements logical left or rigth shift on 3 digit binary number with 0's for padding using only AND OR NOT XOR MUX Gates

################
#  4bitAdder   #
################
Implements a 4bitAdder with carry look ahead using only AND OR NOT XOR Gates

################
#  Divider5    #
################
Implements 5 bit unsigned integer divider that completes a single division in 6 clock cycles or less using any component
except ROM RAM and Dividers

################
#  CPU         #
################
Implements simple 4 bit cpu with simplified control signals and simple alu operations. Python scripts creates microcode for
small program as test case. Registers at end of program hold respective results shown in python script.
