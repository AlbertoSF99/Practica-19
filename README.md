# Práctica 19 - Detector de edad y emociones con Cognitive Service

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 3 - Sesión 8

En esta práctica, se implementó una IA capaz de adivinar el género, la emoción y la edad de una persona en una fotografía por medio de Cognitive Service.

-------------------------------------------------------

#### Requerimientos 
- Cuenta de Azure con suscripción.

-------------------------------------------------------

#### Pasos a seguir

1. Utilizando los mismos recursos creados en la práctica del uso del Machine Learning, y en la página de [https://ml.azure.com/home](https://ml.azure.com/home) nos dirigimos al apartado de ‘Notebooks’ y le damos al símbolo de “+” y le damos en ‘Crear archivo’. En tipo de archivo debe seleccionarse ‘Cuaderno’ y le damos un nombre sin cambiar la extensión del archivo. Le damos en ‘Crear’.

![P19I1](Images\Sesión 7 - P19 01.PNG)

![P19I2](Images\Sesión 7 - P19 02.PNG)

2. Entramos al siguiente link: [https://github.com/josejesusguzman/face-api-consumption-python/blob/main/face-consumption.py](https://github.com/josejesusguzman/face-api-consumption-python/blob/main/face-consumption.py) y le damos al botón de ‘Raw’ para posteriormente copiar todo y pegarlo en la Notebook recién creada.

![P19I3](Images\Sesión 7 - P19 03.PNG)

3. Accedemos a alguna imagen de internet (de preferencia, una selfie) y copiamos el link de dicha imagen y la pegamos en el apartado del Notebook donde diga AQUÍ_PONES_TU_IMAGEN.

![P19I4](Images\Sesión 7 - P19 04.PNG)

4. Accedemos al portal de Azure y buscamos por ‘Face API’ o ‘API de Face’ y le damos en ‘Crear’ y llenamos los datos solicitados para su creación. Le damos a ‘Ir al recurso’ una vez creado y nos dirigimos a ‘Claves y punto de conexión’ y copiamos la clave 1.

![P19I5](Images\Sesión 7 - P19 05.PNG)

![P19I6](Images\Sesión 7 - P19 06.PNG)

5. Pegamos la clave previamente copiada en donde diga ‘subscription_key =’. Copiamos ahora el ‘Extremo’ de la ventana de Azure Portal y la pegamos en ‘face_api_url =’. Una vez habiendo pegado estos datos, le damos en ejecutar al programa y arrojará los valores de edad, sexo y la emoción predominante.