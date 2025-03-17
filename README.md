# EuReD: Ontology

This repository contains RDF descriptions of early modern European peace agreements, which are published by the [University and State Library Darmstadt](https://tueditions.ulb.tu-darmstadt.de/v/pa000008). With more information about the project available on [eured.de](https://eured.de/).

## The Ontology

The EuReD Ontology aims to provide a detailed representation of historical peace agreements. According to the CIDOC Conceptual Reference Model (CRM), the ontology captures key elements of early modern peace agreements, such as the individuals involved, the locations mentioned, and the events described. This enables researchers and historians to delve into and analyze the historical data effectively. A more human-readable description of this model is available [here](https://eured.de/friedensreform/ontologie/).

### Classes of the Ontology

- **Historical Documents (E31 Document)**: Written or recorded artifacts that contain historical or legal information.
- **Identifiers (E42 Identifier)**: Unique codes or references assigned to documents for identification purposes.
- **Events (E5 Event)**: Significant occurrences, such as treaties, wars, or legal agreements, described or recorded in documents.
- **People (E21 Person)**: Individuals who participated in or are mentioned in historical documents.
- **Places (E53 Place)**: Geographical locations mentioned in or relevant to the documents.

### Properties of the Ontology

- **Has Identifier (P1 is identified by)**: Links a document to an identifier, such as a catalog number or a unique reference.
- **Valid In (P6 valid in)**: Indicates the place where a document is considered valid or relevant.
- **Had Participant (P11 had participant)**: Links a document to people who were involved in its creation, negotiation, or signing.
- **Refers To (P67 refers to)**: Indicates places mentioned or relevant in the document.
- **Documents Event (P70i documents)**: Links a document to an event it describes or records.

By structuring the data in this manner, the EuReD Ontology helps to reveal connections and patterns in historical peace agreements, offering valuable insights into the processes and contexts of early modern European diplomacy. This repository is a valuable resource for anyone interested in the study of historical peace treaties and the broader field of historical research.

### Namespaces 
Currently, the ontology uses generic namespaces, such as example.org, as we are still in the process of defining the namespaces.

### Example
An example can be found in `muensterer_vertrag.ttl`. The [introduction](https://tueditions.ulb.tu-darmstadt.de/v/pa000008-0208), written by my colleague, Jan Martin Lies, presents the data inside the file as a human-readable text. 

### Outlook
We will provide such representations for each text that is edited. Furthermore, the data will be made available via the rdfStore that is created at the University and State Library Darmstadt.