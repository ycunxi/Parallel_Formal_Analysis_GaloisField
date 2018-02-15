***. Developed by Dr. Cunxi Yu at University of Massachusetts, Amherst **
**. Formal Analysis of Galois Field Arithmetic Circuits - Verification and Reverse Engineering **


Tool and examples are in /tool_examples.

Example:
Usage: ./gen_irreducible_poly file.eqn #bitwidth #threads
e.g. ./gen_irreducible_poly Mas64.eqn 64 10 (see log file bellow)

cunxi@xxx:~$ ./gen_irreducible_poly Mas64.eqn 64 20
USAGE: ./gen_eqns somefile.eqn (int)bits (int)threads
Number of results: 64

*** Report starts here ***** (Developed by Cunxi Yu at UMass Amherst. Last modified by Nov. 20 2016)

Successfully reverse engineer P(x) in this GF design
[1] ---------- This is a Galois Feild 64-bit (GF(2^64) multiplication) implemented by P(x) showing bellow ---------

[2] ---------- Irreducible polynomial P(x): x^64+x^21+x^19+x^4+1

[3] --------- Z[63:0] = (A[63:0] X B[63:0]) mod x^64+x^21+x^19+x^4+1


Verification results: printed into xxx.eqn_result (e.g., Mas64.eqn_result).
  The polynomial expression of eafh output bit (or each output bit function) are written in this file.
Reverse eng results: printed in the terminal.

*** Report ends here ******(contact: ycunxi@umass.edu, cunxi.yu@epfl.ch)
*** The references of this repository are shown bellow with bibtex ** 

https://ycunxi.github.io/Parallel_Formal_Analysis_GaloisField/


[1] Efficient Parallel Verification of Galois Feild Multipliers. (Best Paper Nomination)
Cunxi Yu and Maciej Ciesielski
IEEE/ACM 22nd Asia and South Pacific Design Automation Conference (ASP-DAC'17), Jan. 16-19, Chiba/Tokyo, Japan.

@inproceedings{yu2017-aspdac17,
  title={Efficient parallel verification of galois field multipliers},
  author={Yu, Cunxi and Ciesielski, Maciej},
  booktitle={Design Automation Conference (ASP-DAC), 2017 22nd Asia and South Pacific},
  pages={238--243},
  year={2017},
  organization={IEEE}
}


[2] Formal Analysis of Galois Field Arithmetic - Parallel Verification and Reverse Engineering (to appear)
Cunxi Yu, Maciej Ciesielski
IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems. (TCAD'18)


@inproceedings{yu2018-tcad-gf,
  title={Formal Analysis of Galois Field Arithmetic - Parallel Verification and Reverse Engineering},
  author={Yu, Cunxi and Ciesielski, Maciej},
  booktitle={IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)},
  year={2018},
  organization={IEEE}
}

