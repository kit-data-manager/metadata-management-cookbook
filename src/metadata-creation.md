# Metadata Creation
<details class="faq-box">
  <summary>How can I create a metadata document for my envisioned purpose?</summary>
  
Unstructured metadata documents can be created by writing a free-text file in a 'readme'-style format using a text editor. Alternatively, structured metadata documents can be created by filling in the values of attributes following a defined template. It is recommended to provide structured metadata documents following metadata schemas, as this improves the findability and reusability of data. Various online tools are available to assist in the validation of such structured metadata documents.
</details>

<details class="faq-box">
  <summary>Are there any metadata schemas, which I can use?</summary>
  
There are published metadata schemas which are well-established and widely accepted by the user community, called metadata standards. Adopting existing standards avoids proliferation of descriptions. Different interdisciplinary metadata standards exist, e.g. Dublin Core and DataCite. There are also discipline-specific standards like NeXus, which describes neutron, x-ray, and muon experiment data and is also used in condensed matter physics and materials science.
You can search for metadata standards in dedicated metadata registries, e.g. [DCC Metadata Standards](https://www.dcc.ac.uk/guidance/standards/metadata/list), [FAIRsharing.org](https://fairsharing.org/), the [RDA Metadata Standards Catalog](https://rdamsc.bath.ac.uk/), and others. 
We also provide two metadata registries including metadata schemas for the [NFDI-MatWerk](https://nfdi-matwerk.de/) consortium, which can be found [here](https://matwerk.datamanager.kit.edu/frontend/schema-management.html), as well as for the [NEP](https://nffa.eu/) and [JL-MDMC](https://jl-mdmc-helmholtz.de/) projects, which can be found [here](https://metarepo.nffa.eu/frontend/schema-management.html).
</details>
<details class="faq-box">
  <summary>I didn’t find a metadata schema for my envisioned purpose. What should I do?</summary>
  
You can start by creating a ["readme"-style metadata document](https://data.research.cornell.edu/data-management/sharing/readme/). Once you have a draft, feel free to contact us, we will support you in formalizing it into a proper schema. It can be considered as a good practice through broad adoption. To be recognized as a standard, however, it must be endorsed by a standardization body.
</details>
<details class="faq-box">
  <summary>Where do I find the information required to fill out a metadata document?</summary>
  
This information represents your metadata and can be obtained from various sources: it may be filled by memory, retrieved from physical lab notes, or extracted from existing resources such as data files, Electronic Lab Notebooks (ELNs), etc… 
</details>
<details class="faq-box">
  <summary> I collected the metadata, but it doesn’t follow the selected schema. What should I do?</summary>
  
You can either create the metadata document using a text editor by reviewing the attributes defined in the metadata schema and entering the corresponding values or use a form generated from the schema to enter the metadata. Using a form makes the process easier and reduces the risk of errors.
[eXact lab](https://www.exact-lab.it/) offers an open-source desktop application called [Metadata Editor](https://metadata-editor.gitlab.io/documentation/) that provides a user interface, allowing users  to easily create metadata documents with the help of forms, generated from already stored metadata schemas. These schemas are available in two different instances: [one](https://matwerk.datamanager.kit.edu/frontend/schema-management.html) provided by the [NFDI-MatWerk](https://nfdi-matwerk.de/) community and the [second one](https://metarepo.nffa.eu/frontend/schema-management.html) offered by [NEP](https://nffa.eu/) and [JL-MDMC](https://jl-mdmc-helmholtz.de/) communities.  
</details>
<details class="faq-box">
  <summary>Is there a way to automatically generate a metadata document that complies with a metadata schema?</summary>
  
Yes, you can map automatically the metadata included in the data files to metadata schemas. If further metadata is required, this can be added manually. In order to achieve this, you can either create your own customized mapping extension or use an existing tool that supports your data formats and used instruments.
We offer a mapping service that extracts metadata from various data-files, and maps it to project-specific JSON metadata schemas ensuring better interoperability. Two instances of the tool are available: [one](https://matwerk.datamanager.kit.edu/frontend/mapping-service-ui.html) for  the [NFDI-MatWerk](https://nfdi-matwerk.de/) community and a [second one](https://metarepo.nffa.eu/frontend/mapping-service-ui.html) for the  [NEP](https://nffa.eu/) and [JL-MDMC](https://jl-mdmc-helmholtz.de/) communities.
 A detailed documentation of the service including the supported instruments, input file formats and vendors is available [here](https://matwerk.datamanager.kit.edu/docs/mapping-service/).
</details>