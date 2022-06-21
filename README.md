# CalculatePartialChargesWithPsi4
An example Jupyter Notebook for calculating partial charges using Psi4.

The program is written in Python 3.7 requiring the following Python libraries:
* RDKit
* RESP
* Psi4
* OpenBabel

It takes a sdf file with compounds (incl 3D coordinates) and outputs a mol2 file with RESP derived partial charges.
Options for setting method (HF, B3LYP, ...), basis set (3-21G*, 6-31G**) and singlepoint or geometry optimization.

Contact: dr.jonas.bostrom at gmail.com

# pato

acá me puse a comparar antechamber con RESP (single point o relajando estructura y calculando las cargas de los confórmeros).
Dan parecido, salvo unos pocos átomos, pero no sé si está bien. Se suponge q RESP se debe hacer en 2 tandas.

https://github.com/cdsgroup/resp/blob/master/examples/example1.py
