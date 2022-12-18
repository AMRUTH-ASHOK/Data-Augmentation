
==================================  DATA AUGMENTATION  ===================================

1. completeFlow() - Augments images in a folder and stores them in another folder
    - arguments:
        -
        src_path_original - path of the folder which contains images belonging to their respective classes.
        src_dest_original - path of the folder where images will be stored after augmentation. (classes has to be created prior to running this function)
        multiplication_factor - Augmentation rate. (Number of images to be generated per image)
    - return : None

2. aug_flow() - helper function for completeFlow()
    - arguments:
        -
        img - image to be augmented
        multiplication_factor - Augmentation rate. (Number of images to be generated per image)
    - return : List of augmented images

============================================================================================            
