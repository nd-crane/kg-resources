# DVC-Test

A simple repo demonstrating how DVC can be used to pull in data from a remote source. In this case, it is pulling in examples and data from the KGLab repo. The eventual hope is that this can be used as a centralized learning tool to get undergraduate students up to speed on knowledge graphs, ontologies, and the various tools and resources surrounidng them. 

## How to pull in the data

After you have cloned the repo into a local environment, run the following command

`dvc pull`

DVC will then pull in the data from the URL's specified in the .dvc files. It's like magic!