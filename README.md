# Paine-Lewis-Portfolio

Included on this site are two separate projects. See project descriptions and links to code below. 

**ASC 842 Automation**

In this project, I utilize Python and SQL to create a framework for automating lease accounting under ASC 842. This project was done with a consulting or audit context in mind, and the final product is designed to be used by a team of several people to track lease information and prepare lease reporting for several companies. The interface is currently a Juypter Notebook (linked below), but I have plans to build a better interface in the future. 

The project first establishes a database hosted in Railway, enabling any team member with access to the internet to add lease information or pull reports (I did not include a link to this code). From there, the first notebook is an interface through which an user can write, update, or delete lease information into the database. To add a lease, an user establishes a company, then adds leases to a company. Each lease requires the input of basic information about the lease terms (for the purpose of lease classification under ASC 842), and a payment schedule. A link to this Notebook is below:

[ASC 842 Automation Part I](https://github.com/PaineLewis/Paine-Lewis-Portfolio/blob/68bf7362b15b5b8e0412cfa7b43d4a9e559191b9/ASC_842_Automation_Part_1.ipynb)

After all leases have been added for a copmany, Part II allows users to pull reports. A link to the Part II Notebook is below, as well as a link to a sample report. This report contains all of the necessary information to compile the lease section of the company's financial statements, including an amortization for each lease individually, and a summary of all lease activity in the period segregated by operating and finance leases. 

[ASC 842 Automation Part II](insertlink)

[Sample Output](inputlink)

This project demonstrates skills relevant to any accounting process that requires aggregating data from various sources into a centralized database, then extracting and preparing the data for use in financial reporting. 

**Inventory Management & Forecasting**

The second project is an experiment applying different forecasting techniques to supplement a basic inventory management strategy. The link below contains a more detailed description/walkthrough of the project, as well as all of the project code. 

[Inventory Manamgement Project](https://github.com/PaineLewis/Data-Science-Portfolio/blob/85cfcabb06ed7e64bf7e2d3c558cad9bd2a42c6f/Exponential%20Smoothing%20and%20Inventory%20Management.ipynb)

This project demonstrates the use of holt-winters forecasting, knowledge of inventory management strategy, and knowledge of the pandas package in Python. 
