# Data analysis exam June 2023

The present is the Github repository containing the information on how to pull the docker image and how to run the docker. Moreover, information about how to execute the code written to solve the exam tasks are reported.

## Download the docker image from Docker hub 
The image can be pulled from my Docker hub repository 
```
https://hub.docker.com/r/francescatornatore/data_analysis_exam_23
```

The image can be pulled by executing on the terminal the command:
```
docker pull francescatornatore/data_analysis_exam_23
```

## Run the docker 
Once the image has been pulled, the docker can be run typing the command 
```
docker run -p8888:8888 -it francescatornatore/data_analysis_exam_23
```
By using the link provided by the execution of the previous command and pasting it on an Internet browser, you are inside the Jupiter Lab docker. 

## Execute the code 
Once inside the Jupiter Lab docker, type on the docker terminal 
```
cd /bin/Exam_FT
```
By typing this command, it is possible to be located inside the Exam_FT folder, in which are mounted all the files used to perform the gene expression analysis. 

By typing 
```
ls
```
different files will be listed: 
* Exam_FT.ipynb (which is the Jupiter Lab notebook that I have written to solve the exam requirements);
* Exam_FT.r (which is the R executable script containing all the code written to answer the exam questions and has been exported from the Exam_FT.ipynb notebook as requested);
* different text files containing the raw count matrix and the data downloaded from the Gene Ontology website, used as input files for the analysis.

Type on the docker terminal 
```
Rscript Exam_FT.r
```
In this way, the code written to answer the questions of the exam will be executed.

## Read the commented code 
The commented code as well as all the other sections of the exam project can be read in the HTML file exported from the Exam_FT.ipynb notebook, provided by email and also contained in this repository. 

The HTML file is organized in 4 different sections: 
* Introduction: brief introduction about the biological problem investigated in the dataset 
* Data Description: description of the dataset used in the analysis 
* Results: the code written to perform the differential expression analysis, commented and supported with appropriate graphs and plots 
* Discussion: brief conclusions and perspectives on the data obtained


