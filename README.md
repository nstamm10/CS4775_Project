# CS4775_Project
Final project for computation genetics course. Attempts to uncover hidden family tree structure from mouse DNA dataset. Dataset comes from: http://mtweb.cs.ucl.ac.uk/HSMICE/

### Abstract

### Steps to Reproduce
1. Clone the repository
    ``` git clone [repo_url]```
2. Ensure you have a jupyter python environment set up
3. Run cells 1-11. NOTE: cell 3 might take a long time (1-2 min) to run
4. Run cells 12 & 13 to get a list of the 10 most similar mice and their similarity percents
5. Run cell 14 and then call the function in that cell to get the similarity percent for any two mice in the dataset. Code below outputs similarity percent for mice 0 and 1400.
    ```get_percent_related(0, 1400)```
