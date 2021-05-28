# MagneticTB

A Mathematica program package MagneticTB, which can generate
the tight-binding model for arbitrary magnetic space group. The only
input parameters in MagneticTB are the (magnetic) space group number
and the orbital information in each Wyckoff positions. Some useful
functions including getting the matrix expression for symmetry operators,
manipulating the energy band structure by parameters and interfacing
with other software are also developed.

## Installation

Copy the MagneticTB directory to any of the following four paths:

* ```FileNameJoin[{$UserBaseDirectory, "Applications"}]```
* ```FileNameJoin[{$BaseDirectory, "Applications"}]```
* ```FileNameJoin[{$InstallationDirectory, "AddOns", "Packages"}]```
* ```FileNameJoin[{$InstallationDirectory, "AddOns", "Applications"}]```


Then one can use the package after running ```Needs["MagneticTB`"]```.
The version of Mathematica should higher or equal to 11.0.

## Capabilities of MagneticTB

* Construct the tight-binding model for arbitrary magnetic space group
* Get the matrix expression for symmetry operators
* Interface with other software
* Manipulate the energy band structure by parameters

See https://arxiv.org/abs/2105.09504 for detail (please cite this paper if you use our code for your research).

## Examples

See examples.nb.


