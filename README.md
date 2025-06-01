# Churn_Prediction
## Steps to Integrate SQL Server with Power BI and get Prediction Data from Machine Learning Model for Churn Prediction Visualization:

### SSMS and SQL Server

Download and install SQL Server Management Studio (SSMS) to manage and query SQL Server databases.

https://learn.microsoft.com/en-us/ssms/install/install

Download and install SQL Server (SQL Express) to Enable database operations. 

https://www.microsoft.com/en-in/sql-server/sql-server-downloads

Check if SQL Server is Running :

Open Command Prompt and run the command sqlcmd -L to list available SQL Servers.

Alternatively, use sqlcmd -S (Your Device Name)\SQLEXPRESS -E to connect to a specific instance.

Connect to SQL Server via SSMS :

Open SSMS and connect to the SQL Server instance using (Your Device Name)\SQLEXPRESS as your Server Name.

Write and Execute SQL Queries :

In SSMS, open a new query window and write your SQL queries to interact with the database.

### Power BI

Load Data into Power BI :

Connect Power BI to SQL Server and load the data directly from the database into Power BI.

Transform Data in Power BI :

Use Power BI’s Power Query Editor to transform the data as per your requirements.

In the Model view, create relationships between newly created tables and reference the original tables.

Create Churn Prediction Visualizations :

Using Power BI, visualize the churn prediction results through various charts and tables.

### Machine Learning

Download Anaconda Prompt: [Anaconda](https://www.anaconda.com/download/success)

Run these commands in Command Prompt to download and run Jupyter Notebook :

```bash
pip install jupyterlab
```
```bash
jupyter lab
```
```bash
pip install notebook
```
```bash
jupyter notebook
```

Download Required Dependencies :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

Train the Random Forest Model :

Train a Random Forest model to predict customer churn using the data in Power BI or other external tools.

Store the Predicted Data :
Save the Churn prediction results in a new file and note the file location.

### Power BI Part
Load Views Data into Power BI :
Load the two files containing views data into Power BI for further analysis.

Check and Verify the Predicted Data :
Verify the saved predicted churn data in the specified file location.

Use Predicted Data for Final Visualization :
Use the churn prediction data to create meaningful visualizations in Power BI, reflecting the model’s predictions.


## SUMMARY AND PREDICTION DASHBOARDS PREVIEWS:
![Summary](https://github.com/user-attachments/assets/a5b7cfd4-a427-4a75-b0c6-858f9098c9e7)
![Churn Prediction](https://github.com/user-attachments/assets/be6ebb5e-7934-4217-9c13-12032f5405e3)
