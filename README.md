
<a name="readme-top"></a>

# Movie-Recommendation-System-MOVICO

The repo ```Movie-Recommendation-System-MOVICO``` contains the ```AI-ML Project```, namely ***MOVICO***.
It is a ***'Movie Recommendation System'*** that mainly uses ***'Collaborative Filtering Techniques'***.

The project ```Movie-Recommendation-System-MOVICO``` was created as a project for the ```Machine Intelligence``` Course , which was part of the course ```UE20CS302```.

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

The repo ```Movie-Recommendation-System-MOVICO``` contains the project ```MOVICO```.

```MOVICO``` is a **MOVIe recommendation system**, and it mainly focuses and utilizes **COllaborative filtering techniques**.

The name ```MOVICO``` originates from the fusion of ```MOVIe COllaborative``` (i.e., MOVI-CO), encapsulating the essence of **Collaborative Movie Recommendations** with precision and accuracy.

The various collaborative filtering techniques utilized are ```KNN```, ```SVD```, etc...



Welcome to MOVICO!!

<br>


### <b>Files :</b>

  In the ```'MOVICO' Directory``` there are several files:

  * <i>Project Python Code File-</i> `MOVICO.ipynb`

  * <i>Dataset Files-</i> `movies.csv`, `ratings.csv`
    
<br>

### <b>Repository Structure :</b>

<details>
  <summary color= blue ><u><b><i>MOVICO repo structure</i></b> click...</u></summary>

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

  </details>

<br>    
<p align="right"><a href="#readme-top">Back to TOP</a></p>

<a name="a2"></a>

##  Prerequisites and Techstack

### Language:
* Python

### Prerequisites: 
* Basic understanding of AI-ML algorithms
* KNN 
* SVD

### Other Tools:
* Anaconda
* Jupyter notebook

### Python Modules:
  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scipy
  * Datetime
  * Re
  * Sklearn
  * Ipywidgets
  * IPython
  * Surprise

<br>  
<p align="right"><a href="#readme-top">Back to TOP</a></p>

<a name="a3"></a>

## Steps for Execution

<br>

To run MOVICO, follow these simple steps: <br>
<b>
Clone > Launch > Navigate > Open > Run-all > MOVICO Specific Instructions > Outputs > CLOSE </b>
<br>
<br>

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
   

     * **a]** In the cell number ```60```,
     
       you can enter ```any number from 1 to 9``` for ```both``` the inputs.

       
        * Enter the number of movies you would love to watch from the list of recommendations. Enter any number from 1 to 9 (say, 6)
          
        * Enter the number of movies from the list of recommendations that you would say are irrelevant to your taste. Enter any number from 1 to 9 (say, 5).
          
        * These can be used for ```fine-tuning models``` too.

   
     * **b]** In the cell number ```53``` ,
     
       you can ```enter the name of a movie``` in the widget, and click ```enter```.
       
       
       * Enter any movie name (say, 'Toy Story'), and press *enter*.

       * This shall display ```personalized movie recommendations```.

    <br>

7. **Outputs**: will be displayed after all the cells have ran.
  
   These shall include ```personalized movie recommendations```, ```evaluation``` and ```error tracking``` based on your inputs.
   
<br>

<p align="right"><a href="#readme-top">Back to TOP</a></p>

<a name="a4"></a>

## Sample Screenshots

<br>

There are 3 models used in MOVICO:

<br>

* MODEL1 : USER-BASED COLLABORATIVE FILTERING
  
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/a96f5f41-7376-4410-83dc-2566663512c9)
  * ![image](https://github.com/ankitacoder3/Movie-Recommendation-System-MOVICO/assets/73939061/783d5481-a29b-415f-be1a-4f63f370e805)

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

<a name="a5"></a>

## Usage

* MOVICO can be used to recommend movies to users, based on ***collaborative filtering techniques*** .

* MOVICO outputs ***personalized movie recommendations*** based on users inputs.

* MOVICO also ***evaluates the recommendations*** received, from the recommendation models.
  
* More ***effective recommendation systems*** can be built using MOVICO.

* The project `MOVICO` or `Movie Recommendation System` could also be used as an `AI-ML Project`, for courses like `Machine Intelligence Project`, or specifically as a project for the courses `UE20CS302` or ue20cs302.
  
</br>
<p align="right"><a href="#readme-top">Back to TOP</a></p>

<a name="end"></a>
<br>

Thank you for exploring the MOVICO project. Happy movie recommending, evaluating and watching! 🍿🎬


###

