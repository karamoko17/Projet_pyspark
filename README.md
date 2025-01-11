# Pyspark Project

Welcome to the Pyspark tutorial section.

The courses comprises of 4 folders containing notebooks. Folders and notebooks are sorted in order of difficulty given their name, so you should follow the numerotation. For example, you should finish all notebooks in `1-beginner` before starting `2-novice`. Likewise, when doing `2-novice` finish the `1-...` notebook before doing `2-...`.

Inside each notebook, we have documented a number of questions and unimplemented code cells answering the question, followed by a code cell which acts as test cases for the function called `Graded cell`. Your submission will be graded on how many test cases you pass given your implementation of the previous function. 

**PS**: The instructor has hidden test cases on his side so don't try to circumvent the system by just returning the expected value in your method.

<h2 id="Prerequisites">🤖 Prerequisites</h2>

- [Anaconda 2019+](https://www.anaconda.com/download/)
- Required Java 8/11. 
    - You can set the `JAVA_HOME` environment variable to point to the Java 8/11 folder you want to use for the project, from `Edit the system environment variables` window or `set JAVA_HOME=<path_to_java>` in command-line before running `jupyter notebook`. 
    - You may also install Java OpenJDK **inside** your Anaconda environment with `conda install openjdk`. The `JAVA_HOME` variable should be automatically updated for this environment only.


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

Notes: 
- you may run into `java.io.FileNotFoundException: HADOOP_HOME and hadoop.home.dir are unset.` warnings on Windows. Do not worry about it, they are necessary for remote connections only.
- you may need to define the `PYSPARK_PYTHON` environment variable so Spark workers can point to the correct Python command.

When you are done with the environment, don't forget to deactivate your Anaconda environment : `conda deactivate`

## Submit

At the end of the course, send your assignments by email to the instructor.

**BEFORE SENDING:**

- Check that your Jupyter notebook runs from start to finish when you run it from top to bottom, using `Kernel > Restart & Run All`. Clean up all unecessary cells. Your grade is based on how far the execution of the notebook goes from top to bottom without me going in.
- Don't rename the files, and preserve the folder structure when sending the zipped project, even if you did not complete the notebook. It should look like:

```
├── 1-beginner
│   └── 1-Initiation.ipynb
├── 2-novice
│   ├── FL_insurance.csv
│   ├── 1-Initiation-RDD.ipynb
│   └── 2-Pagerank-RDD.ipynb
└── 3-advanced
│   ├── FL_insurance.csv
│   ├── titanic.csv
│   ├── 1-Initiation-SparkSQL.ipynb
│   └── 2-Advanced-SQL-and-ML.ipynb
├── cheatsheets/
│   ├── conda-cheatsheet.pdf
│   ├── Jupyter-notebook.pdf
│   ├── Pyspark-RDD.pdf
│   ├── Pyspark-SQL.pdf
│   └── Python.pdf
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

<h2 id="Contribution">🤝 Contribution</h2>

Contributions are welcome! Feel free to open a ticket or submit a pull request to suggest improvements. Here's how you can get involved:

1. Clone the project.
2. Create a branch for your feature.
3. Make your changes and validate them with a clear message.
4. Push your changes to your branch on the remote repository.  
5. Submit a pull request to have your contribution reviewed.

<h2 id="Author">🎯 Author</h2> 
This project was designed and developed by KARAMOKO Awa, a student in Master 2 SISE (Statistics and Computer Science for Data Science) at Université Lumière Lyon 2.
