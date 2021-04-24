# CuriosityVO - Curiosity Mars Rover Monocular Visual Odometry Dataset

This dataset is a curated collection of images from the NASA Curiosity Rover's web gallery (https://mars.nasa.gov/msl/multimedia/raw-images/) and the NASA PDS (https://pdsimage2.wr.usgs.gov/archive/MSL/). The official sources contained many images from different cameras that were not all suitable for visual odometry (blurry images, images of the sky or robot arms). I filtered the images to only keep the navcam images that capture robot movement.

Code for the data collection and filtering is available as a Deepnote notebook. (https://deepnote.com/@pavol-drotar-bed2/CuriosityVO-Dataset-Collection-yFruU8QyTH6Awcx9HmNXfA)

If you use the dataset, you should cite the official NASA Planetary Data System (https://pds.nasa.gov/ds-view/pds/viewDataset.jsp?dsid=MSL-M-NAVCAM-2-EDR-V1.0):
Maki, Justin, MSL Mars Navigation Camera EDR V1.0, NASA Planetary Data System, MSL-M-NAVCAM-2-EDR-V1.0, 2013.

Directory structure:
```
- README.md
- curiosityvo/
  - sol/
    - index - contains the urls of the .jpg images from the sol
    - image_name.jpg - images
    - image_label_name.LBL - image labels downloaded from the PDS
```

Dataset preview (from sol 555)

![](https://github.com/padr31/curiosityvo/blob/main/curiosityvo/555/NLB_446763623EDR_D0280304TRAV00187M_.jpg)  ![](https://github.com/padr31/curiosityvo/blob/main/curiosityvo/555/NLB_446763672EDR_D0280310TRAV00187M_.jpg) ![](https://github.com/padr31/curiosityvo/blob/main/curiosityvo/555/NLB_446763741EDR_D0280316TRAV00187M_.jpg)
