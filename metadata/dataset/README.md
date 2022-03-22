# Subak Data Catalogue Dataset Metadata Specification

In order for Subak to index new datasets in the Data Catalogue we need to collect various 
information about the dataset which we store as metadata. 

## Data Catalogue Metadata Schema
We provide a [YAML schema file](./schema.yml) to help data contributors understand what metadata we collect and the format we expect this to take. For each field in the schema we describe its type, a description of what it is for, whether it is strictly required, a restricted list of options (if applicable) and an example value.

We also provide a template [metadata.yml](./template/metadata.yml) file ready for you to populate based on the rules of the schema and an example pre-filled [metadata.example.yml](./template/metadata.example.yml) file. The [README.md](./template/README.md) and [SOURCES.md](./template/SOURCES.md) files in the template provide a convenient way to populate the `description` and `data_sources` metadata fields which are generally more verbose and better described via [markdown](https://www.markdownguide.org/).

### [Download the metadata template](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/ClimateSubak/community/tree/main/metadata/dataset/template)

If you have any issues when working with our schema, please [start a discussion](https://github.com/ClimateSubak/community/discussions/new?category=q-a) and we'll address any issues you have to get your dataset indexed in the Data Catalogue.

## Publishing your dataset in the Data Catalogue
Currently, you must be a member of an organisation set up in the Data Catalogue in order to create a new dataset. We will be working to improve this process in the coming months. Please [create a user account](https://data.climatesubak.org/user/register) on the Data Catalogue and file a request to [setup your organisation](https://github.com/ClimateSubak/community/issues/new?assignees=&labels=enhancement&template=setup-new-organisation.md&title=%5BNew+Organisation+Set+Up%5D). You can then either use the 'Add dataset' form to populate the dataset metadata from your `metadata.yml` file manually, or submit it to us to upload on your behalf.

We will soon be providing an interface for loading/updating your dataset automatically using your filled in `metadata.yml` file.