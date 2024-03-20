# Watsonx.data Sample Notebooks
These series of notebooks demonstrate various features that are found in the watsonx.data database. Click on the arrow to download the notebook to your local machine. Then use the Jupyter notebook file utility to import the notebooks into your environment.

!!! info "Python Libraries"

Many of the notebooks below rely on Python libraries to be installed. If you are creating your own Jupyter notebook environment, please refer to the *Running Notebooks on an External Server* notebook to load the proper libraries. Several of the notebooks use the Presto Magic commands to run SQL against the server. Make sure you have a copy of the Presto notebook in your environment in order for the SQL commands to work.

<!-- Begin Table -->
<div style="font-family: 'IBM Plex Sans';">
<table style="float:left; width: 650px; border-spacing: 10px; border-collapse: separate; table-layout: fixed; border: none;">
<!-- Begin Row -->
<tr>
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
<!-- Title -->
Introduction to Jupyter Notebooks
</div>
<div style="height: 180px"><p style="font-size: 14px">
<!-- Description -->
If you are not familiar with Jupyter notebooks, select this document to learn about the basics of navigating within a notebook.
</div>
<div style="height: 20px"><p style="font-size: 16px; text-align: right">
<!-- URL -->
<a href="../notebooks/An_Introduction_to_Jupyter_Notebooks.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>          
</div>        
</td> 
<!-- Begin Cell -->   
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height:300px; border: 1px solid black;">
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
<!-- Title -->            
Watsonx.data Credentials
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
All the credentials required to connect to the watsonx.data services can be found in this notebook. The notebook also includes links for download the Presto certificate files.
</div>  
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right">
<a href="../notebooks/Credentials.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>  
<!-- End of Cell -->         
</div></td>
<!-- End of Row  -->
</tr>
<!-- Start of Row -->
<tr>
<!-- Start of Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height:300px; border: 1px solid black;">
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
<!-- Title -->
User Administration
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
The watsonx.data developer edition does not provide a way of adding new users through the UI. The following notebook provides a series of commands that allows for the creation and deletion of users in the system.
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right">
<a href="../notebooks/Administration.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>          
<!-- End of Cell -->         
</div></td>
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">  
Presto Magic Commands
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
Presto Magic commands make it easy to run SQL in cells in your Jupyter Notebook as is, without any Python code. This notebook shows how to enable this feature for watsonx.data and provides some examples of its use.
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right">
<a href="../notebooks/Presto Magic.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>            
</div>            
</td>
<!-- End of Row  -->
</tr>
<!-- Start of Row -->
<tr>
<!-- Start of Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height:300px; border: 1px solid black;">    
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">             
Introduction to Presto SQL
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
Watsonx.data is based on open source PrestoDB, a distributed query engine that enables querying data stored in open file formats using open table formats for optimization or performance.  This notebook will examine some of the SQL features that are available in watsonx.data. 
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right">
<a href="../notebooks/Presto SQL.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>         
</div>            
</td>   
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">    
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2"> 
Presto Federation
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
If you are not familiar with Jupyter notebooks, select this document to learn about the basics of navigating within a notebook.
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right">
<a href="../notebooks/Presto Federation.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>               
</div>        
</td>
</tr>
<tr>       
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2"> 
Python with watsonx.data
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
This notebook will connect to watsonx.data using Python code and the prestodb library. The DBAPI interface is used to communicate to the watsonx.data Presto server. 
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right">
<a href="../notebooks/Python Example.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>           
</div>        
</td>    
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title -->
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
Pandas Dataframes with watsonx.data
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
Pandas dataframes are commonly used in Jupyter notebooks to analyze data. This code will connect to watsonx.data using a Pandas dataframe and display some data from an existing table that was created in Presto.            
Note that the certificate required for this notebook is provided in the environment.
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/Pandas Example.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>          
</div>            
</td>
</tr>
<tr>    
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">          
Accessing watsonx.data with Spark
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
This notebook demonstrates how Spark can connect to watsonx.data and manipulate the data. This system has a local Spark engine that will be used to access watsonx.data. This is a minimally configured Spark engine, but is sufficient to demonstrate the steps needed to connect to watsonx.data and access the data that resides in the catalogs. 
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/Spark and watsonxdata Integration.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>           
</div>            
</td>    
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
Connecting to Db2 
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
This notebook demonstrates connecting to the local Db2 server using Jupyter notebooks. 
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/Db2 Example.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>           
</div>        
</td>  
</tr>
<!-- Begin Row -->
<tr>  
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
Connecting to PostgreSQL
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
This notebook demonstrates connecting to the local PostgreSQL server using Jupyter notebooks. 
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/PostgreSQL Example.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>         
</div>            
</td>
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
Connecting to MySQL
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
This notebook demonstrates connecting to the local MySQL server using Jupyter notebooks. 
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/MySQL Example.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>           
</div>            
</td>
</tr>
<!-- Begin Row -->
<tr>  
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 50px"><p style="font-size: 18px">          
Connecting to Milvus
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
This notebook demonstrates connecting to the local Milvus vector database server using a Jupyter notebook.
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/Milvus Example.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>          
</div>            
</td>
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
Milvus Example
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
Watsonx is IBM's platform committed to injecting generative AI into services that span across customer's data lifecycle. This notebook focusses on the use of watsonx.data as a data repository that is used to feed data into the Milvus vector database. Output from a Milvus query can then be used to generate a prompt into watsonx.ai.
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/Milvus Example Usage.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a> 
</div>            
</td> 
<!-- Begin Row -->
</tr>
<tr>
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
Running Notebooks on an External Server
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
The Jupyter notebooks found in the watsonx.data server can be hosted on an external server. This notebook will provide details of what code needs to be installed to run the examples in another server.
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/External_Jupyter.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>     
</div>        
</td>   
<!-- Begin Cell -->
<td style="padding: 10px; text-align:left; vertical-align: text-top; background-color:#F7F7F7; width: 300px; height: 300px; border: 1px solid black;">
<!-- Title --> 
<div style="height: 40px"><p style="font-size: 18px;line-height: 1.2">
Presto Magic Source Code
</div>
<!-- Abstract -->
<div style="height: 180px"><p style="font-size: 14px">
This notebook contains the Presto magic code that is used in many of the notebooks in this list. Download this notebook (presto.ipynb) and use the <code>%run presto.ipynb</code> command to enable the magic commands in your code. This provides an easy to use interface to access Presto with the <code>%sql</code> command in your notebook.
</div>
<!-- URL -->   
<div style="height: 20px"><p style="font-size: 16px; text-align: right"><a href="../notebooks/presto.ipynb">
Download&nbsp;<img style="display: inline-flex; float:right;" src="./wxd-images/arrowblue.png"></a>      
</div>        
</td>   
</tr>    
</table>
</div>

Copyright (c) IBM 2024, George Baklarz [baklarz@ca.ibm.com]