# General questions
<details class="faq-box">
  <summary>What is metadata? Why is it relevant?</summary>
  
Metadata describes data by providing essential information that helps in its understanding. This can include administrative metadata such as the creator or creation date, etc, or more detailed information beyond the administrative ones e.g. how the data was produced like the used technique, the instrument’s manufacturer,... Metadata can be unstructured, which doesn’t adhere to a specific template, or structured, which follows a defined template. To enhance the findability and reusability of the data, it is important that metadata follows a specification defined by a metadata schema.  
</details>
<details class="faq-box">
  <summary>What is a metadata schema? Why is it important?</summary>
  
A Metadata schema represents a template, which specifies the expected elements and how they are structured, such as attributes’ names, value types, rules, etc. Metadata schemas are actually files, which can be represented in various formats like [JSON](https://www.json.org/), [XML](https://www.w3schools.com/xml/xml_whatis.asp),... Using metadata schemas enables users to describe data with rich and structured metadata, enhancing the findability and reusability of the data.
</details>
<details class="faq-box">
  <summary>What is a metadata document? Why is it important?</summary>
  
A metadata document is a file including a digital description of data. It provides information such as the resource type, author, creation date, used technique, instrument’s manufacturer, etc. Metadata documents can be unstructured, which does not follow a specific template, or structured, which adheres to a defined template. Creating structured metadata documents, following a metadata schema, enhances the findability of the data and supports the reproducibility of results.
</details>
<details class="faq-box">
  <summary>What is the difference between a metadata schema and a metadata document?
</summary>
  
While a metadata schema represents a file defining the structure and rules for metadata such as attributes definitions, a metadata document is a file containing the values for such attributes, describing specific data.
N.B.: A metadata document should be valid against the defined metadata schema, this means it should follow the rules described in the defined schema. 
</details>
<details class="faq-box">
  <summary>What does FAIR mean in research data management?</summary>
  
The [FAIR principles](https://rdcu.be/ewN9f) are a set of guidelines aimed at making data Findable, Accessible, Interoperable, and Reusable. To make data FAIR, it is essential to describe it with rich metadata, assign unique and persistent identifiers to (meta)data, register it in searchable repositories, and ensure it can be retrievable through standardized communication protocols.
FAIRness is not a binary state (yes/no), but it reflects rather how effectively (meta)data fulfill the FAIR principles. This can vary depending on different criterias and the specific needs.
An example of detailed guidance on applying the FAIR principles can be found [here](https://www.go-fair.org/fair-principles/).
</details>