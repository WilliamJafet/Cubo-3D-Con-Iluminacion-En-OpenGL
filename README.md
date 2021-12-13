# Cubo 3D Con Iluminacion En OpenGL

La práctica consiste en realizar un programa donde se muestra un cubo 3D al que se le aplica una iluminación.
Para ello primero se explica el código fuente del programa realizado.
En principio se realiza la importación de librerías necesarias para realizar la práctica.

![image](https://user-images.githubusercontent.com/72232712/145738474-ca184d74-71cc-470b-8be7-eaa031505a3f.png)

El siguiente bloque de código es la declaración de variables necesarias para realizar distintas acciones.

![image](https://user-images.githubusercontent.com/72232712/145738482-695384fa-549d-452a-b8d0-f36e556657a8.png)

La función principal es importante debido a que es en esta parte donde empieza a ejecutarse el programa. En este bloque se realizan diversas configuraciones de la ventana para que se muestre al usuario.

![image](https://user-images.githubusercontent.com/72232712/145738492-f80df62b-5a30-4266-a887-15fb4c5b7973.png)

La función init es parte de la librería OpenGL y se utiliza para inicializar los componentes del Canvas, este es un componente en el que se va a realizar el pintado del objeto.

![image](https://user-images.githubusercontent.com/72232712/145738501-c9154243-9576-434b-8431-295a7305d0fb.png)

En la función reshape se realizan las configuraciones necesarias para que se pueda mostrar el objeto.

![image](https://user-images.githubusercontent.com/72232712/145738509-76587ab6-b7e0-4e17-9d0b-9678021291d6.png)

La función display es una de las funciones más importantes porque es aquí donde se programan las instrucciones para que el programa pinte lo que le estamos indicando.
Para esta práctica se pintan los distintos cuadros que forman el cubo, para ello se tiene en cuenta las coordenadas de cada vértice del cuadrado. En total se pintan seis cuadrados para formar el cubo.
Antes de pintar los cuadrados, lo que se tiene que hacer es habilitar las luces para que éstas se puedan notar en el objeto.

![image](https://user-images.githubusercontent.com/72232712/145738525-5a4dc3e0-de35-44af-b521-48d5758210dd.png)

![image](https://user-images.githubusercontent.com/72232712/145738529-31c137a6-f348-4578-95b3-13e1f52be147.png)

La última función por el momento no se realiza ninguna acción.

![image](https://user-images.githubusercontent.com/72232712/145738537-f004834e-d4db-4c75-b87b-8d87953114f3.png)

Ahora que se ha explicado el código fuente, la siguiente parte es mostrar el resultado.
Como resultado hemos obtenido lo que se muestra en la siguiente figura. 

![image](https://user-images.githubusercontent.com/72232712/145738544-5c0889f3-8973-4401-ae88-f410b40d4158.png)
