# MarutaSeg: Log Instance Segmentation Dataset for Autonomous Forest Machinery

Welcome to the **MarutaSeg**, a collection of annotated images designed for instance segmentation of logs in forestry applications. This dataset supports research and development in forestry automation.

[[`BibTeX`](#CitingThisPaper)] [[`Paper`](https://doi.org/10.1080/14942119.2024.2336856)]

<div align="center">
  <img src="https://github.com/norlab-ulaval/logpiles_segmentation/blob/main/images/graphical_abstract.png" width="100%" height="100%"/>
</div><br/>


## Dataset Structure

- `images/`: Contains images of logs.
- `annotations/`: JSON files with segmentation annotations in COCO format.

This dataset includes 2000 images in total.
The annotation class is "sugi (*cryptomeria japonica*)" only; tree species were not classified.
Note that we used 7466 log annotations for a total of 3262 images in the paper. However, the data were selected due to the rights of the field.


## License

The LogSeg dataset is released under the **CC BY 4.0** license.  

## How to Download the Dataset

Download the whole data from [here](https://github.com/kusui92/marutaseg.git).


## Citation

If you use the MarutaSeg dataset in your research, please cite it as follows:

```bash

@article{doi:10.1080/14942119.2024.2336856,
    author = {Kengo Usui},
    title = {Estimation of log-gripping position using instance segmentation for autonomous log loading},
    journal = {International Journal of Forest Engineering},
    volume = {35},
    number = {2},
    pages = {251--269},
    year = {2024},
    publisher = {Taylor \& Francis},
    doi = {10.1080/14942119.2024.2336856},
    url = {https://doi.org/10.1080/14942119.2024.2336856},
}
```
