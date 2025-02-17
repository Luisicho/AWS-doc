# AWS
Amzaon Web Services (AWS) es un conjunto de tecnologias o servicios en la nube, brinda infraestructura para la creacion de nuevas tecnologias para empresas. 
Es Flexible, innovador y cuenta con un respaldo amplio de herramientas seguras en la nube.

## Beneficios por uso de la nube
Algunos beneficios de utilizar AWS son:
* Gastos variables: ya que la forma de cobrar por parte de AWS es Pay-as-yo-go
* Optimizacion de costos: se gasta menos dinero y tiempo aplicando la infraestructura de las aplicaciones
* Capacidad: cuenta con escalabilidad y desescalar horizontalmente segun se necesite.
* Economias de escala: permite pagar menos si uno crea la misma infraestructura en local.
* Velocidad y agilidad: se pueden probar todas las tecnologias para innovar.
* Global: es una infraestructura global, permitiendo dar acceso a las aplicaciones en cualquier parte del mundo. 


## Servicios AWS
Existen 

### EC2
Un EC2 es una instancia de servidores, en otras palabras son servidores virtuales que contienen caracteristicas como memoria ram, espacio de almacenamiento, algun Sistema Operativo, etc. Las aplicaciones que contengan estas EC2 varian dependiendo de sus instalaciones, son flexibles y permiten tener todo tipo de aplicaciones instaladas al igual que una computadora local.

#### ¿Como funciona?
Para iniciar un EC2 el primer paso es *iniciar una instancia*, para esto es importante definir que tipo de instancia lanzaremos, existen varios tipos de instancias para poder lanzar estas llegan a ser Micro, Medium o xlarge, entre otras.
Tambien es fundamental conocer que sistema operativo y que especificaciones de memoria se necesitan para las instancias EC2 de AWS. Luego de todo esto se *conecta con la instancia* para esto AWS genera claves de acceso por terminal, asi un tecnico puede manejar remotamente la instancia EC2.

#### Tipos de instancia EC2
Existen tipos de instancias EC2 a fin de especializarse para un trabajo en especifico, asi como cuando una cafeteria divide roles de trabajo entre un empleado, el encargado de suministros, etc. De la misma manera existe una diferencia entre instancias de EC2. Diferentes tipos de aplicaciones pueden ejecutarse mejor en distintas instancias EC2, unas optimizadas para memoria, otras para computacion o en general con balance de ambas.
En AWS esto se representa en los nombres de las instancias de EC2, por ejemplo.
```
C5.xlarge, C4.micro, R5.micro, T3.micro
         C5               .            xlarge
Familia y generacion      .    Tamaño de procesamiento
C -> Es la familia de computacion optimizada
R -> Es la familia de optimizacion de memoria
T -> Es equilibrada de uso general
```
#### Precios de instancia
EC2 es una tecnologia que genera costos, estos costos se ven reducidos en base a el tipo de precio de instancia estas son:
* Bajo demanda: Genera gastos den la demanda y el tiempo de utilizacion.
* Spot: Son instancias en una subasta, donde la persona que mas pague y necesite esta instancia tendra prioridad por sobre otras, permitiendo que se genere un mercado y subastas de instancias.
* Reservado: Se genera un contrato con AWS de 1 o 3 años donde especifica que se facturará por debajo de un precio acordado, ofreciendo descuento en el uso de una EC2
* Compute savings plans: Es un contrato donde consigues ofertas si te comprometes a generar costos menores a los establecidos.
