# PROYECTO FINAL DE SISTEMA FLEXIBLE DE MANUFACTURA 
# PALETIZADO DE CAJAS CON ROBOT ON TRACK Y ACTUADOR TIPO GRIPPER
Este proyecto consiste en el paletizado de cajas que ingresan a la estacion de trabajo mediante una banda transportadora donde son desmontadas por un robot IRB1520ID y colocadas en orden ascendente en un stand para luego ser movidas por los operarios a diversas áreas de la bodega.
### ENTREGABLE DEL PROYECTO
[Final_pack and go.rspag.zip](https://github.com/ivanov16/SFM-Ulatina/files/7019883/Final_pack.and.go.rspag.zip)

### SIMULACIÒN DEL PROYECTO EN YOUTUBE 
https://youtu.be/uT4w8DV9kvQ

### DISEÑO DEL GRIPPER 
![Captura de pantalla 2021-08-20 a la(s) 2 05 06 a  m](https://user-images.githubusercontent.com/66663806/130194024-3b3eb49d-10ac-436c-8ca4-3d82200e09fd.png)
![gripper3](https://user-images.githubusercontent.com/66663806/130194039-dfdcc409-eb91-430e-92a1-181df60f9a77.png)
![gripper2](https://user-images.githubusercontent.com/66663806/130194047-e41a3fe7-4529-4ea3-a0b7-d4c105e775e4.png)

### DISEÑO DEL SMART COMPONENT 
![Captura de pantalla 2021-08-20 a la(s) 2 26 53 a  m](https://user-images.githubusercontent.com/66663806/130196584-a2b13eba-3b5c-40d6-9bdf-1bc9c4df92cc.png)
![Captura de pantalla 2021-08-20 a la(s) 2 11 34 a  m](https://user-images.githubusercontent.com/66663806/130194665-2ca61423-03ff-4602-868e-79cc6b03dbca.png)

### PACK AND GO 
Esta herramienta es la que nos permite guardar y compartir todos los archivos trabajados dentro del software, y asi poder garantizar que todos los archivos del proyecto se mantengan en el orden como si fueran librerias.  

### UN PACK AND WORK 
Es el método que nos permite descomprimir los archivos que vienen empaquetados, y poder trabajarlos desde nuestros ordenadores.

### HERRAMIENTAS FUNDAMNETALES PARA EL PROYECTO
Para el desarrollo del diseño de este sistema se necesita el software robotstudio ABB la versión 6.08.01 instalada en una PC, puede obtenerse por un periodo de tiempo de 30 días en su versión demo, la cual permite realiazar las debidas interacciones. Adicional conocer la información referente al datasheet de cada equipo que será puesto en funcionamiento. 

### ENLACES IMPORTANTES 
Manual del operador utilizado para la instalación del software requerido.
https://library.e.abb.com/public/6aeb483836740e11c1257b4b0052375b/3HAC032104-005_revE_es.pdf

Manual de RAPID utilizado.
https://library.e.abb.com/public/688894b98123f87bc1257cc50044e809/Technical%20reference%20manual_RAPID_3HAC16581-1_revJ_en.pdf

Refencia de youtube para instalaciòn del software.
https://www.youtube.com/watch?v=72noUgD_hk0&ab_channel=TUTORIALESDEROB%C3%93TICA

### PROBANDO EL FUNCIONAMIENTO DE LA ESTACIÒN
![Captura de pantalla 2021-08-20 a la(s) 2 25 54 a  m](https://user-images.githubusercontent.com/66663806/130196447-b6eed2b5-8bc9-4db9-b01d-141565793852.png)

### SEÑALES DE SCVACGRIP
![Captura de pantalla 2021-08-20 a la(s) 2 30 17 a  m](https://user-images.githubusercontent.com/66663806/130196922-5b72a6e5-8e0f-43ec-a9ad-61ffa6e012b7.png)

### SEÑALES DE SCCONVEYOR
![Captura de pantalla 2021-08-20 a la(s) 2 31 54 a  m](https://user-images.githubusercontent.com/66663806/130197107-65c88886-574c-442e-a6fd-e38f704a497c.png)

### LOGIC SYSTEM 
![Captura de pantalla 2021-08-20 a la(s) 2 33 45 a  m](https://user-images.githubusercontent.com/66663806/130197331-ee1bbac8-c1d1-4925-a94e-22dce227fcdc.png)

### CONTROLLER CONFIGURATION 
![Captura de pantalla 2021-08-20 a la(s) 2 36 03 a  m](https://user-images.githubusercontent.com/66663806/130197659-3cca592a-a96f-4214-bdc5-a2255478747d.png)

### CODIGO RAPID DE SOLUCIÒN DE ESTACIÒN 
En estecódigo podremos ver el dezplamiento del robot a lo largo de ejecución, tomando las cajas y colocandolas en su debido orden en el estante. En la imagen se detalla los comentarios del desarrollo de funcionamiento.
![Captura de pantalla 2021-08-20 a la(s) 2 38 47 a  m](https://user-images.githubusercontent.com/66663806/130198288-f614d392-6b6d-4036-980f-0eaf319b4138.png)
![Captura de pantalla 2021-08-20 a la(s) 2 38 56 a  m](https://user-images.githubusercontent.com/66663806/130198302-39474b7b-376e-431c-99e9-4576a0107369.png)
![Captura de pantalla 2021-08-20 a la(s) 2 39 06 a  m](https://user-images.githubusercontent.com/66663806/130198319-d392eef3-ecd3-4486-af02-a812eb52acf5.png)

### ENLACE OFICIAL DEL FABRICANTE DEL SOFTWARE
https://new.abb.com/products/robotics/es/robotstudio/descargas

### RECOMENDACIONES
// Analizar e investigar de manera independiente el uso de señales análogas y digitales //
// El smartgripper debe ser creado y agregado como primer punto dentro del proceso //
// Conocer las propiedades de cada una de las señales a utilizar y su funcionamiento //
// Investigar el uso y programación de RAPID y sus comandos, en youtube hay buenos tutoriales //

### AUTORES DEL PROYECTO
PABLO SALAZAR 
BLADIMIR REINA
JOSE FELIPE 

### AGRADECIMIENTOS 
// agradecimiento al profesor Pablo Gonzalez por haber brindado todos sus conocimientos en el apredizaje y la utilizaciòn del software para la realizaciòn de este proyecto, deseandole èxitos en sus labores. //

### REFERENCIAS
https://robotapps.robotstudio.com/#/landing
https://robotapps.robotstudio.com/#/viewApp/561201ce-ec3a-4140-a312-66d5c8b3f231
