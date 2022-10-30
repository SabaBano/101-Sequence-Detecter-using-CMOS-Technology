# 101-Sequence-Detecter-using-CMOS-Technology
Sequence detector is designed using its CMOS layout and draws the
layout using Microwind and writes the netlist in Ngspice.When the
detector receives a sequence 101, its output will be high at the end of the
sequence and for any other sequence, output will be low.
Circuit is overlapping thus, an overlapping sequence like 10101 the first
part of the sequence 101, it will make output high at that position and
second 101 after 10 will also make output high at the end of the
sequence, Circuit is designed as a Mealy machine, so it will change its
output, both by its current state and the current inputs are changed. Input
does affect the output directly as soon as logic is done.
