<a name="readme-top"></a>


# Movie-Recommendation-System-MOVICO
The repository ```Movie-Recommendation-System-MOVICO``` contains the project ```MOVICO```.
``` 'MOVICO' ``` is a ```movie recommendation system```.


<details>
  <summary color= blue >Table of Contents</summary>
<li> Introduction</li>
<li> Prerequisites and Techstack</li>
<li> Steps for Execution </li>
<li> Sample Screenshots </li>
<li> Usage</li>
</details>
</br>

## Introduction
``` 'MOVICO' ``` is a ```movie recommendation system```.
```MOVICO``` mainly focuses and utilizes various ```collaborative filtering techniques``` , like KNN, SVD, etc...

### Files:

The following files are used in ```MOVICO```-
* **Project Python Code File**: `MOVICO.ipynb`
* **Dataset Files**: `movies.csv`, `ratings.csv`

### Repository Structure :
Below is the structure of the ```MOVICO``` project repository
```plaintext
Movie-Recommendation-System-MOVICO/
├── MOVICO/             # Project Folder             
│   ├── MOVICO.ipynb    # Code file
│   └── dataset/        # Dataset Folder 
│        ├── movies.csv      
│        └── ratings.csv       
└─── README.md           # Repository README

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
Clone > Launch > Navigate > Open > Run-all > MOVICO Specific Instructions >

 1. **Clone** the ``` 'Movie-Recommendation-System-MOVICO' ``` github repository.
  ```sh [
  git clone https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO.git
  ```
2. **Launch** ```Jupyter Notebook``` on your system, using Anaconda.
3. **Navigate** to the ``` 'MOVICO' ``` Directory in that.
  ```sh
  cd Movie-Recommendation-System-MOVICO
  cd MOVICO
  ```
  4. **Open** the **```MOVICO.ipynb```** file in Jupter Notebook. 


2. **Run-all** cells, by clicking on the ``` ">>" ``` (fast forward) option in the ```toolbar```, or the ``` "Restart & Run All Cells" ``` option from the ```"Kernel"``` menu.
     * This shall execute all the cells in the notebook.

4. **MOVICO Specific Instructions**:
     * **a]** In the cell number ```53```, you can ```enter the name of a movie``` in the widget (say, 'Toy Story') and click ```enter```.  This shall display personalized movie recommendations.
     * **b]** In cell number ```60```, you can enter ```any number from 1 to 9``` for both the inputs.
        * Enter the number of movies you would love to watch from the list of recommendations. Enter any number from 1 to 9 (say, 6)
        * Enter the number of movies from the list of recommendations that you would say are irrelevant to your taste. Enter any number from 1 to 9 (say, 5).
        * These can be used for ```fine-tuning models``` too.

7. **Outputs**: will be displayed after all the cells have ran. These shall include personalized movie recommendations based on your inputs.

  <p align="right">(<a href="#readme-top">back to top</a>)</p>
</br>

## Sample Screenshots

There are 3 models used in MOVICO:

* MODEL1 : USER-BASED COLLABORATIVE FILTERING
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/a96f5f41-7376-4410-83dc-2566663512c9)
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/e1f6e0b9-ea55-480d-aa1b-977dc476eecf)

  
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
* MOVICO outputs personalized movie recommendations based on users inputs.
* More effective recommendation systems can be buit using MOVICO.
* MOVICO also provides functions to test the recommendations received from the recommendation models.
  <p align="right">(<a href="#readme-top">back to top</a>)</p>
</br>

Thank you for exploring the MOVICO project. Happy movie recommending and watching! 🍿🎬
