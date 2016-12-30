# Contenedores (Virtualización ligera usando contenedores)

## Ejercicios

* [x] 1. Instala LXC en tu versión de Linux favorita. Normalmente la versión en desarrollo, disponible tanto en GitHub como en el sitio web está bastante más avanzada; para evitar problemas sobre todo con las herramientas que vamos a ver más adelante, conviene que te instales la última versión y si es posible una igual o mayor a la 2.0.

![1](EJ1/1.png)
![2](EJ1/2.png)
![3](EJ1/3.png)
![4](EJ1/4.png)

* [x] 2. Instalar una distro tal como Alpine y conectarse a ella usando el nombre de usuario y clave que indicará en su creación.

![1](EJ2/1.png)
![2](EJ2/2.png)
![3](EJ2/3.png)

* [X] 3. Provisionar un contenedor LXC usando Ansible o alguna otra herramienta de configuración que ya se haya usado.

Utilicé Vagrant y Ansible, clic [aquí](EJ3/) para ver los ficheros implicados.

![1](EJ3/1.png)
![2](EJ3/2.png)
![3](EJ3/3.png)

* [x] 4. Instalar una imagen alternativa de Ubuntu y alguna adicional, por ejemplo de CentOS.

![1](EJ4/1.png)
![2](EJ4/2.png)
![3](EJ4/3.png)
![4](EJ4/4.png)

* [x] 5. Crear a partir del contenedor anterior una imagen persistente con commit.

![1](EJ5/1.png)
![2](EJ5/2.png)

### Hito 4

* [x] 6. Reproducir los contenedores creados anteriormente usando un Dockerfile.

Se puede ver el Dockerfile [aquí](https://github.com/mmaguero/MII-CC16-17/blob/master/Dockerfile).

![1](EJ6/1.png)
![2](EJ6/2.png)
![3](EJ6/3.png)
![4](EJ6/4.png)
![5](EJ6/5.png)
![6](EJ6/6.png)

Como en el Dockerfile instalamos un servidor de apache, lo levantamos, el resultado es este...

![7](EJ6/7.png)
![8](EJ6/8.png)

* [x] 7. Crear con docker-machine un entorno local y ejecutar en él contenedores creados con antelación.

 En este caso opté por hacerlo en la cloud con [docker-machine](https://docs.docker.com/machine/examples/aws/), para luego instanciar con una imagen creada para Docker Hub en el [hito 4](https://github.com/mmaguero/MII-CC16-17/tree/master/contenedor)

![1](EJ7/1.png)
![2](EJ7/2.png)
![3](EJ7/3.png)
![4](EJ7/4.png)
![5](EJ7/5.png)

