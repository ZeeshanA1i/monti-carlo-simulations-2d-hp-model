3D Modeling & Simulations in Bioinformatics (CS06F)
ASSIGNMENT: 01
METROPOLIS MONTI CARLO SIMULATION
OF
2D Hyperbolic-Polar model of Proteins

Name: ZEESHAN ALI, Roll No: I14-1623
Instructor: PROF. HAMMAD NAVEED

Results of the algorithm on different protein sequences
(Observed that the performance was better for longer sequences)

S#
Length
Sequence
Energy
01
20
HPHPPHHPHPPHPHHPPHPH
-4
02
24
PPHPPHHPPPPHHPPPPHHPPPPHH
-2
03
25
PPHPPHHPPPPHHPPPPHHPPPPHH
-2
04
36
PPPHHPPHHPPPPPHHHHHHHPPHHPPPPHHPPHPP
-5
05
48
PPHPPHHPPHHPPPPPHHHHHHHHHHPPPPPPPPHHPPHHHPPHHHHH
-16
06
51
HHPHPHPHPHHHHPHPPPHPPPHPPPPHPPPHPPPHPHPHHHHHPHPHPHH
-16
07
60
PPHHHPHHHHHHHHPPPHHHHHHHHHHPHPPPHHHHHHHHHHHHPPPPHHHHHHPHHPHP
-31
08
64
HHHHHHHHHHHHPHPHPPHHPPHHPPHPPHHPPHHPPHPPHHPPHHPPHPHPHHHHHHHHHHHH
-40
09
85
HHHHPPPPHHHHHHHHHHHHPPPPPPHHHHHHHHHHHHPPPHHHHHHHHHHHHPPPHHHHHHHHHHHHPPPHPPHHPPHHPPHPH
-59
10
100
PPPHHPPHHHHPPHHHPHHPHHPHHHHPPPPPPPPHHHHHHPPHHHHHHPPPPPPPPPHPHHPHHHHHHHHHHHPPHHHPHHPHPPHPHHHPPPPPPHHH
-33
11
100
PPPPPPHPHHPPPPPHHHPHHHHHPHHPPPPHHPPHHPHHHHHPHHHHHHHHHHPHHPHHHHHHHPPPPPPPPPPPHHHHHHHPPHPHHHPPPPPPHPHH


    • STRING_01 = "HP"*2+"P"+"H"*2+"P"+"H"+"P"*2+"H"+"P"+"H"*2+"P"*2+"HPH"













    • STRING_02 = "H"*2+("P"*2+"H")*7+"H"


    • STRING_03 = "P"*2+"H"+"P"*2+("H"*2+"P"*4)*3+"H"*2


    • STRING_04 = "PPPHH"+"P"*2+"H"*2+"P"*5+"H"*7+"P"*2+"H"*2+"P"*4+"HHPPHPP”


    • STRING_05 = "P"*2+"H"+("P"*2+"H"*2)*2+"P"*5+"H"*10+"P"*6+("P"*2+"H"*2)*2+"H"+"P"*2+"H"*5



    • STRING_06 = "H"*2+"PH"*3+"P"+"H"*4+"PH"+("P"*3+"H")*2+"P"*4+"H"+("P"*3+"H")*2+"PHP"+"H"*4+"HP"*3+"H"*2


    • STRING_07 = "PPHHHPHHHHHHHHPPPHHHHHHHHHHPHPPPHHHHHHHHHHHHPPPPHHHHHHPHHPHP"


    • STRING_08 = "H"*12+"PH"*2+"PPHH"*2+"PPHPPHHPPHHPPHPPHHPPHHPPHPHP"+"H"*12


    • STRING_09 = "HHHHPPPPHHHHHHHHHHHHPPPPPP"+("H"*12+"P"*3)*3+ "HPPHHPPHHPPHPH"


    • STRING_10 = "PPPHHPPHHHHPPHHHPHHPHHPHHHHPPPPPPPPHHHHHHPPHHHHHHPPPPPPPPPHPHHPHHHHHHHHHHHPPHHHPHHPHPPHPHHHPPPPPPHHH"

    • STRING_11 = "PPPPPPHPHHPPPPPHHHPHHHHHPHHPPPPHHPPHHPHHHHHPHHHHHHHHHHPHHPHHHHHHHPPPPPPPPPPPHHHHHHHPPHPHHHPPPPPPHPHH"
