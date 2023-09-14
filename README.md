<a name="readme-top"></a>


# Movie-Recommendation-System-MOVICO
### This repository contains implementation files of the project 'MOVICO'.

<details>
  <summary color= blue >Table of Contents</summary>
<li> Summary</li>
<li> Prerequisites and Techstack</li>
<li> Steps for Execution </li>
<li> Sample Screenshots </li>
<li> Usage</li>
</details>
</br>

## Summary
### The project ``` 'MOVICO' ``` is a ```movie recommendation system```.
### MOVICO mainly focuses and utilizes various ```collaborative filtering techniques``` , like KNN, SVD, etc...

### Files:
#### The following files are used to implement 'MOVICO' -
* **Project Python Code File**: `MOVICO.ipynb`
* **Dataset Files**: `movies.csv`, `ratings.csv`

### Repository Structure :
#### Below is the structure of the project repository
```plaintext
Movie-Recommendation-System-MOVICO/
├── MOVICO/             # Project Folder             
│   ├── MOVICO.ipynb    # Code file
│   └── dataset/        # Dataset Folder 
│        ├── movies.csv      
│        └── ratings.csv       
├── README.md           # Repository README
├── .gitignore          # Git ignore file
└── .gitattributes      # Git attributes file 
```
  <p align="right">(<a href="#readme-top">back to top</a>)</p>
</br>

##  Prerequisites and Techstack

* Language: Python
* Prerequisites: AI-ML algorithms, like KNN, SVD.
* Other tools: Anaconda, Jupyter notebook.
* Python Modules used:
   * NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scipy
  - Datetime
  - Re
  - Sklearn
  - Ipywidgets
  - IPython
  - Surprise
    
  <p align="right">(<a href="#readme-top">back to top</a>)</p>
</br>

## Steps for Execution

To run MOVICO, follow these simple steps:

 1. **Clone** the ``` 'Movie-Recommendation-System-MOVICO' ``` github repository.
  ```sh [
  git clone https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO.git
  ```
2. **Launch** ```Jupyter Notebook``` on your system, using Anaconda.
 3.**Navigate** to the ``` 'MOVICO' ``` Directory in that.
  ```sh
  cd Movie-Recommendation-System-MOVICO
  cd MOVICO
  ```
  4. Open the ```MOVICO.ipynb``` file in Jupter Notebook. 


2. **Restart and Run All**: Click on the ">>" (fast forward) option in the toolbar, or select the "Restart & Run All Cells" option from the "Kernel" menu. This will execute all the cells in the notebook.

3. **Movie Recommendation**: In the cell number 52, you can enter the name of a movie in the widget (e.g., "Toy Story") to display personalized movie recommendations.

4. **Fine-Tune Recommendations**: In cell number 59:
   - Enter the number of movies you would love to watch from the list of recommendations. Input any number from 1 to 9 (e.g., 8).
   - Enter the number of movies from the list of recommendations that you would say are irrelevant to your taste. Input any number from 1 to 9 (e.g., 2).

6. **View Outputs**: After executing all the cells, the results and outputs will be displayed, including personalized movie recommendations based on your inputs.

  <p align="right">(<a href="#readme-top">back to top</a>)</p>
</br>

## Sample Screenshots

There are 3 models used in MOVICO:

* MODEL1 : USER-BASED COLLABORATIVE FILTERING
* ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/a96f5f41-7376-4410-83dc-2566663512c9)
  
* MODEL2 : KNN-BASED COLLABORATIVE FILTERING
* ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/cf882aa5-8474-4091-84f8-7dcbe38336e6)
* ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/531ae7b9-4492-4f7b-83b5-c20c89fdd7a2)

* MODEL3 : SVD-BASED COLLABORATIVE FILTERING
* ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/a3d60253-b240-40bc-bb11-663cdf3b6269)
* ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/5e754a09-c89f-4abf-8409-7983223d1680)






  <p align="right">(<a href="#readme-top">back to top</a>)</p>
</br>

## Usage
* MOVICO can be used to recommend movies to users, based on collaborative filtering techniques.
* More effective recommendation systems can be buit using MOVICO.
* MOVICO also provides functions to test the recommendations received from the recommendation models.
  <p align="right">(<a href="#readme-top">back to top</a>)</p>
</br>

Thank you for exploring the MOVICO project. Happy movie watching! 🍿🎬
