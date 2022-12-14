# CS4775_Project
Final project for computational genetics course. Attempts to uncover hidden family tree structure from mouse DNA dataset. Dataset comes from: http://mtweb.cs.ucl.ac.uk/HSMICE/

### Abstract
Ancestry websites have become very popular among people who are looking for family members or curious about their history. A lot of these websites are founded on the idea that when given DNA sequences, they can be analyzed and manipulated to find relations between other people who have provided their DNA. With enough people signing up, these companies have been able to create huge family trees across a number of generations. The underlying idea that they use is called Identical by Descent, or IBD, which is the fact that everybody's DNA is a combination of their parent's. One algorithm that can utilize IBD to analyze data is the Position Burrows-Wheeler Transform (PBWT). PBWT computes a prefix array and a divergent array which allows us to receive the longest matches between any pair of subjects in the data set. With this, we can then compute how similar the subjects are to each other by judging the length of the longest matches to the length of the longest matches between other subject. With a quantified value of similarity, it is easy to compare the relationship between two pairs of subjects. Other applications of PBWT and IBD can be to create family trees or discover exact relationships, which is information that the ancestry websites often provide.

### Steps to Reproduce
1. Clone the repository
    ``` git clone [repo_url]```
2. Ensure you have a jupyter python environment set up
3. Run cells 1-11. NOTE: cell 3 might take a long time (1-2 min) to run
4. Run cells 12 & 13 to get a list of the 10 most similar mice and their similarity percents
5. Run cell 14 and then call the function in that cell to get the similarity percent for any two mice in the dataset. Code below outputs similarity percent for mice 0 and 1400.
    ```get_percent_related(0, 1400)```
