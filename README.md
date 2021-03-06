# Exercise1 
NST Part II Chemistry : Programming Option

INTRODUCTION
=========================================================
This program allows calculation of Hückel π-energies and degeneracies for:
  1. A linear polyene with n carbons;
  2. A cyclic polyene with n carbons;
  3. The sp2-hybridized Platonic solids (i.e. 3D structures with faces of a single regular polygon,
     with carbons at each vertex and only 3 edges per vertex): tetrahedron, cube, and dodecahedron.
     (If you wish to suspend your chemical disbelief you might also try the octahedron and
     icosahedron);
 
REQUIREMENTS
=========================================================
This program also requires the following python libraries to work:
  1. Numpy (https://pypi.org/project/numpy/)
  2. pyutilib.math (if not already downloaded: https://pypi.org/project/pyutilib.math/#files includes wheel and zip)
  3. Networkx (https://github.com/networkx/networkx/)


RUNNING THE CODE
========================================================
Run this python script with your python interpreter and follow the instructions.
">>>" Requires user input.

EXAMPLE CODE RUN (Visual Studio Code)
=========================================================

(Please view "Raw"/"Blame": for better presentation of example code)

Microsoft Windows [Version 10.0.17134.345]
(c) 2018 Microsoft Corporation. All rights reserved.

C:\Users\...Exercise1.py"

Welcome to our Huckel Program!

    Please Choose your compound:
        1. length n poly-ene
        2. length n cyclic poly-ene
        3. sp2-hybridised Platonic Solids
    >>> 1

==============================================

This is the length n poly-ene program.
Please choose the value of n : 4

 length n poly-ene , with n = 4 :

[[ 0. -1.  0.  0.]
 [-1.  0. -1.  0.]
 [ 0. -1.  0. -1.]
 [ 0.  0. -1.  0.]]

Eigen values :

 [-1.6180339887498938, -0.6180339887498951, 0.6180339887498947, 1.6180339887498942]
 E = α -1.6β : 1 degeneracies
 E = α -0.6β : 1 degeneracies
 E = α +0.6β : 1 degeneracies
 E = α +1.6β : 1 degeneracies

Eigen vectors :

 [[ 0.37174803 -0.60150096 -0.37174803  0.60150096]
 [ 0.60150096 -0.37174803  0.60150096 -0.37174803]
 [ 0.60150096  0.37174803 -0.60150096 -0.37174803]
 [ 0.37174803  0.60150096  0.37174803  0.60150096]]

==============================================

Thank you for using this Huckel Program.

    Please choose what to do next:
        1. Go back to Start
        2. Exit
    >>>1

==============================================

Welcome to our Huckel Program!

    Please Choose your compound:
        1. length n poly-ene
        2. length n cyclic poly-ene
        3. sp2-hybridised Platonic Solids
    >>> 1

==============================================

This is the length n poly-ene program.
Please choose the value of n : 100

 length n poly-ene , with n = 100 :

[[ 0. -1.  0. ...  0.  0.  0.]
 [-1.  0. -1. ...  0.  0.  0.]
 [ 0. -1.  0. ...  0.  0.  0.]
 ...
 [ 0.  0.  0. ...  0. -1.  0.]
 [ 0.  0.  0. ... -1.  0. -1.]
 [ 0.  0.  0. ...  0. -1.  0.]]

Eigen values :

 [-1.9990325645839773, -1.996131194267189, -1.9912986959380365, -1.9845397447265596, -1.9758608794815102, -1.9652704964445247, -1.9527788411272204, -1.9383979983993247, -1.9221418807974486, -1.904026215065462, -1.8840685269399748, -1.8622881241953295, -1.838706077964472, -1.8133452023541534, -1.7862300323735865, -1.7573868001985409, -1.7268434097933196, -1.6946294099155554, -1.6607759655296006, -1.625315827656501, -1.5882833016895077, -1.5497142142057818, -1.5096458783065192, -1.468117057518919, -1.4251679282950156, -1.3808400411434933, -1.3351762804323055, -1.2882208229007952, -1.2400190949215537, -1.190617728553335, -1.1400645164275702, -1.0884083655120602, -1.0356992497966564, -0.9819881619466476, -0.9273270639706538, -0.8717688369507415, -0.8153672298833794, -0.7581768076807613, -0.7002528983827842, -0.6416515396307356, -0.5824294244545037, -0.5226438464257207, -0.4623526442299398, -0.401614145711436, -0.3404871114447986, -0.2790306778878458, -0.2173043001709491, -0.1553676945780129, -0.09328078077483602, -0.03110362384070269, 0.031103623840700406, 0.09328078077483455, 0.1553676945780114, 0.21730430017094976, 0.27903067788784613, 0.3404871114447963, 0.4016141457114372, 0.46235264422993877, 0.522643846425721, 0.5824294244545051, 0.6416515396307355, 0.7002528983827847, 0.7581768076807568, 0.8153672298833772, 0.8717688369507428, 0.9273270639706562, 0.9819881619466484, 1.0356992497966533, 1.0884083655120604, 1.1400645164275678, 1.1906177285533315, 1.2400190949215455, 1.2882208229007968, 1.3351762804323106, 1.380840041143495, 1.4251679282950183, 1.4681170575189237, 1.509645878306508, 1.5497142142057856, 1.5882833016895068, 1.6253158276565, 1.6607759655295977, 1.6946294099155546, 1.726843409793331, 1.7573868001985402, 1.7862300323735805, 1.8133452023541508, 1.8387060779644735, 1.8622881241953249, 1.8840685269399773, 1.9040262150654765, 1.9221418807974504, 1.938397998399322, 1.952778841127216, 1.9652704964445378,
1.9758608794815178, 1.9845397447265534, 1.9912986959380325, 1.9961311942671836, 1.9990325645839793]
 E = α -2.0β : 7 degeneracies
 E = α -1.9β : 5 degeneracies
 E = α -1.8β : 4 degeneracies
 E = α -1.7β : 3 degeneracies
 E = α -1.6β : 2 degeneracies
 E = α -1.5β : 3 degeneracies
 E = α -1.4β : 2 degeneracies
 E = α -1.3β : 2 degeneracies
 E = α -1.2β : 2 degeneracies
 E = α -1.1β : 2 degeneracies
 E = α -1.0β : 2 degeneracies
 E = α -0.9β : 2 degeneracies
 E = α -0.8β : 2 degeneracies
 E = α -0.7β : 1 degeneracies
 E = α -0.6β : 2 degeneracies
 E = α -0.5β : 2 degeneracies
 E = α -0.4β : 1 degeneracies
 E = α -0.3β : 2 degeneracies
 E = α -0.2β : 2 degeneracies
 E = α -0.1β : 1 degeneracies
 E = α -0.0β : 2 degeneracies
 E = α +0.1β : 1 degeneracies
 E = α +0.2β : 2 degeneracies
 E = α +0.3β : 2 degeneracies
 E = α +0.4β : 1 degeneracies
 E = α +0.5β : 2 degeneracies
 E = α +0.6β : 2 degeneracies
 E = α +0.7β : 1 degeneracies
 E = α +0.8β : 2 degeneracies
 E = α +0.9β : 2 degeneracies
 E = α +1.0β : 2 degeneracies
 E = α +1.1β : 2 degeneracies
 E = α +1.2β : 2 degeneracies
 E = α +1.3β : 2 degeneracies
 E = α +1.4β : 2 degeneracies
 E = α +1.5β : 3 degeneracies
 E = α +1.6β : 2 degeneracies
 E = α +1.7β : 3 degeneracies
 E = α +1.8β : 4 degeneracies
 E = α +1.9β : 5 degeneracies
 E = α +2.0β : 7 degeneracies

Eigen vectors :

 [[ 0.00437636 -0.00874848  0.01311214 ... -0.12849426  0.13934326
   0.13934326]
 [ 0.00874848 -0.01746312  0.02611019 ... -0.10477001 -0.03888104
   0.03888104]
 [ 0.01311214 -0.02611019  0.03888104 ...  0.04306823 -0.12849426
  -0.12849426]
 ...
 [ 0.01311214  0.02611019  0.03888104 ...  0.04306823 -0.12849426
   0.12849426]
 [ 0.00874848  0.01746312  0.02611019 ... -0.10477001 -0.03888104
  -0.03888104]
 [ 0.00437636  0.00874848  0.01311214 ... -0.12849426  0.13934326
  -0.13934326]]

==============================================

Thank you for using this Huckel Program.

    Please choose what to do next:
        1. Go back to Start
        2. Exit
    >>>1

==============================================

Welcome to our Huckel Program!

    Please Choose your compound:
        1. length n poly-ene
        2. length n cyclic poly-ene
        3. sp2-hybridised Platonic Solids
    >>> 2

==============================================

This is the length n cyclic poly-ene program.
Please choose the value of n : 6

 length n cyclic poly-ene , with n = 6 :

[[ 0. -1.  0.  0.  0. -1.]
 [-1.  0. -1.  0.  0.  0.]
 [ 0. -1.  0. -1.  0.  0.]
 [ 0.  0. -1.  0. -1.  0.]
 [ 0.  0.  0. -1.  0. -1.]
 [-1.  0.  0.  0. -1.  0.]]

Eigen values :

 [-1.9999999999999991, -1.0000000000000002, -0.9999999999999996, 0.9999999999999996, 0.9999999999999999, 1.9999999999999991]
 E = α -2.0β : 1 degeneracies
 E = α -1.0β : 2 degeneracies
 E = α +1.0β : 2 degeneracies
 E = α +2.0β : 1 degeneracies

Eigen vectors :

 [[ 0.40824829  0.40824829  0.57735027  0.57245374  0.07503368 -0.09791921]
 [ 0.40824829 -0.40824829 -0.28867513  0.22124579  0.53327632 -0.4437968 ]
 [ 0.40824829  0.40824829 -0.28867513 -0.35120794  0.45824264  0.54171601]
 [ 0.40824829 -0.40824829  0.57735027 -0.57245374 -0.07503368 -0.09791921]
 [ 0.40824829  0.40824829 -0.28867513 -0.22124579 -0.53327632 -0.4437968 ]
 [ 0.40824829 -0.40824829 -0.28867513  0.35120794 -0.45824264  0.54171601]]

==============================================

Thank you for using this Huckel Program.

    Please choose what to do next:
        1. Go back to Start
        2. Exit
    >>>1

==============================================

Welcome to our Huckel Program!

    Please Choose your compound:
        1. length n poly-ene
        2. length n cyclic poly-ene
        3. sp2-hybridised Platonic Solids
    >>> 2

==============================================

This is the length n cyclic poly-ene program.
Please choose the value of n : 10

 length n cyclic poly-ene , with n = 10 :

[[ 0. -1.  0.  0.  0.  0.  0.  0.  0. -1.]
 [-1.  0. -1.  0.  0.  0.  0.  0.  0.  0.]
 [ 0. -1.  0. -1.  0.  0.  0.  0.  0.  0.]
 [ 0.  0. -1.  0. -1.  0.  0.  0.  0.  0.]
 [ 0.  0.  0. -1.  0. -1.  0.  0.  0.  0.]
 [ 0.  0.  0.  0. -1.  0. -1.  0.  0.  0.]
 [ 0.  0.  0.  0.  0. -1.  0. -1.  0.  0.]
 [ 0.  0.  0.  0.  0.  0. -1.  0. -1.  0.]
 [ 0.  0.  0.  0.  0.  0.  0. -1.  0. -1.]
 [-1.  0.  0.  0.  0.  0.  0.  0. -1.  0.]]

Eigen values :

 [-1.9999999999999996, -1.6180339887498951, -1.618033988749895, -0.6180339887498952, -0.618033988749895, 0.6180339887498949, 0.6180339887498957, 1.6180339887498953, 1.6180339887498965, 2.000000000000001]
 E = α -2.0β : 1 degeneracies
 E = α -1.6β : 2 degeneracies
 E = α -0.6β : 2 degeneracies
 E = α +0.6β : 2 degeneracies
 E = α +1.6β : 2 degeneracies
 E = α +2.0β : 1 degeneracies

Eigen vectors :

 [[ 0.31622777  0.31622777 -0.4472136  -0.05555742  0.4472136   0.05680263
   0.4472136  -0.01468205 -0.4472136   0.01810427]
 [ 0.31622777 -0.31622777 -0.3618034   0.21588236  0.1381966   0.43943361
  -0.1381966  -0.42055913  0.3618034  -0.27729673]
 [ 0.31622777  0.31622777 -0.1381966   0.40486241 -0.3618034   0.21478227
  -0.3618034   0.27460189 -0.1381966   0.43057127]
 [ 0.31622777 -0.31622777  0.1381966   0.43919878 -0.3618034  -0.30669087
   0.3618034   0.25084583 -0.1381966  -0.41938222]
 [ 0.31622777  0.31622777  0.3618034   0.30577614  0.1381966  -0.40432765
   0.1381966  -0.42963314  0.3618034   0.24800341]
 [ 0.31622777 -0.31622777  0.4472136   0.05555742  0.4472136   0.05680263
  -0.4472136   0.01468205 -0.4472136   0.01810427]
 [ 0.31622777  0.31622777  0.3618034  -0.21588236  0.1381966   0.43943361
   0.1381966   0.42055913  0.3618034  -0.27729673]
 [ 0.31622777 -0.31622777  0.1381966  -0.40486241 -0.3618034   0.21478227
   0.3618034  -0.27460189 -0.1381966   0.43057127]
 [ 0.31622777  0.31622777 -0.1381966  -0.43919878 -0.3618034  -0.30669087
  -0.3618034  -0.25084583 -0.1381966  -0.41938222]
 [ 0.31622777 -0.31622777 -0.3618034  -0.30577614  0.1381966  -0.40432765
  -0.1381966   0.42963314  0.3618034   0.24800341]]

==============================================

Thank you for using this Huckel Program.

    Please choose what to do next:
        1. Go back to Start
        2. Exit
    >>>1

==============================================

Welcome to our Huckel Program!

    Please Choose your compound:
        1. length n poly-ene
        2. length n cyclic poly-ene
        3. sp2-hybridised Platonic Solids
    >>> 3

==============================================

This is the sp2-hybridised Platonic Solids program.

    Choose your platonic solid:
        1. Tetrahedron
        2. Cube
        3. Dodecahedron
        4. Octahedron
        5. Icosahedron
    >>>1

 sp2-hybridised Platonic Solids , with n = 1 :

[[0. 1. 1. 1.]
 [1. 0. 1. 1.]
 [1. 1. 0. 1.]
 [1. 1. 1. 0.]]

Eigen values :

 [-1.0, -1.0, -0.9999999999999998, 3.0]
 E = α -1.0β : 3 degeneracies
 E = α +3.0β : 1 degeneracies

Eigen vectors :

 [[-0.8660254   0.5         0.21699376  0.        ]
 [ 0.28867513  0.5        -0.86278187  0.        ]
 [ 0.28867513  0.5         0.32289406 -0.70710678]
 [ 0.28867513  0.5         0.32289406  0.70710678]]

==============================================

Thank you for using this Huckel Program.

    Please choose what to do next:
        1. Go back to Start
        2. Exit
    >>>1

==============================================

Welcome to our Huckel Program!

    Please Choose your compound:
        1. length n poly-ene
        2. length n cyclic poly-ene
        3. sp2-hybridised Platonic Solids
    >>> 3

==============================================

This is the sp2-hybridised Platonic Solids program.

    Choose your platonic solid:
        1. Tetrahedron
        2. Cube
        3. Dodecahedron
        4. Octahedron
        5. Icosahedron
    >>>3

 sp2-hybridised Platonic Solids , with n = 3 :

[[0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 1.]
 [1. 0. 1. 0. 0. 0. 0. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 1. 0. 1. 0. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 1. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 1.]
 [0. 0. 0. 1. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 0.]
 [0. 0. 0. 0. 1. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 0. 0. 0.]
 [0. 0. 1. 0. 0. 1. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 1. 0. 1. 0. 0. 0. 0. 0. 1. 0. 0. 0. 0. 0.]
 [0. 1. 0. 0. 0. 0. 0. 1. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 1. 0. 0. 1. 0. 0. 0. 0. 0. 0.]
 [1. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 1. 0. 0. 0. 0. 0. 1. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 1. 0. 0. 1. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 0. 1. 0. 1. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 1. 0. 0. 0. 0. 0. 1. 0. 1. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 1. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 0. 1. 0. 1. 0. 0.]
 [0. 0. 0. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 1. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0. 0. 0. 0. 0. 1. 0. 1.]
 [1. 0. 0. 1. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 1. 0.]]

Eigen values :

 [-2.2360679774997902, -2.2360679774997894, -2.2360679774997885, -2.000000000000001, -2.000000000000001, -1.9999999999999996, -1.9999999999999991, -4.2610482893491913e-16, -9.446381719931472e-17, 2.0381230449687125e-17, 9.568084172184577e-16, 0.9999999999999979, 0.9999999999999999, 1.0, 1.0000000000000004, 1.0000000000000007, 2.236067977499789, 2.2360679774997902, 2.2360679774997934, 2.999999999999999]
 E = α -2.2β : 3 degeneracies
 E = α -2.0β : 4 degeneracies
 E = α -0.0β : 4 degeneracies
 E = α +1.0β : 5 degeneracies
 E = α +2.2β : 3 degeneracies
 E = α +3.0β : 1 degeneracies

Eigen vectors :

 [[ 2.23606798e-01  3.87298335e-01 -3.87298335e-01  4.47213595e-01
  -4.96964672e-02 -4.47213595e-01  3.06944527e-02 -3.11050841e-02
   5.90021306e-03  6.90460288e-03  1.86127917e-02 -7.72603786e-02
  -1.87143697e-02 -2.03415363e-01 -3.24790918e-02  5.00000000e-01
  -3.04941125e-02  5.89600560e-03  8.00725043e-03  2.57719172e-02]
 [ 2.23606798e-01  2.88675135e-01  2.88675135e-01 -3.68520272e-16
   2.33479671e-01  2.98142397e-01 -3.97450553e-02  4.68136831e-02
  -2.43991240e-01 -4.32028989e-01 -1.32318198e-01 -1.71474029e-01
  -2.09642572e-01  1.85675140e-02  9.17512328e-02  1.66666667e-01
  -2.82746041e-01 -2.23551746e-01 -3.41865705e-01  8.03619459e-02]
 [ 2.23606798e-01  1.29099445e-01 -1.29099445e-01 -2.23606798e-01
  -9.39373633e-02 -7.45355992e-02 -2.24905399e-01  2.82374223e-01
  -2.14785092e-01  9.61947322e-02  3.37029948e-01  3.45869141e-01
   1.54169562e-01  2.30230038e-01  2.14707852e-01 -1.66666667e-01
  -2.85656174e-01  6.07936238e-02 -8.53345405e-02 -7.65327612e-02]
 [ 2.23606798e-01  1.29099445e-01 -1.29099445e-01 -2.23606798e-01
   1.52658388e-01 -7.45355992e-02  3.87990434e-01  3.50039876e-01
   5.31567526e-02  1.84506630e-01 -2.71460315e-01 -1.01627586e-01
  -2.54243064e-01  2.87852457e-01 -3.35590058e-01 -1.66666667e-01
   1.08339189e-01  4.42875364e-01 -9.65842056e-02  1.76426190e-02]
 [ 2.23606798e-01 -1.29099445e-01  1.29099445e-01  2.23606798e-01
  -3.28492285e-01 -7.45355992e-02 -3.97041037e-01  3.44039725e-01
   1.44099433e-01 -2.40617756e-01  2.62243028e-02 -1.47106822e-01
   2.58861220e-02  1.03004608e-01 -2.76317917e-01 -1.66666667e-01
   4.46665394e-01  4.31576993e-02 -1.93165468e-01 -2.53316511e-01]
 [ 2.23606798e-01 -2.88675135e-01 -2.88675135e-01 -3.77212342e-16
   2.03430106e-01  2.98142397e-01  1.32390582e-01  2.72665775e-01
  -6.76367453e-02 -2.87605965e-01  1.53050737e-01  3.21501933e-01
  -8.13591317e-02 -3.14667132e-01  1.53361298e-01  1.66666667e-01
   3.04921959e-01 -1.09476289e-01  1.67957152e-01 -4.02081919e-01]
 [ 2.23606798e-01 -1.29099445e-01  1.29099445e-01  2.23606798e-01
  -1.76087729e-01 -7.45355992e-02  1.01565420e-01  2.34554399e-01
  -2.89439580e-01  2.47522359e-01 -3.49843362e-01 -4.18636666e-01
   1.55546511e-01 -3.06419971e-01  2.43838825e-01 -1.66666667e-01
  -1.11249322e-01 -1.58529994e-01  3.53115370e-01 -1.74537326e-01]
 [ 2.23606798e-01 -1.29099445e-01  1.29099445e-01  2.23606798e-01
   2.84251389e-01 -7.45355992e-02 -1.10616022e-01 -3.05604181e-02
  -3.64784738e-01  1.91411233e-01  2.92192854e-01  1.69902259e-01
  -3.83903453e-01  8.44370939e-02 -3.68069150e-01 -1.66666667e-01
  -1.30515107e-01 -1.09847329e-01  2.70492758e-01  3.04077355e-01]
 [ 2.23606798e-01  1.29099445e-01 -1.29099445e-01 -2.23606798e-01
  -3.78442584e-01 -7.45355992e-02  2.73701057e-01 -1.46590562e-01
  -3.36696119e-01 -1.03099335e-01 -5.97702550e-02  7.43392957e-02
   2.83829951e-01 -2.68146744e-02 -1.82228760e-01 -1.66666667e-01
   3.34042459e-02 -2.90241376e-01 -2.64538415e-01  1.31122790e-01]
 [ 2.23606798e-01  1.29099445e-01 -1.29099445e-01 -2.23606798e-01
   3.28492285e-01 -7.45355992e-02 -3.97041037e-01 -3.44039725e-01
  -1.44099433e-01  2.40617756e-01 -2.62243028e-02 -1.47106822e-01
   2.58861220e-02 -1.03004608e-01  2.76317917e-01 -1.66666667e-01
   4.46665394e-01  4.31576993e-02 -1.93165468e-01 -2.53316511e-01]
 [ 2.23606798e-01  2.88675135e-01  2.88675135e-01  3.93023334e-16
  -2.03430106e-01  2.98142397e-01  1.32390582e-01 -2.72665775e-01
   6.76367453e-02  2.87605965e-01 -1.53050737e-01  3.21501933e-01
  -8.13591317e-02  3.14667132e-01 -1.53361298e-01  1.66666667e-01
   3.04921959e-01 -1.09476289e-01  1.67957152e-01 -4.02081919e-01]
 [ 2.23606798e-01  1.29099445e-01 -1.29099445e-01 -2.23606798e-01
   1.76087729e-01 -7.45355992e-02  1.01565420e-01 -2.34554399e-01
   2.89439580e-01 -2.47522359e-01  3.49843362e-01 -4.18636666e-01
   1.55546511e-01  3.06419971e-01 -2.43838825e-01 -1.66666667e-01
  -1.11249322e-01 -1.58529994e-01  3.53115370e-01 -1.74537326e-01]
 [ 2.23606798e-01 -1.29099445e-01  1.29099445e-01  2.23606798e-01
   9.39373633e-02 -7.45355992e-02 -2.24905399e-01 -2.82374223e-01
   2.14785092e-01 -9.61947322e-02 -3.37029948e-01  3.45869141e-01
   1.54169562e-01 -2.30230038e-01 -2.14707852e-01 -1.66666667e-01
  -2.85656174e-01  6.07936238e-02 -8.53345405e-02 -7.65327612e-02]
 [ 2.23606798e-01 -1.29099445e-01  1.29099445e-01  2.23606798e-01
  -1.52658388e-01 -7.45355992e-02  3.87990434e-01 -3.50039876e-01
  -5.31567526e-02 -1.84506630e-01  2.71460315e-01 -1.01627586e-01
  -2.54243064e-01 -2.87852457e-01  3.35590058e-01 -1.66666667e-01
   1.08339189e-01  4.42875364e-01 -9.65842056e-02  1.76426190e-02]
 [ 2.23606798e-01 -2.88675135e-01 -2.88675135e-01 -2.95680343e-16
  -8.10751147e-02  2.98142397e-01 -1.54034433e-01 -1.56299010e-01
  -1.89547772e-01 -1.44423024e-01 -2.43749467e-01  4.49285275e-03
   3.28430443e-01  3.33234646e-01 -6.16100653e-02  1.66666667e-01
  -5.26700304e-02  3.38924041e-01  1.81915803e-01  3.47491891e-01]
 [ 2.23606798e-01 -3.87298335e-01  3.87298335e-01 -4.47213595e-01
   4.96964672e-02 -4.47213595e-01  3.06944527e-02  3.11050841e-02
  -5.90021306e-03 -6.90460288e-03 -1.86127917e-02 -7.72603786e-02
  -1.87143697e-02  2.03415363e-01  3.24790918e-02  5.00000000e-01
  -3.04941125e-02  5.89600560e-03  8.00725043e-03  2.57719172e-02]
 [ 2.23606798e-01 -2.88675135e-01 -2.88675135e-01  2.24736699e-16
  -2.33479671e-01  2.98142397e-01 -3.97450553e-02 -4.68136831e-02
   2.43991240e-01  4.32028989e-01  1.32318198e-01 -1.71474029e-01
  -2.09642572e-01 -1.85675140e-02 -9.17512328e-02  1.66666667e-01
  -2.82746041e-01 -2.23551746e-01 -3.41865705e-01  8.03619459e-02]
 [ 2.23606798e-01 -1.29099445e-01  1.29099445e-01  2.23606798e-01
   3.78442584e-01 -7.45355992e-02  2.73701057e-01  1.46590562e-01
   3.36696119e-01  1.03099335e-01  5.97702550e-02  7.43392957e-02
   2.83829951e-01  2.68146744e-02  1.82228760e-01 -1.66666667e-01
   3.34042459e-02 -2.90241376e-01 -2.64538415e-01  1.31122790e-01]
 [ 2.23606798e-01  1.29099445e-01 -1.29099445e-01 -2.23606798e-01
  -2.84251389e-01 -7.45355992e-02 -1.10616022e-01  3.05604181e-02
   3.64784738e-01 -1.91411233e-01 -2.92192854e-01  1.69902259e-01
  -3.83903453e-01 -8.44370939e-02  3.68069150e-01 -1.66666667e-01
  -1.30515107e-01 -1.09847329e-01  2.70492758e-01  3.04077355e-01]
 [ 2.23606798e-01  2.88675135e-01  2.88675135e-01 -3.54533620e-17
   8.10751147e-02  2.98142397e-01 -1.54034433e-01  1.56299010e-01
   1.89547772e-01  1.44423024e-01  2.43749467e-01  4.49285275e-03
   3.28430443e-01 -3.33234646e-01  6.16100653e-02  1.66666667e-01
  -5.26700304e-02  3.38924041e-01  1.81915803e-01  3.47491891e-01]]

==============================================

Thank you for using this Huckel Program.

    Please choose what to do next:
        1. Go back to Start
        2. Exit
    >>>2

==============================================

C:\Users\...Part II_Chemistry\Exercise_1>
