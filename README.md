# Sharp_flat_2-adic_Iwasawa_invariants_quadratic_twists_ellpitic_curves
This repository contains the SageMath code used to compute the Iwasawa invariants in Section 3 and Section 5 of Taiga Adachi’s paper, “Iwasawa Invariants of Sharp/Flat 2-adic L-Functions for Quadratic Twists of Elliptic Curves.”

## Note on `IwInv_sage97.sage`

The file `IwInv_sage97.sage` is based on Robert Pollack's original
`IwInv.sage`.

To make the file compatible with Python 3 and SageMath 9.7, the Python 2
statement

```python
print line,
```

was replaced by

```python
print(line, end="")
```

This is the only modification made to Pollack's original file. In particular,
no changes were made to the mathematical algorithms or to the computation of
Mazur--Tate elements and Iwasawa invariants.
