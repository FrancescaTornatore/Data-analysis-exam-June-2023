# Data analysis exam June 2023

The present is the Github repository containing the information on how to pull the docker image and how to run the docker. Moreover, information about how to execute the code written to solve the exam tasks are reported.

## Downloading the docker image from Docker hub 
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
By using the link provided by the execution of the previous command and pasting it an an Internet broweser, you are inside the Jupiter Lab docker. 

## Executing the code 
Once inside the Jupiter Lab docker, type on the docker terminal 
```
cd /bin/Exam_FT
```
By typing this command, it is possible to be located inside the Exam_FT folder, in whichare mounted all the files used to perform the gene expression analysis. 

By typing 
```
ls
```
different files will be listed: 
Markup : * Bullet list
