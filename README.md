# Knowledge Representation and Semantic Web Assignment 2

This repository contains files and documentation for Assignment 2 in Knowledge Representation (KR). The focus is on creating a basic structure using the OWL (Web Ontology Language) to represent relationships and hierarchies typically found in a university setting.
## Contents

  `university.rdf`: The primary OWL file defining the ontology structure for a university.
  Class Hierarchies: Includes definitions for University, Department, Course, Professor, and Student.
  Relationships: Captures relationships such as:
      attends: Students → Courses
      studentsOf: Course → Students
      teaches: Faculty → Course
  Individuals: Aswathy_Gopalakrishnan, He_Tan, Malmo_University, Sneha_Manmathukalam, Johannes_Oestsch, KTH

## Features

  Ontology Design: Uses OWL to model university entities, their properties, and relationships.
  Workflow Description: Includes the logical reasoning workflow to validate relationships and hierarchy.
  Reasoning: Demonstrates how reasoners like HermiT or Pellet can infer implied relationships.

## How to Use

  Open university.owl in Protégé or any OWL editor.
  Run a reasoner to verify and explore inferred relationships.
  Use the ontology to expand or analyze university structures.

## Dependencies

  Protégé or any OWL-compatible editor.
  Reasoning engine (HermiT 1.4.3.456).

## Future Scope

  Extending the ontology with advanced roles (e.g., Research Groups).
    Incorporating real-world datasets to validate the ontology.
