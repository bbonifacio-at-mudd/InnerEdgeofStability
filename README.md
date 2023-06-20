# InnerEdgeofStability
Code Repo for Inner Edge of Stability research w/ Prof. Tamayo


# Summary of repo and what is left to do

All of my files are in Real_Research, but I put a copy of the most important ones in June_2023_Most_Important_Files. This has the following files: 

-20230302_all_exoplanets.csv: Nikolas's csv of exoplanets

-20230304_exoplanet_archive_final.ipynb: Nikolas's jupyter notebook getting information from the csv of exoplanets

-Code_For_Obtaining_Initial_KDE_From_Populations.ipynb: Includes my code for creating a sample distribution of features, like eccentricity or mass, from an existing population of planets. This needs to be implemented in the Final_Status_of_Code

-exoarchive_planet_pairs.csv: Prof. Tamayo's csv of planets

-Final_Status_of_Code_Before_KDE.ipynb: This was the code before I cleaned things up and added KDE sampling to initialize the population
         
-June2023_Final_Population_Initialized_From_KDEs-Copy1: This is the final status of the code. I added KDE sampling to initialize the population and cleaned up the code a little to make sure it worked, and I generated the following figure as a "final" plot of observed period ratios versus the spock-flitered period ratios. This graph can change if you want to initialize the populations differently, but right now, it was made by initializing with observered masses and eccentricities. 

![image](https://github.com/bbonifacio-at-mudd/InnerEdgeofStability/assets/114462423/9080aa30-9902-492d-8d6d-8379cacbc087)

