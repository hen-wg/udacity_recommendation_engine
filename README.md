# Recommendation Engine Project
This project forms part of the [Udacity Data Science nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025?utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_term=143524484639&utm_keyword=udacity%20data%20science_p&gclid=Cj0KCQiA5NSdBhDfARIsALzs2EAHpUX_4D3aZrBcu_PbklsCJYBWFEupJ-i6mpiKLVpCNy_7u8hDLVoaAje4EALw_wcB). 

It uses an anonymised dataset provided by [IBM Watson Studio](https://dataplatform.cloud.ibm.com/gallery?context=cpdaas) which contains data of user's interactions with articles on the IBM Watson Studio platform. The goal of the project is to build a recommendation engine that recommends articles to users based on their interactions with articles.

# Project Folders
Please see below a description of each of the folders and files of interest.                                       

### Data                                               
- Input data provided by IBM Watson Studio.                               

### Other files                                               
- Recommendations_with_IBM (Jupyter notebook) that contains the code for the project.
- The file `project_tests.py` contains verification tests for the project.

# Getting Started
This project uses remote development through [Windows Subsystem for Linux 2](https://docs.microsoft.com/en-us/windows/wsl/install) , or running natively from Windows. The environment is controlled using `venv` and `pip` for package management.

## Installation process
In order to get the project up and running, open a terminal window and run the following commands:

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
