<a name="readme-top"></a>


# Movie-Recommendation-System-MOVICO

```MOVICO``` is a ```MOVIe recommendation system```.

In ```MOVICO```, ```COllaborative filtering techniques``` are majorly given importance.

<br>

<details open>
  <summary color= blue >Table of Contents</summary>
<li> <a href="#a1">Introduction</a></li>
<li> <a href="#a2">Prerequisites and Techstack</a></li>
<li> <a href="#a3">Steps for Execution </a></li>
<li> <a href="#a4">Sample Screenshots </a></li>
<li><a href="#a5">Usage </a></li>
<a href="#end"><u><i>Skip to END...</i></u></a>
</details>
</br>

<a name="a1"></a>
## Introduction

```Movie-Recommendation-System-MOVICO``` contains the project ```MOVICO```.

```MOVICO``` is a ```Movie Recommendation System```, and it mainly focuses and utilizes ```Collaborative Filtering Techniques```.

The name ```MOVICO``` originates from the fusion of ```MOVIe COllaborative```, encapsulating the essence of *Collaborative Movie Recommendations* with precision and accuracy.

The various collaborative filtering techniques utilized are ```KNN```, ```SVD```, etc...

<br>

### <b>Files :</b>

  The following files are used in ```MOVICO```-
  * <i>Project Python Code File-</i> `MOVICO.ipynb`
  * <i>Dataset Files-</i> `movies.csv`, `ratings.csv`
    
<br>

### <b>Repository Structure :</b>

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
    
  <p align="right"><a href="#readme-top">Back to TOP</a></p>
</br>

<a name="a2"></a>
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
    
  <p align="right"><a href="#readme-top">Back to TOP</a></p>
</br>

<a name="a3"></a>
## Steps for Execution
<br>

To run MOVICO, follow these simple steps: <br>
<b>
Clone > Launch > Navigate > Open > Run-all > MOVICO Specific Instructions > Outputs > CLOSE </b>
<br><br>

 1. **Clone** the ``` 'Movie-Recommendation-System-MOVICO' ``` github repository.
  ```sh [
  git clone https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO.git
  ```
<br>

2. **Launch** ```Jupyter Notebook``` on your system, using Anaconda.
   
<br>

3. **Navigate** to the ``` 'MOVICO' ``` Directory in that.
  ```sh
  cd Movie-Recommendation-System-MOVICO
  cd MOVICO
  ```
<br>

  4. **Open** the **```MOVICO.ipynb```** file in Jupter Notebook. 

<br>

5. **Run-all cells**,
  
   by clicking on the ``` ">>" ``` (fast forward) option in the ```toolbar```,

   or the ``` "Restart & Run All Cells" ``` option from the ```"Kernel"``` menu.



   This shall execute all the cells in the notebook.
   
<br>

6. **MOVICO Specific Instructions**:
   
   <br>


     * **a]** In the cell number ```60```,
     
       you can enter ```any number from 1 to 9``` for both the inputs.

       <br>
       
        * Enter the number of movies you would love to watch from the list of recommendations. Enter any number from 1 to 9 (say, 6)
          
        * Enter the number of movies from the list of recommendations that you would say are irrelevant to your taste. Enter any number from 1 to 9 (say, 5).
          
        * These can be used for ```fine-tuning models``` too.

    <br>

   
     * **b]** In the cell number ```53``` ,
     
       you can ```enter the name of a movie``` in the widget (say, 'Toy Story')

       and click ```enter```.

       This shall display <i>personalized movie recommendations</i>.

    <br>

7. **Outputs**: will be displayed after all the cells have ran.
  
   These shall include ```personalized movie recommendations```, ```evaluation``` and ```error tracking``` based on your inputs.
   
<br>

<br>

  <p align="right"><a href="#readme-top">Back to TOP</a></p>
</br>

<a name="a4"></a>
## Sample Screenshots



There are 3 models used in MOVICO:


<br>

* MODEL1 : USER-BASED COLLABORATIVE FILTERING
  
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/a96f5f41-7376-4410-83dc-2566663512c9)
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/e1f6e0b9-ea55-480d-aa1b-977dc476eecf)

  <br>
  
* MODEL2 : KNN-BASED COLLABORATIVE FILTERING
  
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/cf882aa5-8474-4091-84f8-7dcbe38336e6)
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/531ae7b9-4492-4f7b-83b5-c20c89fdd7a2)

<br>

* MODEL3 : SVD-BASED COLLABORATIVE FILTERING
  
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/a3d60253-b240-40bc-bb11-663cdf3b6269)
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/5e754a09-c89f-4abf-8409-7983223d1680)

<br>
  <p align="right"><a href="#readme-top">Back to TOP</a></p>
</br>

<a name="a5"></a>
## Usage

<br>

* MOVICO can be used to recommend movies to users, based on ***collaborative filtering techniques*** .

  
* MOVICO outputs ***personalized movie recommendations*** based on users inputs.

* MOVICO also ***evaluates the recommendations*** received, from the recommendation models.
  
* More ***effective recommendation systems*** can be buit using MOVICO.

  
  
  <p align="right"><a href="#readme-top">Back to TOP</a></p>
</br>
<a name="end"></a>
Thank you for exploring the MOVICO project. Happy movie recommending, evaluating and watching! 🍿🎬
