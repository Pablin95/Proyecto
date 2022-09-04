   # MAESTRIA DE CIBERSEGURIDAD

![imagen](https://user-images.githubusercontent.com/111188486/188062560-3202f0fe-b03d-416c-b3e0-d49583283d1d.png)

# PROYECTO FINAL TRATAMIENTO DE DATOS
# CLASIFICADOR DE IMAGENES
                   
# INTEGRANTES:
- ### David Andres Romero Armas
- ### Juan Pablo Rivera Piñaloza
- ### Jose Ruben Mendoza Muñoz
- ### Cynthia Escuntar Escobar
  
  
     # CLASIFICADOR DE IMAGENES

El objetivo de esta proyecto es emplear los conocimientos de Tratamiento de Datos en procesos industriales. Para ello vamos a crear un clasificador de tipos de carnes, el cual es un ejemplo simplificado, que utiliza un modelo de procesamiento real con imágenes de mayor resolución y un conjunto de entrenamiento. Mediante el estudio de ciertas imagenes se llegará a tener un modelo predictivo de alta efectividad en la clasificación de las carnes.

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

_Para realizar la instalación de estos programas se debe tomar en cuenta descargar las ultimas versiones para que no existen problemas en la realización de dicho proyecto._

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

_Resultados obtenidos_

![imagen](https://user-images.githubusercontent.com/111188486/188060717-5170ed07-38f7-4705-bfa0-5558db10a663.png)


### Analice las pruebas end-to-end 🔩

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


_Resultados obtenidos_


## Conclusiones y resultados 🎁
_En este post hemos visto lo fácil que resulta crear un clasificador de imágenes en tensorflow-keras a través de un ejemplo sencillo. Espero que esto pueda ayudar a “desmitificar” las redes neuronales y las técnicas de visión artificial. Hemos visto tanto cómo construir un modelo propio desde cero, o simplemente usar uno de los disponibles en tf.keras. Por supuesto, si quisiéramos mejorar el rendimiento, o estuviésemos trabajando con un dataset “real” más complejo, hay montones de técnicas más complejas que podemos hacer, pero incluso de esta forma tan sencilla hemos construido un modelo que obtiene resultados aceptables para la mayoría de aplicaciones._

  
