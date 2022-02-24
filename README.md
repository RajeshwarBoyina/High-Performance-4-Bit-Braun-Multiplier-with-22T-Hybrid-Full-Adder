# High Performance 4 Bit Braun Multiplier with 22T Hybrid Full Adder
This Repository presents the design of a 4 Bit Braun Multiplier using 22T Hybrid Full Adder

# Table of Contents
[TOCM]

1. [Abstract](#Abstract)
2. [Reference Circuit Details](#reference-circuit-details)
3. [Installation of the tools](#installation-of-the-tools)
4. [Methodology](#Methodology)
    - [Step1 Construct AND Gate](#step1-construct-and-gate)
    - [Step2 Construct 4X4 Matrix of AND Gate](#step2-construct-4x4-matrix-of-and-gate)
    - [Step2 Construct Full Adder](#step4-construct-full-adder)
    - [Step5 Construct 4-Bit Braun Multiplier](#step5-construct-4-bit-braun-multiplier) 
5. [Results](#results)
    - [Command Window](#command-window)
    - [Obtained Output Waveforms](#obtained-output-waveforms)
6. [References](#references)
7. [Acknowledgement](#Acknowledgement)
8. [Author](#author)

## Abstract

* Low power and high speed circuits have become important requirements in high performance VLSI design in the last few years. An ***Arithmetic Logic Unit*** basically consists of an **Adder** and a **Multiplier**. The basic component of any ALU is an adder and the operation performed by it is called as addition. And this adder is used as a building block to design a multiplier. Hence, multiplication becomes a fundamental unit of any DSP application like FFT, etc. As a result, new approaches to arithmetic circuit design are needed to achieve desirable output in terms of area, power and delay.

* The main objective is to design a High Performance Adder and Multiplier which will be working upto 2 GHz clock frequency. The proposed Hybrid Full Adder is designed  using Pass Transistors, Transmission gates and Conventional Complementary Metal Oxide Semiconductor. For multiplication operation, Braun multiplier architecture has been implemented using the above mentioned adder. And the average propagation delay and power dissipated by both the circuits is also calculated.

## Reference Circuit Details

* Braun Multiplier
  1. Also known as **Carry Save Array Multiplier**.
