# Food_4_Thought: Concepts and Theory

### The Semantic Web:
refers to an extension of the World Wide Web where information is structured in a way that allows it to be processed more effectively by machines. It aims to make web content more meaningful and interpretable by creating a layer of semantic data that provides context and relationships between different pieces of information.

#### Key Concepts of the Semantic Web:
- <b>Semantic Data:</b> Information is encoded using standards such as RDF (Resource Description Framework), which represent data as triples (subject-predicate-object statements).

- <b>Ontologies:</b> define the relationships and properties of entities in a domain. They provide a shared understanding and vocabulary for describing concepts, allowing for more precise and interoperable data integration.

- <b>Linked Data:</b> The practice of exposing, sharing, and connecting structured data on the web using URIs (Uniform Resource Identifiers) and RDF triples. This enables data to be interconnected across different datasets and domains.

- <b>Interoperability:</b> By using RDF and ontologies, the Semantic Web promotes data integration and interoperability among different applications and systems.


### DBpedia:
DBpedia is a crowd-sourced community effort to extract structured information from Wikipedia and make this information available on the web. <br>
The DBpedia ontology is a structured framework of classes and properties used to describe entities and their relationships within the data extracted from Wikipedia.
https://www.dbpedia.org/

### RDF (Resource Description Framework):
Is a framework for representing information about resources in the web. It provides a structured way to describe resources using triples, which consist of subject-predicate-object statements. RDF enables data interoperability and integration by offering a standardized format for expressing relationships and metadata about resources on the internet.

### SPARQL:
(pronounced "sparkle") is a query language and protocol used for querying and manipulating data stored in RDF format. It stands for SPARQL Protocol and RDF Query Language.<br>
It is a W3C standard, ensuring compatibility and interoperability across different RDF databases and applications.

- SPARQL provides a syntax for retrieving and manipulating data stored in RDF triples.
- Queries in SPARQL use triple patterns (subject-predicate-object) to specify conditions that the data must satisfy.
- It supports querying RDF graphs, performing aggregations, filtering results, and sorting.
- SPARQL includes a protocol for sending queries to remote RDF databases and receiving results.

- for example: 
```
SELECT ?name
WHERE {
  <http://example.org/person1> <http://xmlns.com/foaf/0.1/name> ?name .
}
```



