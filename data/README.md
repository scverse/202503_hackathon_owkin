# How to access data during the hackathon

Most projects will require a certain amount of data, either simple single-cell data or more complex spatial data. Therefore, we have prepared this overview of the data available to you during the hackathon.

## Data

### Single-cell data

For simple single-cell data we advise you to browse, for example, the [`scanpy` tutorials](https://scanpy.readthedocs.io/en/stable/tutorials/index.html) documentation or the [`cellxgene` dataset page](https://cellxgene.cziscience.com/datasets). Both of those sources will provide you with `AnnData` objects, which are the standard data structure for single-cell data in Python. Please check the [`AnnData` documentation](https://anndata.readthedocs.io/en/stable/) for more details on this data structure.

### Spatial data

For spatial data, we advise you to work with our new [`SpatialData` format](https://spatialdata.scverse.org/en/stable/). The format allows you to store arbitrary spatial data, including images, segmentation masks, transcript localization, count tables, their relative transformations to each other and more. More tutorials can be found [here](https://spatialdata.scverse.org/en/stable/) and a recorded talk [here](https://www.youtube.com/watch?v=LjHf451ICPY).

To make distributing spatial data for the hackathon easier, we are using the opportunity to launch the alpha stage of a [new database for spatial omics data](https://lamin.ai/scverse/spatialdata-db/artifacts?filter[and][0][or][0][_branch_code][eq]=1&filter[and][1][or][0][is_latest][eq]=true) we are working on. The database is built togehter with [`lamin.ai`](https://lamin.ai/) and allows you to browse the current selection of about 130 spatial datasets. Eventually we will upload significantly more data, however, for the scope of the hackathon we focussed on a small subet of our data corpus.

We have prepared several notebooks illustrating on how you can actually download data from the database and use it in your project.

- [Intro to SpatialData-DB and Lamin](https://github.com/scverse/202503_hackathon_owkin/blob/main/data/intro.ipynb)
- [Using our pore-defined collections](https://github.com/scverse/202503_hackathon_owkin/blob/main/data/query_collections.ipynb)
- [Query SDDB by public ontologies](https://github.com/scverse/202503_hackathon_owkin/blob/main/data/query_ontologies.ipynb)
- [Query SDDB by custom ontologies](https://github.com/scverse/202503_hackathon_owkin/blob/main/data/query_labels.ipynb)
- [Query SDDB by gene occurrence](https://github.com/scverse/202503_hackathon_owkin/blob/main/data/query_genes.ipynb)

We also provide a [template notebook](https://github.com/scverse/202503_hackathon_owkin/blob/main/data/template_notebook.ipynb) that you can use to get started. Enjoy!