# Pi_value
Once logged into AWS. Goto services and check for EMR.
Goto Notebooks and click on *create new notebook*(I have named it as Pi_calculation). While creating the notebook you can either use existing cluster or create a new cluster. 
![Cluster](https://user-images.githubusercontent.com/56847819/79587747-f9a9d100-80a0-11ea-97b4-86860d32a6d2.JPG)

Here we are creating a new cluster while creating the notebook itself with a single node. Ideally whenever we create on single node all components run on master node i.e core node and task node are not utilized here.

Keep all other settings at default and click on *Create Notebook*

Wait for the status of notebook to change from *pending* to *ready*. Once it is ready *open jupyter notebook*

Change Kernel type to Pyspark by clicking on *Kernel* and select *Pyspark*

Select Spark Job Progress to know the elapsedtime to run the application. 
![image](https://user-images.githubusercontent.com/56847819/79589085-d8e27b00-80a2-11ea-85c1-f8d40801c21f.png)

