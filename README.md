# MaskRCNN
MaskRCNN avec tf 2.3

# Installation 

* conda create -n maskRCNN python=3.8  

* conda install opencv  

* pip install numpy scikit-image tensorflow-gpu keras h5py imgaug 

* conda activate maskRCNN 

* conda install jupyter notebook 

* cd PATH-DE-LA-DEMO 

* git clone https://github.com/pdollar/coco.git  

* cd coco/PythonAPI 

* python setup.py install 

* (si erreur rencontré mettre à jour https://docs.microsoft.com/en-us/answers/questions/136595/error-microsoft-visual-c-140-or-greater-is-require.html) 

* jupyter notebook

# Utilisation

Démo dans samples/Mask-RCNN-Demo.ipynb, permet le téléchargement du modèle pré-entrainé coco.

# Citation

@misc{matterport_maskrcnn_2017,
  title={Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow},
  author={Waleed Abdulla},
  year={2017},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/matterport/Mask_RCNN}},
}

