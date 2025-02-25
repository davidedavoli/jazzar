# BASH: a standard hash function from Belarus

Here is a Jasmin reference implementation for x86 that is a direct translation
of the standard and a vectorized implementation for AVX2.

Use at your own risks.

The official standard СТБ 34.101.77-2016 can be downloaded from
<http://apmi.bsu.by/resources/std.html>.

A C implementations from Сергей Агиевич, released under the terms of the GPLv3
license, can be found in the Bee2 library <https://github.com/agievich/bee2>

Formal description of the sponge function:
<https://eprint.iacr.org/2016/587.pdf>
