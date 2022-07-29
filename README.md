# Custom visión: Predicción de galaxias 
**Objetivo:** Crear un proyecto que pueda distinguir diferentes imágenes entre sí.   

![](/imagenes/vision_.jpg)

**Requisitos**
- Cuenta de Azure con una suscripción activa
- Equipo de cómputo con sistema operativo: Windows, Linux o MacOs.

**Pasos**  
Ingresamos a la página de https://www.customvision.ai/e iniciamos sesión.  
Damos clic en crear un nuevo proyecto, ahí llenamos los siguiente:  
![Imagen 1](/imagenes/Imagen0.png)

Nombre: Colocamos el que queramos.  
Descripción: Colocamos la descripción del proyecto.  
Recurso: Seleccionamos crear nuevo recurso, ahí vamos a escoger las siguientes opciones:
- En tipo: Seleccionamos Cognitive services.
- Nivel de precio: Seleccionamos el gratis.
- Todo lo demás lo llenamos como queramos.
- Damos clic en crear recurso.

Seleccionaremos el recurso que acabamos de crear, llenamos la ventana siguiente de la siguiente forma:  
Tipo de proyecto: Seleccionamos clasificación.  
Tipo de clasificación: Seleccionamos multimedia.  
Dominios: Seleccionamos General [A2].  
Damos clic en crear proyecto.  
![](/imagenes/Imagen1.png)

A continuación, en agregar imágenes vamos a subir imágenes, en este caso serian del espacio, primero subiremos de galaxias y le podremos en Tag galaxia.  
Luego subiríamos de nebulosas y en tag le ponemos nebulosa, luego subiríamos de planetas y en tag le pondríamos planeta.  
![](/imagenes/Imagen2.png)

Después subiríamos imágenes de cosas que no queremos que se detecten, en este caso serian estrellas, así que las subiríamos, solo que en tag seleccionaríamos negativo.  
![](/imagenes/Imagen3.png)

Damos clic en el botón de Train, seleccionamos Quick Training y le damos en Train, esperamos a que termine de realizar el proceso.  
![](/imagenes/Imagen4.png)

Le damos en Quick Test, colocamos la url de una imagen que queramos que pruebe y miramos los resultados.  
![](/imagenes/Imagen5.png)

En este caso como pusimos una imagen de estrellas,  nos da una probabilidad más grande que sea una tag negativa.