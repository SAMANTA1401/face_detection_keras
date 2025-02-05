Detection of face using classification model VGG16, opencv
to train the model image folder structure

* -image data
     *  - train
         *  - class1
               *- image.jpg
                 * .....
         * -class2
                * - image.jpg
     * - test
        * -class1
        * -class2
     * - validation 
        *  -class1
        *  -class2
          
extract image using glob() library then yield image using Imagedatagenerator() then it pass to model fit
