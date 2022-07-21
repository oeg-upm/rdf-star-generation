# Resources for RDF-star generation


## SPARQL-anything test-cases
The  SPARQL-anything test cases are used to determine the conformance to the [RDF-star specification](https://w3c.github.io/rdf-star/cg-spec/editors_draft.html) of tools that execute SPARQL-anything queries.

In the folder sparql-anything-test-cases you can find the different test cases. Each test case is comprised in a single folder, and contains three types of files:
- Zero or more files containing the data sources in CSV format
- One file with the SPARQL-anything query, called query.rq, in the SPARQL format.
- Zero or one file with the expected RDF-star extracted from the [N-Triples RDF-star test-cases](https://w3c.github.io/rdf-star/tests/nt/syntax/). No file is provided if an error is expected that must halt the generation of the RDF-star.

Each RDF-star test case is transformed to two different SPARQL-anything test-cases: SATCXXXa cases do not contain joins among sources, while SATCXXXb cases do.

## Use-cases

Two real use-cases for generating RDF-star from heterogeneous data sources. One is about software metadata extraction and another one extracted from biomedical research literature. Both provide: mapping in RML-star, queries for SPARQL-antyhing, and data/schema.


## License
This code is copyrighted under the Apache 2.0 License
