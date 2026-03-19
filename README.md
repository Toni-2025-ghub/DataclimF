# Dataclim
It's a tool that assists with data cleaning, imputation, and transformation, designed with easy-to-learn modules. 
This tool is free to use and streamlines the basic tasks of preparing datasets for machine learning model design.

# Dataclim modules

The modules it comprises are as follows:
Dataclim Module: Contains the elements shown in Figure 1.
Box 1: Information about the preloaded or searched dataset.
Box 2: General information about the loaded dataset is displayed.
Box 3: Preloaded datasets available in the interface are shown.
Box 4: Options are presented based on the quality of the dataset.
<img width="921" height="527" alt="image" src="https://github.com/user-attachments/assets/1633f32a-cae0-41a6-a6d2-e25e4c409b3e" />
Figure 1: Elements on the Dataclim initial screen.

Data module in graphs: Contains the elements shown in Figure 2.
Box 1: Data from the dataset loaded in the initial module.
Box 2: Options for attributes with missing data.
Box 3: Options for plotting attributes without missing data.
Box 4: Options for performing missing data imputation.
<img width="921" height="495" alt="image" src="https://github.com/user-attachments/assets/356278e4-b5bf-4cf6-828d-8abfc9f7cc9c" />
Figure 2. Description of the elements of the Data in Graphs module.

Transformation and Statistics Module: Contains the elements shown in Figure 3.
Box 1: Dataset data after cleaning and imputation.
Box 2: Transformed data using the options in Table 5.
Box 3: Option to download the dataset with transformed data.
Box 4: Statistics of the dataset attributes.
Box 5: Options for transforming the data.
<img width="921" height="516" alt="image" src="https://github.com/user-attachments/assets/c9e94e03-d4aa-4028-b7f7-8ff5f69953a7" />
Figura 3. Descripción de los elementos del módulo transformation and statistics.

Correlation graphs module: Includes the elements shown in Figure 4.
Box 1: Correlation matrix.
Box 2: Option to download correlation matrix data.
Box 3: Scatter plot with trend line of 2 attributes.
<img width="921" height="495" alt="image" src="https://github.com/user-attachments/assets/887c6e89-013b-40d6-be02-96d35184ab83" />
Figure 4. Description of the elements of the correlation and graphs module.

# Illustrative example
Use the breast cancer dataset and perform the pre-processing exercise following these steps:
Step 1: In the Dataclim module, select the breast cancer dataset in the Preloaded datasets section and click the Load button.
Step 2: Click the Imputation and Missing button.
<img width="921" height="532" alt="image" src="https://github.com/user-attachments/assets/e19e9962-8c74-4e09-b7c4-0ac2efb2b0f6" />
Step 3: In the Data in graphs module, observe the attributes with missing values.
Step 4: Choose the "node-caps" attribute in the "Attribute to impute" list, click the "mode" option in the "Method" section, and then click the "Impute" button.
Step 5: Repeat step 4 with the "breast-quad" attribute.
Step 6: Click the "Close window" button or the "X" button in the upper right corner to return to the initial Dataclim module.
<img width="921" height="496" alt="image" src="https://github.com/user-attachments/assets/85f2b8c5-f5d7-4f95-84d6-fa06f8c6a85f" />
Step 7: We click on the Transformation and Statistics button.
<img width="921" height="532" alt="image" src="https://github.com/user-attachments/assets/2c7be28f-83f4-4913-a555-0b673c45c3cf" />
Step 8: Click the "Change Data Categorical -> Integer" button in the Transformation section.
<img width="877" height="490" alt="image" src="https://github.com/user-attachments/assets/78aee397-ed6c-4670-81e8-b20c8cf12f55" />
Step 9: The encoded data is displayed in the Transformed data section, and the statistics are shown in the Statistics section.
Step 10: If desired, the user can download the transformed data in .csv format (Download transformed data button). Then, click the Close window button or the X button in the upper right corner to return to the initial Dataclim module.
<img width="921" height="279" alt="image" src="https://github.com/user-attachments/assets/dc1967f0-0fbe-487c-bdd4-146e2bd72924" />
Step 11: With the transformed data, you can click the "Correlation graphs" button to obtain the correlation matrix and design graphs.
<img width="921" height="518" alt="image" src="https://github.com/user-attachments/assets/f437b554-0b17-435b-b897-7c15a50e29cb" />

# Recommendations
Important! It is recommended that after pre-processing a dataset, you delete the current date (.csv) files from the Dataclim folder to avoid data confusion. 
In the "Data in Graphs" module, users can remove attributes by selecting them from the dropdown list and clicking the "Remove attribute" button (1). Also, remember that only attributes with complete data can be graphed (2).
<img width="921" height="491" alt="image" src="https://github.com/user-attachments/assets/91285cef-b6a2-437c-8a26-60aaf5ca8fdc" />
The "Download transformed data" option in the Transformation and Statistics module saves the file as "datos-transf.csv" in the Dataclim folder on the desktop. It is recommended to rename the downloaded file to avoid data loss when working with the preprocessing of another dataset.
<img width="921" height="521" alt="image" src="https://github.com/user-attachments/assets/5fd3a404-956c-498f-a330-af73d65221dc" />

# Steps to install the Dataclim tool:

1. Create a folder on your Desktop named Dataclim.
2. Download the .csv files (5 total) and save them in the Dataclim folder.
3. Click on Dataclim v1.0 in the releases section and download the Dataclim.exe file into the Dataclim folder.
4. Run the Dataclim.exe file.
