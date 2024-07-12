# Food_4_Thought

** This project revisits and expands upon an original assignment completed as part of the "Data and Knowledge Engineering" course during my Bachelor's degree in Business Informatics at Wirtschaftsuniversität Wien (WU).

original date: June 2021 <br>
current date: July 2024

## Project Technical Description: <u>Integrating Relational Database Tables with RDF Data Sources.</u>

## Technologies: 
- Python
    - Pandas
- SQL
    - Relational DataBase (SQlite)
- SPARQL
    - RDF (Resource Description Framework)

## Theoretical Objective
The primary goal of this project was to develop a small application that integrates data from two distinct data models: traditional <b>relational databases</b> and <b>RDF</b> (Resource Description Framework) data sources, commonly used in the context of the <i>Semantic Web</i>.

This integration aims to demonstrate how knowledge (data) stored in different formats can leverage the strength of both data models to provide a more comprehensive and interconnected view of data.

## Project Theme: Food
### Introduction:
Food and nutrition are fundamental to human health and well-being, making the study of ingredients an essential theme for understanding and improving dietary habits and nutritional outcomes. Moreover, the same ingredients are used in different recipes around the world, carrying a wealth of cultural customs and knowledge.

### Project concrete objectives
The aim of this project is to:
1. create a Python application that integrates data from a relational table of common vegetables with nutritional RDF data from DBpedia.org.
2. The project will output a new CSV report with nutritional values derived from DBpedia and 
3. match recipes from DBpedia with our nutritional table.

????Steps:
 
Data Integration:

Combine a CSV table containing common vegetables and their scientific names with nutritional RDF data from DBpedia.
Data Output:

Generate a new CSV report that includes the nutritional values obtained from querying DBpedia.
Recipe Querying:

Query recipes from DBpedia and match them with our nutritional table in a Python application.????

### Significance:
By integrating diverse data sources and leveraging both relational and RDF models, this project not only enhances our understanding of food and nutrition but also showcases the cultural richness associated with ingredients used globally. This approach provides a comprehensive view of the nutritional content and culinary uses of common vegetables, contributing to better dietary choices and appreciation of global food traditions.



### Methodology:

Data Extraction:

Relational Database: Extracted data from various relational database tables using SQL queries.
RDF Sources: Retrieved RDF data using SPARQL queries to access and manipulate the RDF triples.
Data Transformation:

Mapping: Established mappings between the relational database schema and RDF schema to ensure compatibility and meaningful integration.
Normalization: Transformed the extracted data into a common format, resolving any schema differences and ensuring consistency.
Data Integration:

Merging: Combined the normalized data from both sources into a unified dataset. This involved linking relational data entities with RDF entities based on common attributes and relationships.
Enrichment: Enhanced the relational data with additional context and relationships derived from the RDF data, enriching the overall dataset.
Application Development:

Backend: Developed the backend logic to handle data extraction, transformation, and integration processes.
Frontend: Created a user interface to allow users to query and interact with the integrated data seamlessly.
APIs: Implemented APIs to facilitate data retrieval and integration tasks.
Technologies Used:

Relational Database Management System (RDBMS): For storing and managing relational data (e.g., MySQL, PostgreSQL).
RDF Store: For storing and querying RDF data (e.g., Apache Jena, RDF4J).
SQL: For querying relational data.
SPARQL: For querying RDF data.
Programming Languages: Used a programming language like Python, Java, or JavaScript for application logic.
Frameworks and Libraries: Utilized frameworks such as Flask or Django for backend development, and libraries like RDFlib for RDF processing.
Benefits:

Comprehensive Data View: By merging relational and RDF data, the application provides a more holistic view of the information, enabling richer insights and better decision-making.
Enhanced Interoperability: Facilitates interoperability between different data sources, allowing for more flexible and dynamic data integration.
Improved Data Utilization: Leverages the strengths of both relational and RDF data models, maximizing the value derived from the data.

## Conclusion:
This project demonstrates the potential of integrating relational database tables with RDF data sources, showcasing how diverse data models can be harmonized to create a powerful and flexible application. The resulting application not only bridges the gap between structured and semi-structured data but also opens up new possibilities for data analysis and application development.
