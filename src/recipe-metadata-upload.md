# Upload a JSON metadata document to a Metadata Repository (MetaStore)

**Description**: This recipe guides you on how to upload your JSON metadata document to a Metadata Repository (MetaStore) using the Demo Frontend - a graphical user interface.

**Ingredients**: 
- A JSON metadata document. If you need help creating a metadata document, please refer to the previous recipes.
- An SEM TIFF Image is available under this [link](https://matwerk.datamanager.kit.edu/api/v1/dataresources/c729a6d9-d2d2-4f4b-8bb4-ea7444620b1f/data/SCeO5_17.tif). If you already have a URL for your SEM image, you can use that instead.
- Web browser

**Steps**: 
1. Access the [Demo Frontend](https://demo.datamanager.kit.edu). Please note that all demonstrators are automatically reset every day at midnight, and all uploaded data is deleted.
2. Log in using the key icon in the upper-right corner. You can sign in using GitHub, ORCID, or Helmholtz AAI. You can also use the shared credentials (demo, demo), but any data uploaded this way will be visible to everyone.
2. Select the “Research Metadata Repository” button and access the list of all metadata schema.
3. To add a new metadata document, select the "create" button of the “Scanning Electron Microscopy Schema v0.1.0” schema.
4. Fill out the administrative metadata on the left-hand side.  
	“Title Value”: “SEM image”;  
	"Related Resource URL value": [Link to your SEM image](https://matwerk.datamanager.kit.edu/api/v1/dataresources/c729a6d9-d2d2-4f4b-8bb4-ea7444620b1f/data/SCeO5_17.tif).
5. Click the transfer button to upload the administrative metadata on the right-hand side. A record.json file will then appear on the left-hand side.
6. Upload your metadata document using the “add more" button in the upper-right corner.
7. Click the “Upload 2 files” button to begin the upload.
A form containing the administrative metadata will appear. You can use it to edit the existing metadata values if needed. For this recipe, simply click Cancel.

**Servings**: An uploaded JSON metadata document that is privately accessible.

