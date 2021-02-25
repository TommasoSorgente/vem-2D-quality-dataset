# vem-quality-dataset

Datasets used for "The role of mesh quality and mesh quality indicators in the Virtual Element Method" by T. Sorgente, S. Biasotti, G. Manzini and M. Spagnuolo.

The files are organized in folders corresponding to the different generation techniques and subfolders relative to the different datasets.
Each dataset is composed of a collection of .off or .obj files numbered increasingly as "Namestep.obj/off", being "Name" the name of the dataset and "step" the refinement step. For example, the first mesh of dataset D_Maze is "Maze0.obj".

In "png_previews" there are visual representations of all the datasets: each image shows a selection of four meshes from that dataset, with decreasing meshsize.

All the datasets (but not the preview images) are archived in the zip file "All_Datasets". For linux and mac user there should be no problem in unzipping the files; for windows any 7zip equivalent works fine.

Here a complete list of the content of each folder:
- Reference: folder containing the reference dataset D_Triangle.
- Hybrid: folder containing the hybrid datasets D_Maze and D_Star.
- Mirroring: folder containing the mirroring datasets D_Jenga, D_Slices and D_Ulike.
- Mirroring_x4: folder containing the multiple mirroring datasets D_Jenga4, D_Slices4 and D_Ulike4.
- png_previews: folder containing the png preview images of the datasets. 


## Citing us
If you use one or more datasets in your academic projects, please consider citing the original paper using the following BibTeX entry:

```bibtex
@article{sorgente2021role,
  title={The role of mesh quality and mesh quality indicators in the Virtual Element Method},
  author={Sorgente, Tommaso and Biasotti, Silvia and Manzini, Gianmarco and Spagnuolo, Michela},
  journal={arXiv preprint arXiv:2102.04138},
  year={2021}
}
```

## Acknowldegment
This paper has been realized in the framework of ERC Project CHANGE (https://cordis.europa.eu/project/id/694515), which has received funding from the European Research Council (ERC) under the European Union’s Horizon 2020 research and innovation programme (grant agreement No 694515).
