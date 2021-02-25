# vem-quality-dataset

Datasets used for "The role of mesh quality and mesh quality indicators in the Virtual Element Method" by T. Sorgente, S. Biasotti, G. Manzini and M. Spagnuolo.

The files are organized in folders corresponding to the different generation techniques and subfolders relative to the different datasets used in [1].
Each dataset is composed of a collection of .off or .obj files numbered increasingly as "Namestep.obj/off", being "Name" the name of the dataset and "step" the refinement step. For example, the first mesh of dataset D_Maze is "Maze0.obj".
In "png_previews" there are visual representations of all the datasets: each image shows a selection of four meshes from that dataset, with decreasing meshsize.

Here a complete list of the content of each folder:
- Reference: folder containing the reference dataset D_Triangle.
- Hybrid: folder containing the hybrid datasets D_Maze and D_Star.
- Mirroring: folder containing the mirroring datasets D_Jenga, D_Slices and D_Ulike.
- Mirroring_x4: folder containing the multiple mirroring datasets D_Jenga4, D_Slices4 and D_Ulike4.
- png_previews: folder containing the png preview images of the datasets. 

REFERENCE: [1] - Sorgente, Tommaso, et al. "The role of mesh quality and mesh quality indicators in the Virtual Element Method." arXiv preprint arXiv:2102.04138 (2021).
