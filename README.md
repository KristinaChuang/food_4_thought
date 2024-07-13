# Food_4_Thought

** This project revisits and expands upon an original assignment completed as part of the "Data and Knowledge Engineering" course during my Bachelor's degree in Business Informatics at Wirtschaftsuniversität Wien (WU).

original date: June 2021 <br>
current date: July 2024

### Usage
- Clone the repository:

```
git clone https://github.com/KristinaChuang/food_4_thought.git 
cd food_4_thought 
```
 
- Set up a virtual environment:

```
virtualenv venv 
source venv/bin/activate
 ```

- Install the dependencies from requirements.txt:

```
pip install -r requirements.txt
```
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

#### Steps:
 
- Data Integration:

Combine a CSV table containing common vegetables and their scientific names with nutritional RDF data from DBpedia.
- Data Output:

Generate a new CSV and HTML report that includes the nutritional values obtained from querying DBpedia.
And computing the Kilocalories for each food.
- Recipe Querying:

Query recipes from DBpedia and match them with our nutritional table in a Python application. Save to txt file.

### Significance:
By integrating diverse data sources and leveraging both relational and RDF models, this project not only enhances our understanding of food and nutrition but also showcases the cultural richness associated with ingredients used globally. This approach provides a comprehensive view of the nutritional content and culinary uses of common vegetables, contributing to better dietary choices and appreciation of global food traditions.


## Conclusion:
This project demonstrates the potential of integrating relational database tables with RDF data sources, showcasing how diverse data models can be harmonized to create a powerful and flexible application. The resulting application not only bridges the gap between structured and semi-structured data but also opens up new possibilities for data analysis and application development.
