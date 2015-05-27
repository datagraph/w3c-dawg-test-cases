
# W3C DAWG test cases

This repository comprises the W3C SPARQL 1.0 and 1.1 test suites in consolidated form.
The initial state corresponds to the served content

- http://www.w3.org/2001/sw/DataAccess/tests/data-r2/ (for SPARQL 1.0)
- http://www.w3.org/2009/sparql/docs/tests/data-sparql11/ (for SPARQL 1.1)

coincident with its creation. That state is reflected in the master branch.
Additional branches serve specific implementations:

- datagraph : Datagraph's SPARQL implementation


## Datagraph's variations

This branch introduces several capabilities in order to account for semantic variations between stores
with respect to
- RDF 1.0 v/s 1.1 term semantics (LiteralLexicalForms v/s LiteralValues)
- term value canonicalization, normalization, and implicit entailment ()
- implicit dataset reification (DereferenceGraphURI)
- operator sematics which permit all types (ClosedModel v/s PartialModel)
- Constraints on undefined variables (UndefinedVariablesAreUnbound v/s UndefinedVariablesAreInvalid)
