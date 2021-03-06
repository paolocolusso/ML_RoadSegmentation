# ML_RoadSegmentation

README for the Machine Learning CS-433: Project 2 - Road Segmentation

Group names: 
- Diego Fiori
- Paolo Colusso 
- Valerio Volpe

CrowdAI team name: LaVolpeilFioreEilColosso

### Architecture

A data folder with the following structure must be created:

```
data/training/
    /test_set_images/
```

The files created and the functions developed are presented in the following sections:

* [Helpers](#helpers)
* [Preprocessing](#prepr)
* [Logistic Regression](#logistic)
* [Ridge Regression](#ridge)
* [Neural Nets](#cnn)
* [Post Processing](#pp)

### <a name="helpers"></a>Helpers
Contains the function used to perform generic operations:
```
load_image
img_float_to_uint8
concatenate_images
value_to_class
img_crop
from_mask_to_vector
transform_subIMG_to_Tensor
reduce_dataset
label_to_img
make_img_overlay
compute_F1
calcul_F1
create_submission
```
### <a name="prepr"></a>Preprocessing
```
rotation_local
flip
add_features
extract_features
poly_features
add_border
```
### <a name="logistic"></a>Logistic Regression
### <a name="ridge"></a>Ridge Regression
### <a name="cnn"></a>Neural Nets
### <a name="pp"></a>Postprocessing
``` Post_processing.py```


## References

+ Statistical learning: James, Witten, Hastie, Tibshirani, *Introduction to Statistical Learning*, see [details](https://www-bcf.usc.edu/~gareth/ISL/).

+ Image processing: Burger, Burge, *Digital Image Processing. An Algorithmic Introduction Using Java*, see [details](https://www.springer.com/de/book/9781447166832).

+ Neural nets: EPFL course available [here](https://fleuret.org/ee559-2018/dlc/).
