# House-Properties-Tagging

This repository show code which I used during House Properties Tagging Hackatron on 14 Mar 2022 to 18 Mar 2022.

In Autogluon.ipynb, I train 5 EfficientNetB3 30 epochs finetune using Autogluon to predict whether input image have Surveillance camera (label 1), Car park (label 2), Car (label 3), Shrine (label 4), Garden (label 5).

Each model is trained to predict each class of label (E.g. first EfficientNetB0 is trained to predict whether input image have Surveillance camera or not).

In Autogluon_Predict.ipynb, I used 5 trained model in Autogluon.ipynb to predict test image and submit result in CSV file.

In hackatron, I got 0.50988 F1 score in private dataset.

# Citation

Kriengkrai Jirawongaram, Suchathit Boonnag, Tip tip. (2022). Super AI Engineer 2021: Properties Tagging. Kaggle. https://kaggle.com/competitions/super-ai-engineer-2021-properties-tagging
