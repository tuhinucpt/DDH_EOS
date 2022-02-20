# DDH_EOS
## Relativistic description of dense matter equation of state and compatibility with neutron star observables: a Bayesian approach 

The general behavior of the nuclear equation of state (EOS), relevant for the description of neutron stars (NS), 
is studied within a  Bayesian approach applied to a set of models based on a density dependent relativistic mean 
field description of nuclear matter [Malik et al 2022](https://arxiv.org/abs/2201.12552). 
The EOS is subjected to a  minimal number of constraints based on nuclear 
saturation properties and  the low density pure neutron matter EOS  obtained from a precise next-to-next-to-next-to-leading 
order (N$^{3}$LO) calculation in chiral effective field theory ($\chi$EFT). The number of final sample parameters 
corresponding to the posterior sets are around {fifteen thousand}. We present five EOSs among them, namely 
DDBl, DDBm, DDBu1, DDBu2 and DDBx. The DDBl, DDBm, DDBu2 were chosen so that the radius of the 1.4$M_\odot$ 
star has the lower limit, a medium value and the upper limit  of the the 90\% CI for the conditional 
probabilities $P(R|M)$. We have also included DDBu1 that has a slightly lower $R_{1.4}$ than the upper limit but
lies completely inside the 90\% CI for the conditional probabilities $P(R|M)$. The DDBx is the one that predicts 
a maximum mass of 2.5$M_\odot$ and has the following nuclear matter properties, $K_0=300$ MeV, $J_{sym,0}=30$ MeV 
and $L_{sym,0}=39$ MeV.

We also release our entire sets of ~14K NS matter EOS. All the EOSs are for NS core and starting 
baryon density is 0.04 fm$^{-3}$. One needs to add their own choice of crust EOS for the star properties calculation.
The uncertainty in star properties for the choice of different crust has been discussed in Section 2.1 of 
the manuscript (arxiv: 2201.12552).

## Steps to extract the entire sets of DDB EOSs
   1) zip -F eos.zip --out ddb_14k_eos.zip
   2) unzip ddb_14k_eos.zip

All the eos files have three columns baryon density (fm-3), energy density (MeV.fm-3), and pressure (MeV.fm-3). The starting density is 0.04 fm-3, as it is NS core eos. One needs to add their own choice of crust eos in order to calculate NS properties. 


# Citation 
[1] Malik, T., Ferreira, M., Agrawal, B. K., and Providência, C., “Relativistic description of dense matter equation of state and compatibility with neutron star observables: a Bayesian approach”, <i>arXiv e-prints</i>, 2022.
 
BibTex-- 
@article{Malik:2022zol,
    author = "Malik, Tuhin and Ferreira, Márcio and Agrawal, B. K. and Providência, Constança",
    title = "{Relativistic description of dense matter equation of state and compatibility with neutron star observables: a Bayesian approach}",
    eprint = "2201.12552",
    archivePrefix = "arXiv",
    primaryClass = "nucl-th",
    month = "1",
    year = "2022"
}

# Acknowledgments:
This work was partially supported by national funds from FCT 
(Fundação para a Ciência e a Tecnologia, I.P, Portugal) under the
Projects No. UID/\-FIS/\-04564/\-2019, No. UIDP/\-04564/\-2020, 
No. UIDB/\-04564/\-2020, and No. POCI-01-0145-FEDER-029912 with 
financial support from Science, Technology and Innovation, in its
FEDER component, and by the FCT/MCTES budget through national funds (OE). 
BKA acknowledges partial  support from the Department of Science and 
Technology, Government of India  with grant no.  CRG/2021/000101. 

The authors acknowledge the Laboratory for Advanced Computing at University of Coimbra for providing HP
resources that have contributed to the research results reported within this paper, 
[URL](https://www.uc.pt/lca).
