# TMDb_Dataset_Analysis
In this project, we will investigate the **<u>'TMDb Movie Data' dataset</u>**. This dataset is selected from <a href=https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf>Here</a> to fulfill the requirements of Project no. 2 in **<u>Egyptian MCIT / ITIDA FWD</u>** initiative course **<u>Data Analysis - Professional Nanodegree</u>** taken through **<u>Udacity</u>** online platform. The goal of this project is to <font color =blue>analyze</font>, <font color =blue>explore</font> and <font color =blue>visualize</font> a dataset in a way that would allow <font color =blue>concluding</font> results to help <font color =blue>answering</font> related questions.  
This dataset represent information about <font color =blue>10,000 movies</font> collected from a specific source. The goal is to answer the following questions:
1. **<font color =blue>Which genres are most popular from year to year?</font>**
2. **<font color =blue>What properties are associated with high revenue movies?</font>**

To run this project code successfully, the following packages must be installed and imported to the project.

1. **numpy**, **pandas**, **matplotlib** and **seaborn**:  
All of them are considered standard packages within this course and are assumed to be available already. In case any of those packages is not available, please install it (using the method appropriate to the available setup) first.
<br><br>
2. **IMDbPy**:  
- General to any dataset, missing inputs are not uncommon. The majority of these inputs in this dataset cannot be inferred using the standard **pandas** filling methods, because they are mainly characteristics of the movie being analyzed. As an example, how would one fill a missing 'genre' of a movie?
- As such it became of paramount importance to be able to get such data from another source. The source in this case, is the **<a href=https://www.imdb.com><u>IMDb website</u></a>**.
- There are many ways to scrape the website:
    - Screen scrape a webpage: requires massive works and is highly prone to errors.  
    - Use an API: most of the APIs found require registration for a key to be used. This imposes constraints for code sharing and reproducability.  
    - <font color=blue>Weapon of Choice:</font> Use **IMDbPy** python package and its <a href=https://imdbpy.readthedocs.io/en/latest/>Documentation</a>. This is a <font color = blue>GPL License</font> python package for retrieving and managing the data of the **<u>IMDb</u>** movies database. Use the Documentation reference to install it to be able to run this project.
