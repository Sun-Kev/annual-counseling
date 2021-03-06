# annual-counseling
## Process and Notebook for annual college counseling tool refresh
The code here is used for creating an updated college directory and
all other source tables for Noble college counseling tools

### To follow the process, click through the workbooks linked to below
### To replicate the process, run the ipynb files in Jupyter after pulling the repo

Note that as you run through the Workbooks you'll want to increment
the year on the core source files, so you'll need to edit the file
reference based on the newest available file (downloaded in Step 0)
_(In the future, we could potentially edit this code to look for the
existence of the newest files and push those names to a master list)_  

Development has been conducted in a private repo, but most of this process
should eventually be made public (private data marked in the list below as
such)

### These links will take you to the individual notebook for each section:
_They should view nicely within Github and can be executed locally_

0. [Grabbing the NCES data files](Notebooks/Step_0_Grab_data.ipynb)
1. [Calculating distance from Chicago](Notebooks/Step_1_distance_calcs.ipynb)
2. [Cleanup Barrons Ratings](Notebooks/Step_2_get_Barrons.ipynb)
3. [Part 2: Cleanup Barrons Ratings](Notebooks/Step_2_5_Get_Barrons_inferred.ipynb)
4. [Calculate Grad Rates](Notebooks/Step_3_get_Grad_Rates.ipynb)
5. [Calculate "Money" Codes](Notebooks/Step_3_5_Add_Affordability.ipynb)
6. [Combine the files](Notebooks/Step_4_combine_files.ipynb)

## More data/tools
_These are performed on student data so are not included in this public repository_
_However, there will eventually be a public link to each of these with sanitized documentation

7. [Odds analysis](Notebooks/Example_of_Analyzing_Odds.ipynb)
8. Target calculation
9. Playbook creation
9. College Bot creation
