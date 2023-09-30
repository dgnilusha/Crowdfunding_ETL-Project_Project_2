# Crowdfunding_ETL
# ETL Mini Project

## Overview

In this mini-project, we work collaboratively with a team to create an ETL (Extract, Transform, Load) pipeline using Python and Pandas. The goal of the project is to extract data from Excel files, transform it, and ultimately load it into a Postgres database. The project consists of several tasks that will guide you through the process of creating a Category DataFrame, a Campaign DataFrame, and a Contacts DataFrame.

### Team Members
- Brandon
- Judy
- Nilusha
- Zohair

### Create the Category and Subcategory DataFrames

Extract and transform the data from the "crowdfunding.xlsx" Excel file to create a Category DataFrame. This DataFrame should contain the following columns:

- "category_id": Sequential identifiers from "cat1" to "catn" representing unique categories.
- "category": Contains only the category titles.

The resulting Category DataFrame should look like this:

| category_id | category        |
|-------------|-----------------|
| cat1        | Technology      |
| cat2        | Art             |
| cat3        | Music           |
| cat4        | Food            |
| ...         | ...             |

In this part of the project, we clean and manipulate the data, including renaming, reordering, and dropping columns as needed.

### Create the Campaign DataFrame

Create a Campaign DataFrame by extracting and transforming data from the "crowdfunding.xlsx" file. This DataFrame should contain information about crowdfunding campaigns. Your transformations should include renaming, reordering, and dropping columns to ensure that the data is organized effectively.

### Create the Contacts DataFrame

Extract and transform the data from the "contacts.xlsx" Excel file to create a Contacts DataFrame. This DataFrame should include relevant contact information for the crowdfunding campaigns.

### Create the Crowdfunding Database

You will upload the transformed data from the Category, Campaign, and Contacts DataFrames into a Postgres database. Define the table schemas appropriately to match the data structures of each DataFrame.

## Conclusion

In this mini-project, we have learned how to build an ETL pipeline using Python and Pandas. We have successfully extracted, transformed, and loaded data from Excel files into a Postgres database, creating a foundation for further analysis and insights.
