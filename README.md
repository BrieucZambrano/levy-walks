# levy-walks

Python Code for Simulations of Levy Walks Searching an Unknown Size Target on the Torus

Python code is provided for simulating Lévy walks in the torus, searching for a target of unknown diameter, allowing to verify the figures shown in the paper "Intermittent Inverse-Square Lévy Walks are Optimal for Finding Targets of All Sizes" by Guinard and Korman (Science Advances, 2021). See also the preprint  https://arxiv.org/abs/2003.13041


Parameters are:
− the area n of the torus
− the diameter D of the target.
− the shape of the target (a line, a ball or a square).
− the probability p to detect a target while moving. If p=0, the target can only be detected while immobile, i.e., the process pertains to the intermittent detection model. If p>0, the process is said to have continuous detection.− the exponent mu of the Levy distribution.
− the cut-off lmax of the Levy distribution. There are two Python files. One is for the computation of the data and should be used first. The other one is for the examination of the resulting data, and includes the code for producing the figures exhibited in the paper.


Funding:	 H2020 European Research Council, Award: 648032 
