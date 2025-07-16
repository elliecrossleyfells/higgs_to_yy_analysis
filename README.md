# higgs_to_yy_analysis
Replication of H → γγ decay signals, using data collected by the ATLAS experiment at the Large Hadron Collider (LHC) in 2015 and 2016, and made available for public use via the ATLAS Open Data Portal. The data corresponds to proton-proton collisions at a center-of-mass energy of 13 TeV, with a luminosity of 36 fb^(-1)

The data is in the form of ROOT files, and is already curated (skimmed) to only contain di-photon events, and the photon selection criteria and methodology is simplified.

Added a section in the data download part to check for existing .root files to improve rerunability. You will need to download them for the first time, expect this process to take around an hour. 

Running with less than 100% of the data produces a less impressive chart. I would recommend using all of the available data. 

Awkward requires an older version of NumPy. Recommend creating a virtual environment for this. 


 
