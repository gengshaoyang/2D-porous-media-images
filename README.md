# 2D-porous-media-perm-images
This respository aims to predict the porous media permeability from 2D porous media image using transfer learning based on Swin transformer architecture.
## Data
The data includes three datasets. The first includes 1000 2D porous media images and their corresponding permeabilities. In first dataset, the permeability of porous media ranges from 90.9 to 2651.7 mD, and
porosity ranges from 0.24 to 0.52. The second includes 670 2D noisy porous media images and their corresponding permeabilities, which is generented by Quartet Structure Generation Set (QSGS) method. The third includes 200 rock porous media images from real rock thin sections.
## Citations
If you are interested in our repository or our paper, please cite the following paper:

    @article{GUPTA2024106115,
    title = {Swin transformer based transfer learning model for predicting porous media permeability from 2D images},
    journal = {Computers and Geotechnics},
    volume = {168},
    pages = {106115},
    year = {2024},
    issn = {0266-352X},
    doi = {},
    url = {},
    author = {Shaoyang Geng, Shuo Zhai, Chengyong Li},
    keywords = {Deep learning, Transfer learning, Permeability prediction, Swin transformer, Computer vision, Porous media},
    abstract = {Soil and rock, as typical porous media, widely exist in natural slopes and landslides and underground reservoirs.Accurate predicting the permeability of porous media is crucial in preventing geological
    disasters and extracting underground energy. The conventional methods for obtaining the porous media permeability involve experiments or numerical simulations, both of which are usually time-consuming. In recent
    years, a new approach to predicting the porous media permeability has emerged, utilizing porous media images and leveraging deep learning algorithms. However, previous image-based permeability prediction 
    frameworks have been dominated by convolutional neural networks (CNNs). CNNs require extensive data and intricate network architectures to achieve reasonably accurate predictive performance. State-of-the-art 
    neural networks and methods are employed to overcome the shortcomings of CNNs. To initiate this research, we generated 1200 two-dimensional porous media images. The permeability labels for the target porous media 
    were acquired through computational fluid dynamics. Subsequently, an end-to-end permeability prediction surrogate model was established based on the Swin Transformer architecture. The proposed model falls under 
    the category of transfer learning models, where pretrained weights and bias from other datasets serve as the initial weights and bias for our dataset. Our model has achieved State-of-the-art performance, 
    outperforming CNN by a significant margin on small-size datasets. Even with a small dataset size as 200, the proposed model still achieves an R2 score of 0.9717 on the testing set. Both transfer learning and the 
    Swin Transformer architecture have demonstrated robust predictive capabilities in the context of predicting permeability in small-size dataset porous media based on computer vision.}
    }
