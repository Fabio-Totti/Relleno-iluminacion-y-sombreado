# Relleno, iluminacion y sombreado

# Este repositorio corresponde a las actividades complementarias con respecto a la unidad 4 en la asignatura de graficación.

Los programas consisten en el relleno, iluminacion y sombreado de la superficie de una figura 3D, en este caso un cubo, esto mediante el uso de librerias correspondientes a la herramienta GLUT de Opengl en el lenguaje de programacion Java con ayuda del entorno de desarrollo integrado libre "NetBeans". 
Estos programas se dividen de la siguiente manera:

-Rellenado de color para cada lado del cubo, en esta clase se generada un cubo mediante la creacion de poligonos y proporcionarles de un color diferente para cada lado del cubo.

-Degradado de color para cada lado del cubo, mediante esta clase cada lado presente en el cubo dispondra de un degradado unico interpolando de un color a otro.

-Presentar una fuente de iluminacion en el espacio en el que se encuentra el cubo, con ello observar la sombra y el reflejo que produce en su superficie.

Todos estos programas consisten en la creacion de un objeto 3D para su manipulacion mediante la adquisicion de un color y aplicacion de una fuente de iluminacion en su superficie.

# Codigo fuente usando lenguaje de programacion java mediante el IDE de Netbeans Apache y OpenGL para la creación de los graficos.

# Programa 1: Relleno.

Se importan las librerias la generacion de graficos con OpenGL y la ventana.

![1](https://user-images.githubusercontent.com/72088585/144141181-d8b18cd1-9e00-48d4-83a8-24ac3781bd76.png)

Metodo Main para la creacion de la ventana y ejecucion del programa.

![2](https://user-images.githubusercontent.com/72088585/144142110-e0cecbe7-de71-4002-afc2-dc010006a4fc.png)

Metodo Init que creara el entorno.

![3](https://user-images.githubusercontent.com/72088585/144142348-a75556ad-5079-422d-abf4-c92420a0cfaf.png)

Metodo reshape que creara la proyeccion del entorno y las formas.

![4](https://user-images.githubusercontent.com/72088585/144142590-4bab2a09-ac05-4653-bf24-9c03a12f3404.png)

Metodo display, este metodo se encarga de crear el cubo lado por lado y con ello aplicar un color diferente para cada uno.

![5](https://user-images.githubusercontent.com/72088585/144143142-e67e064b-70a5-440f-8a78-e1c6fbbd6f0f.png)
![6](https://user-images.githubusercontent.com/72088585/144143296-e8f0b196-09cc-472d-a547-e18bbff117bb.png)
![7](https://user-images.githubusercontent.com/72088585/144143393-ccdd260f-57d6-4228-97ff-884f4e09680c.png)

Metodo displayChanged.

![8](https://user-images.githubusercontent.com/72088585/144143701-2039f0b1-7531-41fe-abb0-cbdc56dc8614.png)

# Ejecucion y resultados.

Al ejecutar esta sintaxis obtenemos la primera perspectiva de un cubo cuyos lados pintan de un color distinto.

![9](https://user-images.githubusercontent.com/72088585/144143935-2f1552f7-d1ca-479f-a704-0c0a880578a8.png)

# Programa 2: Degradado.

Se importan las librerias la generacion de graficos con OpenGL y la ventana.

![1](https://user-images.githubusercontent.com/72088585/144144603-1b0cd6e4-c78e-40dd-901a-93aaf22620cd.png)

Metodo Main para la creacion de la ventana y ejecucion del programa.

![2](https://user-images.githubusercontent.com/72088585/144144738-892acfdc-7364-4644-9d3b-ec915d7f7c08.png)

Metodo Init que creara el entorno.

![3](https://user-images.githubusercontent.com/72088585/144144976-de6e0e7e-28b0-4a68-ba6d-762d538adbcb.png)

Metodo reshape que creara la proyeccion del entorno y las formas.

![4](https://user-images.githubusercontent.com/72088585/144145056-01a1307e-f8ec-4a71-a30b-146a95497b4f.png)

Metodo display, este metodo se encarga de crear el cubo lado por lado y un respectivo degradado para cada uno.

![5](https://user-images.githubusercontent.com/72088585/144145236-628ba169-95c4-4031-8df8-c6a0a7b0f5ef.png)
![6](https://user-images.githubusercontent.com/72088585/144145338-32540318-5767-4762-9545-54f16fb69860.png)
![7](https://user-images.githubusercontent.com/72088585/144145423-02760dd3-9305-45e9-b2bb-a711a154a696.png)

Metodo displayChanged.

![8](https://user-images.githubusercontent.com/72088585/144145638-ee321a05-3d46-432e-b740-4f8bfd9a3bb8.png)

# Ejecucion y resultados.

Al ejecutar esta sintaxis obtenemos la primera perspectiva de un cubo cuyos lados se componen de un color degradado, interpolando de un lado a otro.

![9](https://user-images.githubusercontent.com/72088585/144146049-a0c6bd0c-b0de-488f-b925-67d3bc02146e.png)

# Programa 3: Iluminacion y sombreado.

Se importan las librerias la generacion de graficos con OpenGL y la ventana.

![1](https://user-images.githubusercontent.com/72088585/144141181-d8b18cd1-9e00-48d4-83a8-24ac3781bd76.png)

Se crean las matrices correspondientes a los parametros de iluminacion.

![1](https://user-images.githubusercontent.com/72088585/144146853-7f2297b9-cd0d-40d5-a4b9-c59d68d9c1e6.png)

Metodo constructor con propiedades de la ventana.

![2](https://user-images.githubusercontent.com/72088585/144147015-c00a01b0-6207-4572-8398-cbbaebb59d27.png)

Metodo Main para ejecucion del programa.

![3](https://user-images.githubusercontent.com/72088585/144147107-de3173a0-6f2e-4f07-97cc-6de9e439edc0.png)

Clase interna encargada de los graficos, el metodo init tiene la funcion de crear el entorno y las distintas fuentes de iluminacion.

![4](https://user-images.githubusercontent.com/72088585/144149650-99547b69-5ff7-459d-8585-ed57e3db642a.png)

Metodo reshape que creara la proyeccion del entorno y las formas.

![5](https://user-images.githubusercontent.com/72088585/144149841-ba04a4bb-d1e1-49e8-84e6-eea1d4575307.png)

Metodo display, este metodo se encarga de crear el cubo lado por lado, las funciones de la camara y los parametros de iluminacion del objeto.

![6](https://user-images.githubusercontent.com/72088585/144150264-30bbf3ea-1057-4c47-bbb4-e200aedb4923.png)

Se crea el cubo lado a lado.

![7](https://user-images.githubusercontent.com/72088585/144150461-cfbea632-fd21-4d4f-8edc-c9e71243fe1c.png) ![8](https://user-images.githubusercontent.com/72088585/144150469-4541c5e9-cf7d-49ab-8136-9a71906420a3.png)

Metodo DisplayChanged.

![9](https://user-images.githubusercontent.com/72088585/144150687-ea851aaa-6a9c-42d8-9a7a-7599c8f5c998.png)

# Ejecucion y resultados.

Al ejecutar esta sintaxis obtenemos la primera perspectiva de un cubo que presenta una sombra debido a una fuente de luz cercana en ambiente semi iluminado.

![11](https://user-images.githubusercontent.com/72088585/144151433-f7e63853-01e4-4b38-a0e3-eeeb1d4e3572.png)



