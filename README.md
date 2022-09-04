   # MAESTRÍA DE CIBERSEGURIDAD

![imagen](https://user-images.githubusercontent.com/111188486/188062560-3202f0fe-b03d-416c-b3e0-d49583283d1d.png)

# PROYECTO FINAL TRATAMIENTO DE DATOS
# CLASIFICADOR DE IMÁGENES
                   
# INTEGRANTES:
- ### David Andrés Romero Armas
- ### Juan Pablo Rivera Piñaloza
- ### Jose Ruben Mendoza Muñoz
- ### Cynthya Escuntar Escobar
  
  
     # CLASIFICADOR DE IMÁGENES

El objetivo de esta proyecto es emplear los conocimientos de Tratamiento de Datos en procesos industriales. Para ello vamos a crear un clasificador de tipos de carnes, el cual es un ejemplo simplificado, que utiliza un modelo de procesamiento real con imágenes de mayor resolución y un conjunto de entrenamiento.
Mediante el estudio de ciertas imágenes se llegará a tener un modelo predictivo de alta efectividad en la clasificación de las carnes.

### Pre-requisitos 📋

_Para realizar este proyecto se necesita tener instalado los siguientes programas._

_Anaconda Navigator 2.2.0_

![imagen](https://user-images.githubusercontent.com/111188486/188058787-259d8363-80c0-4d51-b5a2-6616f3bb9e3b.png)

_Jupyter Notebook 6.4.12_

![imagen](https://user-images.githubusercontent.com/111188486/188058593-d4b270bd-0b4e-4f9f-b17f-c03a65e6ccf1.png)

_GitHub Desktop_

![imagen](https://user-images.githubusercontent.com/111188486/188058638-658faa22-c067-4404-a11b-1c62149779c2.png)


Se debe tomar muy en cuenta instalar estos tres programas para su posterior uso en la creación de dicho proyecto, ya que existen una coorelación entre estos.


### Instalación 🔧

_Para realizar la instalación de estos programas se debe tomar en cuenta descargar las últimas versiones para que no existen problemas en la ejecución del proyecto._

_Link instalación Anaconda_

```
https://www.aprendemachinelearning.com/instalar-ambiente-de-desarrollo-python-anaconda-para-aprendizaje-automatico/
```

_Link instalación GitHub Desktop_

```
https://docs.github.com/es/desktop/installing-and-configuring-github-desktop
```

## Ejecutando las pruebas ⚙️

_Importar Librerías._

![imagen](https://user-images.githubusercontent.com/111188486/188059797-6a5cbd27-1299-4038-a65d-5dab2ee384db.png)

_Cargar las imágenes._

![imagen](https://user-images.githubusercontent.com/111188486/188059932-a278be30-6adf-4586-be4f-5f12bd29d61b.png)

_Crear etiquetas y clases_

![imagen](https://user-images.githubusercontent.com/111188486/188060081-0b7a0305-80d0-4a1d-b50d-0c3297e961d3.png)

_Creamos sets de Entrenamiento y Test, Validación y Preprocesar_

![imagen](https://user-images.githubusercontent.com/111188486/188060367-83bffce7-50fb-444b-ac18-381a956c99b0.png)

_Creamos la red_

![imagen](https://user-images.githubusercontent.com/111188486/188060496-5ff4c729-be82-4405-813c-480d28b7b959.png)

_Entrenamos la CNN_

![imagen](https://user-images.githubusercontent.com/111188486/188060650-5277aaf8-31d1-4c2c-bfd5-1cf0d495f366.png)

_Evaluamos la Red_

![imagen](https://user-images.githubusercontent.com/111188486/188060717-5170ed07-38f7-4705-bfa0-5558db10a663.png)

![imagen](https://user-images.githubusercontent.com/111188486/188330363-0fb8b952-aa67-4470-9153-eb5474b9e0a2.png)

![imagen](https://user-images.githubusercontent.com/111188486/188330420-bb75905e-08a9-4659-8b7a-f73408efb277.png)

_Aprendemos de los errores_

![imagen](https://user-images.githubusercontent.com/111188486/188330438-b4b3f49a-b2b6-4ac5-a9f7-1c76be54e3aa.png)

![imagen](https://user-images.githubusercontent.com/111188486/188330460-29eb8748-dc71-4998-ab4a-fff6e5fd7383.png)

![imagen](https://user-images.githubusercontent.com/111188486/188330516-9b4047cf-afa1-4c38-b84d-8060f8a5fdb5.png)


### Análisis de las pruebas end-to-end 🔩

_Importar Librerías._

![imagen](https://user-images.githubusercontent.com/111188486/188060907-fff5789c-c582-483a-a201-57cb11e612f7.png)

_Cargar las imágenes._

![imagen](https://user-images.githubusercontent.com/111188486/188060955-9a2a4950-d22e-40bb-bbf6-a3f990b803b0.png)

_Crear etiquetas y clases_

![imagen](https://user-images.githubusercontent.com/111188486/188061028-e7756f5c-8756-4d9e-a865-f94032323e1f.png)

_Creamos sets de Entrenamiento y Test, Validación y Preprocesar_

![imagen](https://user-images.githubusercontent.com/111188486/188061064-f330b17b-f9ca-4560-ac1a-d1ce89cdaa7c.png)

_Creamos la red_

Se realizara la red neuronal convuncional que es un tipo de red que permite procesar sus capas mediante un aprendizaje supervisado de tal forma que trata de imitar al cortex del ojo, es decir las capas pueden detectar lineas, curvas y la silueta o rostro para que una vez entrenado el algoritmo la red pueda captar las características únicas de cada objeto para finalmente poder reconocer a que grupo pertenece.


1) Creamos la primera capa de neuronas en donde se registran las imágeners
2) Se utilizará la función "LeakyLU()" para activar las neuronas
3) Reduciremos la imagen para mantener las características únicas mediante "MaxPooling()"
4) Se aplana con la función "Flatten()" y se crea una capa con "Dense()"
5) Compilamos la red mediante "compile()" y se le asigna un optimizador Adagrad()

![image](https://user-images.githubusercontent.com/111256602/188297518-5a43f543-ccdf-4205-9b12-9f6421c51d56.png)

_Entrenamos la CNN_

Para entrenar a la red utilizaremos fit() que toma los datos de entremaniento como dos argumentos una entrada para los datos de muestra (X) y los valores de clasificación en el valor (Y).

Se guarda la red ya entrenada mediante la función save() en un formato de archivo h5py, lo que nos ayudará a poder reutilizarla.

![image](https://user-images.githubusercontent.com/111256602/188298704-51fb9b0f-9d9a-4756-9382-5c8684d4edfb.png)

_Evaluamos la Red_

![imagen](https://user-images.githubusercontent.com/111188486/188330543-faa3efc6-4c48-498f-ae03-4c647fc7ac79.png)

_Aprendiendo de los errores_

Etiquetas correctas

![imagen](https://user-images.githubusercontent.com/111188486/188330579-f924bcdf-ccdb-448a-98c5-341913c6ebe8.png)

Etiquetas Incorrectas

![imagen](https://user-images.githubusercontent.com/111188486/188330585-24955da3-c8d4-41f8-a8a7-fe85d0e22e8d.png)

![imagen](https://user-images.githubusercontent.com/111188486/188330624-72feda2e-24e6-433d-89be-031adc56f2a3.png)


     # PUNTOS ADICIONALES
     
Para poder realizar las dimensiones de una imagen, cambio de color, detección de bordes, eliminación de ruido y suavizar contornos se utilizó una imagen del dataset proporcionado.
 
_Cambio de color en la imagen_ 

 1) Cargamos la imagen que vamos a utilizar e importamos las librerias (Matplolib, io, numpy)
 ![image](https://user-images.githubusercontent.com/111256602/188335064-44f883ec-2355-44a6-b4bf-130fed521e0f.png)

2) Realizamos el cambio de color de la imagen utilizando la librería numpy y una vez colocado en el arreglo se coloca la opción en gris y rojo.

![image](https://user-images.githubusercontent.com/111256602/188335164-a3c2262d-db79-478b-b0a0-9a0cec0d54dd.png)

![image](https://user-images.githubusercontent.com/111256602/188335196-01c20894-753c-4f49-a294-215417835dfe.png)


_Detección de bordes_ 

Se detectó la descontinuidad basado en la discontinuidad en el nivel de la intensidad de la imagen y para eso se utilizó la librería io/skimage y matplotlib.

Se aplicó los filtros: sobel, roberts, prewitt y se realizó un for para poder aplicar cada uno de los filtros.

![image](https://user-images.githubusercontent.com/111256602/188335238-7c33335d-8b2d-40df-bdb5-a07343665aa2.png)

_Eliminación de ruido_

Se conoce que existen diferentes tipos de ruido que es producido por perturbaciones agudas y repentinas en las imagener y para poder reducirlo se sacó la media


![image](https://user-images.githubusercontent.com/111256602/188335581-ea44def3-a073-44e7-a1a0-cb7836847b80.png)

_Suavizar y resaltar contornos_

Para poder detectar y suavizar los bordes se utilizó la función Canny() que está compuesta por tres etapas: La primera fue la reducción de ruido para tener una imagen suave y la segunda contiene los gradientes de intensidad de los pixeles.

![image](https://user-images.githubusercontent.com/111256602/188335604-f38a6548-92f3-4b35-a4ff-5e891ff06964.png)


## Conclusiones y resultados 🎁
_En este post hemos visto lo fácil que resulta crear un clasificador de imágenes en tensorflow-keras a través de un ejemplo sencillo. Espero que esto pueda ayudar a “desmitificar” las redes neuronales y las técnicas de visión artificial. Hemos visto tanto cómo construir un modelo propio desde cero, o simplemente usar uno de los disponibles en tf.keras. Por supuesto, si quisiéramos mejorar el rendimiento, o estuviésemos trabajando con un dataset “real” más complejo, hay montones de técnicas más complejas que podemos hacer, pero incluso de esta forma tan sencilla hemos construido un modelo que obtiene resultados aceptables para la mayoría de aplicaciones._

Hay que tener en cuenta que para poder ejecutar el clasificador de imagenes y poder utilizar sus diferentes funciones es necesario importar todas las librerias necesarias para su ejecución. Entre las principales tenemos las siguientes: keras, tensorflow numpy, matplotlib, os.

Crear los sets de entrenamiento, test y validación nos permitirá tener una segregación en las imagenes y poder trabajar con ellas, mediante el uso de la función to_categorical() se convierten las clases para poder realizar la clasificación y generar la salida de la red neuronal.


