# preliminary_ampelography
a repository for preliminary ampelography data

# Images
The image files for leaves can be downloaded from the Dryad repository https://doi.org/10.5061/dryad.3ffbg79m8. After downloading and unzipping the file, the following directory paths should be used to access the leaves: `./doi_10_5061_dryad_3ffbg79m8__v20220523/all_leaves/20190614/` or `./doi_10_5061_dryad_3ffbg79m8__v20220523/all_leaves/20190619/`. It is associated with the following publication:  https://doi.org/10.1002/ajb2.16033.

# Blade outline data
The outline data is located in the zipped folder `OUTLINES`.

# Landmark and metadata
The metadata for the leaves can be downloaded from the file `goali_all_data.csv` in the github repo https://github.com/zoemigicovsky/grape_leaf_temp using the following url: https://raw.githubusercontent.com/zoemigicovsky/grape_leaf_temp/main/data/goali_all_data.csv. It is associated with the following publication: https://doi.org/10.20870/oeno-one.2024.58.2.7735.

Note: see other Jupyter notebook in this repository for analyzing each of the folders above indepdently before combining data together here in this notebook.

# Folder structure
The following folder structure is necessary to run this code. Again, note that this changes slightly if analyzing an individual folder.

* Images: `./doi_10_5061_dryad_3ffbg79m8__v20220523/all_leaves/20190614/` or `./doi_10_5061_dryad_3ffbg79m8__v20220523/all_leaves/20190614/`
* Outlines: `./OUTLINES/`
* Empty folder to store image check plots: `./PLOTS/`
* Empty folder to store leaf check plots: `./LEAVES/`
* Empty folder to store leaf images: `./IMAGES/`
