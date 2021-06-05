# emotion_classification_keras
El script Prediction_EMOTION_CLASS.ipynb es el archivos para hacer inferencias personalizadas. La funcion para hacer esto es predictions, la entrada a esta funcion es la oracion
en forma de string, el modelo glove ya cargado y fasttext ya cargado. En caso de usar el colaboratory se debe de descargar todos los archivos de https://drive.google.com/drive/folders/1KrJjdnyIA6DPj8DsV5SNp1Eq2ulEVKGW?usp=sharing
guardarlos en un path conocido y cambiar glove_dataset_dep , fasttext_dataset_dep y el path que abre el pickle en dentro de la funcion convert2embeding hacer el cambio de path 
respectivamente a los modelos y archivos correspondientes (el pickle guarda el tokenizer)
