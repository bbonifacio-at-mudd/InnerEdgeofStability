# InnerEdgeofStability
Code Repo for Inner Edge of Stability research w/ Prof. Tamayo


# Summary of repo and what is left to do

All of my files are in Real_Research, but I put a copy of the most important ones in June_2023_Most_Important_Files. This has the following files: 

-20230302_all_exoplanets.csv (Nikolas's csv of exoplanets)
-20230304_exoplanet_archive_final.ipynb (Nikolas's jupyter notebook getting information from the csv of exoplanets)
-Code_For_Obtaining_Initial_KDE_From_Populations.ipynb (Includes my code for creating a sample distribution of features, like eccentricity or mass, from an existing population of planets. This needs to be implemented in the Final_Status_of_Code)
exoarchive_planet_pairs.csv (Prof. Tamayo's csv of planets)
- Final_Status_of_Code.ipynb:
        The final status of the code used to make the graphs in the paper. There's two main TODO's for this before the paper can be completed. The first is to put the gaussian_kde code from
        Code_For_Obtaining_Initial_KDE_From_Populations.ipynb into the 5th cell in this code where the populations are initialized. The second, and less important, TODO is to double check how the
        KS-test calculates its p-values for how similar the curves are. 
