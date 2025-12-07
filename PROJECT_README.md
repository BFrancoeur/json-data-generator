# JSON Data Generator

## Problem
It takes way too much time to manually create even small data sets for testing an application.

## Solution
Create a tool that quickly generates as many rows of data as needed to conduct testing within app.

## Technical Requirements
* Developer-oriented. This tool is intended only for web developers and software engineers to use. 
* Easy to model. You create your own Object (class, if you prefer) and populate it with as many properties as you need. Enter the number of records that you need and a reference parent object (say, for car makes, models, years, etc.), and this tool will quickly create your JSON for you. 
* CRUD functions will be available for performing common tasks in the data set
* Abstract away blocks of code to simplify use

## Architecture -- ALL MODULES
* Create a data.json file for the dataset
* Create a parent object model file 
* Create an interface file for extending the parent object
* Create a generator module that uses the parent object (and interface, if necessary)
* Create a file for CRUD operations
* Create a web page for viewing the data (may need multiple templates)
