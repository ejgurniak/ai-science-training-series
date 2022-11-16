Emily Gurniak

Machine Learning to predict polymer chain re-arrangement

Previous work used machine learning to characterize atoms in a Lennard-Jones glass as “soft” or “hard” based on the propensity for each atom to displace. This work considered the local structure around each atom and used 2 body terms and 3 body terms for neighbor atoms within a cutoff of the central atom. They used a Support Vector Machine to separate “soft” atoms that are likely to re-arrange from “hard” atoms that are likely to not re-arrange. 1 A similar technique can be applied to polymers. Polymers are characterized by crystalline and amorphous regions. The parameters to train can include the 2 body and 3 body terms used by Cubuk et. al. For polymers, it may be critical to also include 4 body dihedral angle terms. A Support Vector Machine characterizes items as belonging to one group or another. It may make sense to use a Neural Network to derive a parameter that is continuous rather than binary to predict polymer re-arrangements.



1 E.D. Cubuk, S.S. Schoenholz, J.M. Rieser, B.D. Malone, J. Rottler, D.J. Durian, E. Kaxiras, and A.J. Liu, Phys Rev Lett 114, 108001 (2015).
 
