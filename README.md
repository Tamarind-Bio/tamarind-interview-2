Protein ligand docking to assess binding affinity is an important task for small molecule and enzyme drug discovery. One popular open source docking tool is Autodock Vina. Smina is a fork of Autodock Vina optimized for special ligands and scoring. You will implement a program to run smina on a list of jobs containing pdb/sdf files. Your program should:
    - Run while there are any jobs with status “In Queue”
    - Run smina and save the result in a folder titled the job name
    - Set the job to status “Complete” at the end of a successful run
