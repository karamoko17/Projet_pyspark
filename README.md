# Pyspark Project

## 📖 **Table of Contents**
1. [Descriptions](#descriptions)
2. [Prerequisites](#Prerequisites)
3. [Project structure](#Project-structure)
4. [Installation](#Installation)
5. [Contribution](#Contribution)
6. [Author](#Author)

<h2 id="Descriptions">🧩 Descriptions</h2>

This project offers a series of hands-on tutorials to learn the basics of PySpark, a powerful programming interface for manipulating large datasets using Spark in Python. Organized in Jupyter notebooks, these tutorials offer a step-by-step approach suitable for all levels, from beginners to more experienced users.

Each module explores key concepts such as creating and manipulating Resilient Distributed Datasets (RDDs), one of Spark's fundamental structures. Participants will also learn how to implement complex algorithms such as calculating PageRank, which is used in search engines to rank web pages.

In addition, the tutorials include using Spark SQL to query distributed data and introduce machine learning techniques that leverage the power of Spark MLlib. This comprehensive learning path prepares users to take full advantage of Spark for their Big Data and Data Science projects.
   
<h2 id="Prerequisites">🤖 Prerequisites</h2>

- [Anaconda 2019+](https://www.anaconda.com/download/)
- Required Java 8/11. 
    - You can set the `JAVA_HOME` environment variable to point to the Java 8/11 folder you want to use for the project, from `Edit the system environment variables` window or `set JAVA_HOME=<path_to_java>` in command-line before running `jupyter notebook`. 
    - You may also install Java OpenJDK **inside** your Anaconda environment with `conda install openjdk`. The `JAVA_HOME` variable should be automatically updated for this environment only.


<h2 id="Project-structure">🏗️ Project structure</h2>

```
├── 1-beginner/
│   ├── 1-Initiation.ipynb
│   └── jupyter.png
├── 2-novice/
│   ├── 1-Initiation-RDD.ipynb
│   ├── 2-Pagerank-RDD.ipynb
│   ├── FL_insurance_sample.csv
│   └── pagerank.png
├── 3-advanced/
│   ├── 1-Initiation-SparkSQL.ipynb
│   ├── 2-Advanced-SQL-and-ML.ipynb
│   ├── FL_insurance_sample.csv
│   └── titanic.csv
├── cheatsheets/
│   ├── Jupyter-notebook.pdf
│   ├── Pyspark-RDD.pdf
│   ├── Pyspark-SQL.pdf
│   ├── Python.pdf 
│   └── conda-cheatsheet.pdf
├── docs/
│   ├── css/
│   │   └── custom.css
│   ├── images/
│   │   └── ...
│   ├── index.html
│   ├── intro.pdf
│   └── pyspark.pdf  
├── README.md
└── requirements.txt

```

<h2 id="Installation">🛠️ Installation</h2>

To install the project on your local machine, you can use the following command :
```
https://github.com/karamoko17/Projet_pyspark.git
```
Then move to the project directory and create a new conda environment with the following command :
```sh
conda create -n pyspark-tutorial python=3.11
conda activate pyspark-tutorial
pip install -r requirements.txt
# pip install bokeh jupyter numpy pandas psutil pyspark seaborn
```
We provide you with a requirements.txt which is used to download dependencies in a conda environment we will name pyspark-tutorial.

You can run the Jupyter notebook now.

<h2 id="Contribution">🤝 Contribution</h2>

Contributions are welcome! Feel free to open a ticket or submit a pull request to suggest improvements. Here's how you can get involved:

1. Fork the project.
2. Create a branch for your feature.
3. Make your changes and validate them with a clear message.
4. Push your changes to your branch on the remote repository.  
5. Submit a pull request to have your contribution reviewed.

<h2 id="Author">🎯 Author</h2> 
This project was designed and developed by KARAMOKO Awa, a student in Master 2 SISE (Statistics and Computer Science for Data Science) at Université Lumière Lyon 2.
