# datafun-06-eda

This project entails analyzing data to extract valuable and actionable insights.

## Process

1. Create a project repository name datafun-06-eda in GitHub with a default README.md file.
2. Clone datafun-06-eda onto a local machine using the command ```git clone https://github.com/kwameape123/datafun-06-eda```
3. Open project repository in VS Code.
4. Create a virtual environment name .venv to hold project dependencies using the command ```py -m venv .venv```
5. Activate the project virtual environment using the command ```.venv\Scripts\Activate```
6. Create a .gitignore file to list resources to be excluded from source control using the command ```ni .gitignore```
7. Create a requirements.txt folder to list project dependencies using the command ```ni requirements.txt```
8. Install project dependencies into .venv folder using command ```py -m pip install -r requirements.txt```
9. Sync contents of project repository on local machine with that of GitHub using the commands below in order.
    ```git add .```
    ```git commit -m "initial commit"```
    ```git push origin main```
10. Identify and describe project dataset. Refer to the subsection named "Dataset" for additional details.
11. Perform exploratory data analysis. Refer to jupyter notebook name arnoldatchoe_eda.ipynb for details.
12. Sync contents of project repository on local machine with that of GitHub using the commands below in order.
    ```git add .```
    ```git commit -m "initial commit"```
    ```git push origin main```

## Dataset

This project makes use of the "taxis" dataset included in the seaborn library. A copy of the csv_file containing this dataset
was obtained from https://github.com/mwaskom/seaborn-data/blob/master/taxis.csv. The csv_file has been copied to our project repository.
Dataset contains information on yellow and green taxi trips in New York city for march of 2019. The dataset was collected by various technology providers under the Taxicab and Livery Passenger Enhancement Programs(TPEP/LPEP) and made available to NYC Taxi an Limousine Commission. The dataset include features such as pickup and drop-off date/time, pickup and drop-off location, trip distance,itemized fares, rate types, payment types and passenger count reported by drivers. This brief description of the project dataset was obtained from https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page. Refer to project jupyter notebook for exploratory data analysis and detailed understanding of project dataset.

