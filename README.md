#BenzylAcetateFluxAnslysis

**Note**: 
This source code was developed in Linux, and has been tested in Ubuntu 16.04 with Python 3.8.
We used cobrapy==0.21.0

1. Clone the repository

        git clone https://github.com/kaistsystemsbiology/BenzylAcetateFluxAnalysis.git

2. Create and activate virtual environment

        conda create -n flux_analysis python=3.8 ipykernel
        conda activate flux_analysis
        
3. Install required libraries

        pip install cobra
        conda install matplotlib
    

##Perform


- 1. Construction of GEMs with benzyl acetate production pathways

        Run 1_GEM_construction.ipynb

- 2. Calculate the maximum benzyl acetate production flux for integrated strains

        Run 2_analysis_integrated_strains.ipynb

- 3. Calculate the maximum benzyl acetate production flux for co-culture systems

        Run 3_analysis_co_culture_strains.ipynb