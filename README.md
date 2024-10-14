Stage 1:
Protein ligand docking to assess binding affinity is an important task for small molecule and enzyme drug discovery. One popular open source docking tool is Autodock Vina. Smina is a fork of Autodock Vina optimized for special ligands and scoring. You will implement a program to run smina on a list of jobs containing pdb/sdf files. Your program should:
    - Run while there are any jobs with status “In Queue”
    - Run smina and save the result in a folder titled the job name
    - Set the job to status “Complete” at the end of a successful run

Stage 2:
Add additional functionalities to make your program handle a wide variety of inputs. Some ideas are below:
    - Set the job to status “Stopped” if smina fails to produce a result
    - Get binding affinity from log
    - Support whole protein docking
    - Handle conversion of sdf to pdbqt

Smina paper: https://pubs.acs.org/doi/10.1021/ci300604z 