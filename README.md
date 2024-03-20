# Summary

Essentially using TensorFlow/Keras API to classify 5 different food & drink into their correct classes. 

But this can easily be swapped for other image classess or expanded to include much more new image classess. 

# Possible Future Work (Musings)

Sort countless photo gallery pictures into niche/class(es) offline.

Currently the most popular image recognition software such as Google Photos only allows sorting of images into broad categories (e.g. people, pets, buildings etc) in the cloud and hence you need to be online for it to work. 

An app that can classify images offline will surely be useful and especially if it can sort custom image claasses that are very domain specific or uncommon (e.g. Telegram chats screenshots, school/work PowerPoint Slides screenshots, etc) on an end user's device. 

However, sufficient images in the photo gallery of a particular class needs to be present to undergo training for some time and requires significant computational power from somewhere (local/cloud).  

*Refactoring my code for increased understanding for beginers or adding more comments may be done someday...

# Results
The confusion matrices shows the number of correctly predicted image classes for a particular training iteration only. 

Results may not always be exactly reproducible.  

![CNN_Percentage](https://github.com/MSHI005/Multiclass-Image-Classification/assets/159223357/fbc9ef15-e292-4b81-90da-f8ae05b5c384)

![VGG16_Percentage](https://github.com/MSHI005/Multiclass-Image-Classification/assets/159223357/d706508e-8c2d-4cc3-8c69-06d6001d8679)

# NOTICE
The Juypter Notebook was executed and adapted to the Google Colab runtime environment before uploading.

The original image_dataset.zip was not backed up and cannot be recovered, but any small image dataset zipped file with the specified file directory structure can work as well.   

Much more information can be found inside the notebook so that this README.md file can be kept concise.
