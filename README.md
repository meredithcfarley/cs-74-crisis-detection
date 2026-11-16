# Crisis Detection of Suicide Ideation in User-Generated Text
CS 74 Final Project · Meredith Farley Duhrsen 

**Dataset:** Suicide and Depression Detection (Komati, 2021), CC BY-SA 4.0.
- Copy in this repository: see the **v1.0 release** (`archive.zip`)
- Original source: https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch

**Run in order in Google Colab:**
1. `01preprocessing.ipynb`: cleaning and saving the data
2. `02models.ipynb`: training, tuning, and test evaluation
3. `03analysis.ipynb`: feature reliance, error audit, and hyperbole analysis

## Generative AI use
**Tool:** Claude (Anthropic).
**Tasks:** Claude helped write supporting code (loading data from Google Drive, saving and reloading results, drawing the random samples for the error audit and hyperbole analysis). It also helped explain error messages across all notebooks, usually syntax errors, and also helped me fix errors when Colab wasn't running, my data wasn't loading, creating this Github. 

**Verification:** I read and understood every line of code that Claude produced, and the success was usually clear based on whether the data loaded or saved, and the random sample selection was verified by confirming the post id. 

**My own work:** all design decisions, basis of the the hand labeling of posts, and the interpretation of results. See the report for the full disclosure.
