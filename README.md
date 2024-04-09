Estas dos razas de oveja son muy antiguas y han sido criadas para especializarlas en diferentes producciones: la merina produce muy buena lana y el principal uso de la churra siempre ha sido lechero.

Nuestro problema de negocio viene de un granjero que ha decidido diversificar su producción y quiere tener tanto churras como merinas.
Después de pastorear, las ovejas pasan la noche en graneros separados, como al perro pastor le da igual si la oveja es churra o merina quiere que nos encarguemos nosotros de eso.
Va a instalar una cámara en la entrada de los establos y que nuestro modelo, entrenado a base de fotos de las ovejas, las clasifique.

El entrenamiento ha utilizado un Transfer Learning con una cabeza personalizada, MobileNetV2 y los pesos de imagenet.

En este repositorio público se encuentran los siguientes directorios:
    - data_sample: muestra de los datos, 5 ejemplos de cada raza
    - results notebook, que contiene:
        - data: los directorios que contienen las imagenes para entrenar y evaluar
        - results.ipynb: el notebook resumen del proceso
    - presentacion.pdf: el documento de soporte para la presentación en vivo

------------------------------------------------------------------------------------------------------


These two sheep breeds are very long-standing in Spain. They've been breeded for two different production purposes: merino sheep produce greaty quality wool and the main purpose of churra has always been dairy.

Our bussiness problem comes from a farmer who wants to diversify production and have churras as well as merinas.
After grazing, the sheep spend the night in separate barns. Given the fact that de sheperd dog doesn't mind if sheep are one race or another the farmer needs us to take care of that.
He is going to install a camera at the entrance of the barns and our model, trained from sheep images, is going to sort them.

Model has been fitted using Transfer Learning with a customized head, MobileNetV2 and the imagenet weights.

In this public repository you will find the following directories:
    - data_sample:a sample of the data, 5 examples for breed
    - results_notebook, which contains:
        - data: the directories that contain the images to train and test
        - results.ipynb: summmarized modeling process
    - presentacion.pdf: the document to assist the live presentation
