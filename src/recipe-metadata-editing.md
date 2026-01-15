# Edit a JSON metadata document using the Metadata Editor

**Description**: This recipe guides you on how to edit your JSON metadata document using the Metadata Editor application and save it locally.

**Ingredients**: 
- JSON metadata document: this can be an own document created through a specific process or generated using the [previous recipe](recipe-metadata-creation.md).
- Installed Metadata Editor desktop application: a detailed documentation on how to install it is available [here](https://metadata-editor.gitlab.io/documentation/Download/).

**Steps**: 
1. Open the Metadata Editor application and select the MetaStore “nfdi matwerk” instance.
2. Select the “MetaStore schemas” button to get schemas.
3. Load the suitable metadata schema by selecting the “raw data” label and “scanning-electron-microscopy” schema identifier.
4. Load the JSON metadata document and verify that all properties are accurate. Some required properties are missing, which should be manually filled.  
	“Technique”: “SEM”;  
	“Measurement purpose”: “completeness check”;  
	“Parents”: Add one parent with “parentType”: “not applicable”.  
5. Confirm your metadata by selecting the “DONE” button.
6. Save your metadata document locally as a JSON file by selecting the "Export" button.  

**Servings**: An edited JSON metadata document, which is locally saved.

If you prefer learning by watching, we’ve also made this recipe available as a [youtube video](https://www.youtube.com/watch?v=w4VlrsNK24I&t=2s)!
