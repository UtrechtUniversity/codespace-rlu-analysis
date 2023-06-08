# Codespace RLU analysis

A codespace for an online jupyter notebook environment.
It provides a number of packages and the UU-maintained `wellwellwell` package.
Use this template to create a shareable code repository for your RLU analyses.

# Setup

1. Create a repository by clicking `Use this template > Create new repository`
2. Under owner, specify `UtrechtUniversity`
3. After creating the repository, open the repository in a codespace
4. Add your data to the `data` folder
5. Remove `data/example.txt`
6. in the file `CITATION.cff` insert your name and affiliation(s)
7. Proceed with the data analysis

The analysis is conducted in 1 or more jupyter notebooks.
Structure them by prefixing the notebook with an number to indicate the order, for instance:

- 00_validation.ipynb
- 01_cleaning.ipynb
- 02_boxplots.ipynb
- 03_t-tests.ipynb

If your pipeline depends on a previous file, you can use this command:`%run MyOtherNotebook.ipynb`.
For instance, if you have a processed dataset at the end of `01_cleaning.ipynb` that you want to use in plotting,
you can start that file by writing `%run 01_cleaning.ipynb`.

# Example repositories

*To be added...*