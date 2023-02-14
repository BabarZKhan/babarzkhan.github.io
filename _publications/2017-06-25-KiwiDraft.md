---
title: "Kiwi Scientific Acceleration: FPGA HLS of Custom Arithmetic including Gustafson and Yonemoto's Posit Unum"
collection: publications
permalink: /publication/2017-06-25
excerpt: 'This is an unfinished draft when I was involved in HLS compilers during my research. Thanks to DJ Greaves who is the original and first author of this draft. I was the user of the Kiwi compiler.'
date: 01 September 2017

---

An appealing aspect of FPGA computation is the ability to use custom bit-widths and custom arithmetic systems. This is well known to save execution energy.
The recent increased use of machine learning algorithms has stimulated interest in custom arithmetic, both for training and deployment: the standard use of single-precision IEEE floating point is generally rekoned to be overkill for nearly all machine learning algorithms. Other application spaces where custom arithmetic is very useful include low-density parity checking and general Bayesian inference.
Using an HLS toolchain, it should be easy to replace one arithmetic system with another or reparameterise a given arithmetic system using alternative field widths. The basic approach will be to overload all of the basic arithmetic operators and allow the HLS compiler to instantiate the appropriate ALUs and custom-width data paths. In this little study we use the KiwiC HLS compiler that accepts dotnet files generated from CSharp.
Complete draft available [here](https://www.cl.cam.ac.uk/research/srg/han/hprls/orangepath/kiwic-demos/kiwi-posit-unum-and-custom-arithmetics/)

[Download paper here](https://babarzkhan.github.io/files/Kiwi-draft2017.pdf)
