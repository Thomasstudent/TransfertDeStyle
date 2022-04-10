# TransfertDeStyle
:pencil2: Dans ce projet, on étudie deux architectures de réseaux de neurones pour le Transfert de Style. :pencil2:

# Les données : 
:blue_book: Les jeux de données que l'on utilise du projet peuvent être téléchargés à cette adresse : https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/. On considère les jeux de données suivants : monet2photo, vangogh2photo ainsi que ukiyoe2photo.  
:blue_book: On manipule également deux images disponibles sur ce GitHub : https://github.com/leongatys/PytorchNeuralStyleTransfer/tree/master/Images.

# Le code :
:computer: Le notebook Colab réalisé est trop volumineux, pour le consulter rendez-vous [ici](https://colab.research.google.com/drive/1NosBqygUw3pTQNFLX_qTpUg1Lb1erdnJ?usp=sharing).

## Expérimentations :
:open_file_folder: Les fichiers *Classique*, *No_Cycle*, *No_Identity*, *Small_Buffer_Size*, "Ukiyoe" et "Vangogh* contiennent les données de l'entraînement de plusieurs réseaux CycleGAN selon l'expérimentation. Dans ces dossiers, on trouve les images générées pendant l'apprentissage à partir des ensembles d'entraînement et de validation, les valeurs de la fonction de coût à chaque epoch et les poids des réseaux.
