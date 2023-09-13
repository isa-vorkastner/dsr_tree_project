# Tree Vision

Tree Vision is a data science bootcamp final project aimed at detecting urban trees in aerial images.

## Data Downloading

### Public Trees Dataframe
To get started with this project, you'll need to download the dataframe containing information about public trees in Berlin. You can find this dataset [here](https://hub.arcgis.com/datasets/esri-de-content::baumkataster-berlin/explore). This dataframe consists of approximately 800,000 public trees in Berlin.

### Aerial Images
To acquire aerial images of Berlin, please refer to the provided Jupyter Notebook located at `notebooks/Download_aerial_images.ipynb`. Please note that accessing these images requires a Google Earth Engine account.

## Model

We've developed a Detectron2 model that's trained on aerial images of Wilmersdorf, using data from the Baumkataster Berlin. To evaluate the model's performance, we used aerial images of Prenzlauer Berg with manually labeled trees.

To replicate and explore the model's training and evaluation process, you can refer to the Jupyter notebook at `notebooks/Detectron2_RGB.ipynb`.
