# Movie-Recommendation-System-MOVICO
### This repository contains implementation files of the project 'MOVICO'.

<details>
  <summary color= blue >Table of Contents</summary>
<li> Summary</li>
<li> Prerequisites and Techstack</li>
<li> Steps for execution</li>
<li> Usage</li>
</details>
</br>

## Summary
### The project ``` 'MOVICO' ``` is a movie recommendation system.
### MOVICO mainly focuses and utilizes various ```collaborative filtering techniques``` , like KNN, SVD, etc...

### Files:
#### The following files are used to implement 'MOVICO' -
* **Project Python Code File**: `Movie_Recommendation_System.ipynb`
* **Dataset Files**: `movies.csv`, `ratings.csv`

### Repository Structure :
#### Below is the structure of the project repository
```plaintext
Movie-Recommendation-System-MOVICO/
├── MOVICO/             # Project Folder             
│   ├── Movie_Recommendation_System.ipynb      # Code file
│   └── dataset/        # Dataset Folder 
│        ├── movies.csv      
│        └── ratings.csv       
├── README.md           # Repository README
├── .gitignore          # Git ignore file
└── .gitattributes      # Git attributes file 
```


##  Prerequisites and Techstack

* Language: Python
* Prerequisites: AI-ML algorithms, like KNN, SVD.

* Python Modules used:
   * NumPy
  - pandas
  - matplotlib
  - seaborn
  - scipy
  - datetime
  - re
  - sklearn
  - ipywidgets
  - IPython
  - surprise
  - datetime

## Steps for Execution

To run the movie recommendation system, follow these simple steps:

1. **Open Jupyter Notebook**: Launch Jupyter Notebook on your system and navigate to the folder where you extracted the files. Open the `Collaborative_Movie_Recommendation_System.ipynb` file.

2. **Restart and Run All**: Click on the ">>" (fast forward) option in the toolbar, or select the "Restart & Run All Cells" option from the "Kernel" menu. This will execute all the cells in the notebook.

3. **Movie Recommendation**: In the cell number 52, you can enter the name of a movie in the widget (e.g., "Toy Story") to display personalized movie recommendations.

4. **Fine-Tune Recommendations**: In cell number 59:
   - Enter the number of movies you would love to watch from the list of recommendations. Input any number from 1 to 9 (e.g., 8).
   - Enter the number of movies from the list of recommendations that you would say are irrelevant to your taste. Input any number from 1 to 9 (e.g., 2).

6. **View Outputs**: After executing all the cells, the results and outputs will be displayed, including personalized movie recommendations based on your inputs.

Thank you for exploring the Collaborative Movie Recommendation System project. Happy movie watching! 🍿🎬
