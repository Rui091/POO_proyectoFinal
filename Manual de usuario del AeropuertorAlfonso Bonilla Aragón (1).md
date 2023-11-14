# Manual de Usuario del Aeropuerto Alfonso Bonilla Aragón 
Desarrolladores 

Rui Yu Lei Wu       
Marco Antonio Riascos Salguero

## Introducción

Bienvenido al Manual de usuario del sistema del Aeropuerto Alfonso Bonilla Aragon; Este programa le permitirá conocer las principales operaciones y acciones de un aeropuerto; acciones que pueden ser realizadas por  el controlador aéreo del aeropuerto, una aerolínea y el usuario al que se le va a prestar el servicio; de manera clara, sencilla y eficiente. 

## Contenido

1. Inicio Rápido
      1.1. Requisitos del Sistema
      1.2. Ejecución
2. Acceso del Empleado
    2.1 Aerolinea
        2.1.1 Crear Aerolínea
        2.1.2. Crear vuelo
        2.1.3 Crear Areonave
        2.1.4 Ver aviones
        2.1.5 Ver vuelos
        2.1.6 Asignar vuelos
        2.1.7 Eliminar vuelo
        2.1.8 Eliminar Aerolínea
    2.2 Torre de Control
        2.2.1 Crear puerta de embarque
        2.2.2 Asignar puerta 
        2.2.3 Eliminar puerta
        2.2.4 Permiso de vuelo
        2.2.5 Notificar ubicación
        2.2.6 Ver puertas
        2.2.4 Ver Ubicaiones 
3. Acceso de pasajero
    3.1 Inicio
        3.1.1 Servico de cafeteria
        3.1.2 Servicio de tiendas 
        3.1.3 Servicio de parqueadero
    3.2 Informacion del pasajero
    3.3 Ver vuelos 
    3.4 Reservar vuelos
    3.5 Información sobre los países de destino
    3.6 Ver mis vuelos


4. Solución de Problemas Comunes
        4.1. No se puede abrir el programa
        4.2. Error en los cálculos

5. Diagrama UML

6. Contacto y Soporte Técnico


### 1. Inicio Rápido
**1.1. Requisitos del Sistema**

- Sistema Operativo: Windows 10 o superior
- Procesador: 1 GHz o superior
- Memoria RAM: 512 MB
- Espacio en Disco: 10 MB

### 2. Acceso al empleado

##### 2.1. Aerolínea

**Crear Aerolínea**

EL programa permitirá al usuario ingresar con el menú, si es un pasajero o un empleado, al seleccionar empleado, en la barra del menú izquierdo, el menú secundario le preguntara que tipo de cargo tiene, si es una aerolínea o un empleado que maneja la torre de control, a lo que debe acceder usando la opción de aerolínea 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/creacion%20aerolinea1.png?token=GHSAT0AAAAAACJXRZTT2HLL6XMJ35PJA76QZKTERYQ)


Al ingresar como empleado la primera opción del menú secundario que se desplegara es si quiere registrar una aerolínea, al dar clic en esa opción se desplegara un menú que le permitirá registrar la aerolínea digitando el nombre 

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/creacion%20aeroinea2.png?token=GHSAT0AAAAAACJXRZTS7KPFJUXR2HXJSJHWZKTETBA)

Al dar en el botón de crear, será exitosa la creación de la aerolínea y le permitirá acceder a todas las funciones de aerolínea 

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/creacion%20aerolinea%20exitoso.png?token=GHSAT0AAAAAACJXRZTTL5LVGJ3BJW4JJJM2ZKTET6Q)

Si por el contrario se ingresa el nombre de una aerolínea que ya existe, el programa no le permitirá continuar y le saldrá un mensaje con la alerta de que esa aerolínea ya existe 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/aerolinea%20existente.png?token=GHSAT0AAAAAACJXRZTTKQ3UCQ2G3MWCP57SZKTEVFA)


**Crear vuelo**
Al ser exitoso la creación de la aerolínea, el programa le permitirá al usuario dueño de la aerolínea, crear vuelos accediendo a través de la segunda opción del menú y selecciona su aerolínea de la lista de aerolíneas existentes
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/creacion%20de%20vuelo1.png?token=GHSAT0AAAAAACJXRZTS6F6FDM4NUR42IGSEZKTEWFA)

Seguido de eso le permitirá al empleado de la aerolínea llenar el formula de inscripción de una aeronave; a través de diferente tipo de selectores, tanto como input de texto, como selectores de fechas, para el correcto registro del vuelo
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/formulario%20vuelo%20selector%20de%20dia.png?token=GHSAT0AAAAAACJXRZTSTQGJDS74QV56ZPXGZKTEXFA)

1. `inputAirline`: Un campo de selección que permite a los usuarios elegir una aerolínea de una lista de opciones disponibles.

2. `inputNum`: Un campo de entrada de texto que permite a los usuarios ingresar el número del vuelo.

3. `inputDestiny`: Un campo de entrada de texto que permite a los usuarios ingresar el destino del vuelo.

4. `inputNumPassengers`: Un campo numérico que permite a los usuarios ingresar el número de pasajeros que estarán en el vuelo. Debe ser un número entero mayor o igual a 1.

5. `inputDepartureDate`: Un campo que permite a los usuarios seleccionar la fecha de salida deseada.

6. `inputArrivalDate`: Un campo que permite a los usuarios seleccionar la fecha de llegada deseada.

7. `inputSeats`: Un campo numérico que permite a los usuarios ingresar el número de asientos que desean reservar. Debe ser un número entero mayor o igual a 1.

8. `inputOrigen`: Un campo de entrada de texto que permite a los usuarios ingresar el origen del vuelo.

Al concluir con el registro del vuelo; el empleado debe usar el botón de crear y eso hará que el programa guarde el vuelo recién creado 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/formulario%20vuelo%20exitoso.png?token=GHSAT0AAAAAACJXRZTTNT6GPLA6T4GLD3PKZKTEXVA)

**Crear Aeronave**
El usuario debe seleccionar la opción que dice crear aeronave para tomar una aeronave existente y regístrala a nombre de la aerolínea, a fin de que luego en el programa se le puedan asignar un vuelo de la misma aerolínea
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/creacion%20de%20aeronave1.png?token=GHSAT0AAAAAACJXRZTTFWN6OEONQOLQMXT2ZKTEYYA)

El programa le pedirá que especifique el tipo de aeronave entre los tipos de aeronaves disponible 
1. `Avión Comercial` es una aeronave de gran tamaño diseñada para transportar a un gran número de pasajeros en rutas regulares y programadas. Estos aviones suelen ser operados por aerolíneas comerciales y ofrecen comodidades y servicios a bordo para los pasajeros. Los aviones comerciales son ampliamente utilizados para vuelos de pasajeros a nivel global y ofrecen una amplia variedad de rutas y destinos.

2. `Helicóptero` es una aeronave que tiene rotores giratorios que le permiten despegar y aterrizar verticalmente, así como volar en cualquier dirección. Son versátiles y se utilizan en aplicaciones que van desde el transporte de pasajeros hasta operaciones de rescate y militares.

3. `Jet Privado` es una aeronave más pequeña y de lujo utilizada para el transporte exclusivo de individuos o grupos privados. Estos aviones son propiedad de individuos adinerados, empresas o se alquilan para uso personal. Los jets privados ofrecen un alto nivel de comodidad, privacidad y flexibilidad, y son ideales para viajes directos a destinos específicos sin necesidad de pasar por aeropuertos comerciales. Suelen estar equipados con comodidades personalizadas y ofrecen un servicio más exclusivo.

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/creacion%20de%20aeronave2.png?token=GHSAT0AAAAAACJXRZTTYER64WBQ3RRXAGRGZKTEZJQ)


Elije el tipo de aeronave y el modelo de los que el programa le muestra para evitar errores en la creación de aeronaves
   1. `Avión Airbus` se refiere a cualquier aeronave producida por Airbus S.A.S., una empresa europea líder en la industria aeroespacial. Los aviones Airbus son conocidos por su diseño avanzado y eficiencia en el consumo de combustible. Se utilizan en una variedad de aplicaciones, desde aviones comerciales para pasajeros hasta aviones de carga y militares.

    2. `Avión Boeing` se refiere a cualquier aeronave producida por The Boeing Company, una empresa estadounidense de renombre mundial en la industria de la aviación. Los aviones Boeing son conocidos por su versatilidad y se utilizan en una amplia gama de aplicaciones, desde aviones comerciales hasta aviones militares y de carga. Boeing es famoso por modelos icónicos como el 747 y el 737.

    2. `Avión  Antonov `se refiere a las aeronaves producidas por Antonov Corporation, una empresa de diseño y fabricación de aviones de Ucrania. Los aviones Antonov, como el Antonov An-124 Ruslán, son conocidos por su capacidad de carga excepcionalmente alta y se utilizan en aplicaciones de carga pesada y transporte aéreo militar. Los aviones Antonov son apreciados por su capacidad para transportar cargas voluminosas y pesadas a nivel mundial.
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/creacion%20de%20aeronave3.png?token=GHSAT0AAAAAACJXRZTTZB6K7JKUB7MBXHPWZKTEZZA)

AL COMPLETAR TODOS LOS CAMPOS, LE PERMITIRA A LA AEROLINEA REGISTRAR UNA AEROANVE DEL AEROPUERTO
1. `inputAirlineAvion`: Un campo de selección que permite a los usuarios elegir una aerolínea de una lista de opciones disponibles.

2. `inputBrand`: Un campo de selección que permite a los usuarios elegir la marca o tipo de aeronave de una lista que incluye "BOEING", "AIRBUS" y "ANTONOV".

3. `inputModel`: Un campo de selección que permite a los usuarios elegir el modelo específico de la aeronave, que depende de la marca seleccionada ("BOEING" o "AIRBUS").

4. `inputCapacity`: Un campo numérico que permite a los usuarios ingresar la capacidad máxima de la aeronave en términos de pasajeros o carga. Debe ser un número entero mayor o igual a 1.

5. `inputMaxSpeed`: La velocidad máxima de la aeronave, que en este caso está configurada en 1000, lo que puede ser un valor predeterminado o puede permitir que los usuarios lo ingresen.

6. `inputAutonomy`: La autonomía de la aeronave, que en este caso está configurada en 3000, al igual que la velocidad máxima, este valor puede ser un predeterminado o permitir que los usuarios lo ingresen.

7. `inputYear`: Un campo numérico que permite a los usuarios ingresar el año de fabricación de la aeronave. Debe ser un número entero mayor o igual a 2000.

8. `inputState`: Un campo que representa el estado de la aeronave, que en este caso está configurado en 2, lo que podría ser un valor predeterminado o depender del sistema.

9. `inputLocation`: Un campo de entrada de texto que permite a los usuarios ingresar la ubicación de la aeronave.

10. `inputId`: Un campo de entrada de texto que permite a los usuarios ingresar un identificador único o ID de la aeronave.

11. `inputFlying`: Un campo booleano que indica si la aeronave está volando (True) o no (False).

12. `inputMaxAltitude`: Un campo numérico que permite a los usuarios ingresar la altitud máxima a la que la aeronave puede volar. Debe ser un número entero mayor o igual a 1.

13. `inputNumEngines`: Un campo numérico que permite a los usuarios ingresar el número de motores de la aeronave. Debe ser un número entero mayor o igual a 1.

14. `inputCategory`: Un campo de entrada de texto que permite a los usuarios ingresar la categoría de la aeronave.

15. `inputSeatsAvion`: Un campo numérico que permite a los usuarios ingresar el número de sillas o asientos en la aeronave.

16. `inputAvailableSeats`: Un campo numérico que permite a los usuarios ingresar el número de sillas disponibles en la aeronave. Debe ser un número entero mayor o igual a 1

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/creacion%20de%20aeronave4.png?token=GHSAT0AAAAAACJXRZTT52ZGH57A5GUQG7RQZKTE2NA)

**Ver aviones**

Al dar clic en la opción de ver aviones, el programa deberá permitirle seleccionar entre las aerolíneas disponibles, a lo que el trabajador deberá escoger la que le pertenece

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/verAviones1.png?)

Si el usuario selecciona una aerolínea que no tiene ninguna aeronave asociada no se le desplegara ninguna 

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/Aerolinea%20sin%20aeroanves.png?token=GHSAT0AAAAAACJXRZTTW7FL4JK2FBCJR2QEZKTE5GA)
Si por el contario la aerolínea cuenta con aeronaves asociadas se le mostrara una fotografía de la aeronave y su respecto especificaciones
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/Aerolinea%20con%20aeronaves.png?token=GHSAT0AAAAAACJXRZTSJIY4EVORMCAP4PSIZKTE5UQ)

**Ver vuelos**
El usuario deberá seleccionar la opción de ver vuelos y seleccionar su aerolínea para desplegar todos sus vuelos 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/verVuelos1.png?token=GHSAT0AAAAAACJXRZTTBYQC5KZ4LLBTVU76ZKTE7TA)

Si el usuario selecciona una aerolínea que no tiene ningún vuelo asociado no se le desplegara ningún vuelo y le mostrara una advertencia que dice que la aerolínea no cuenta con ningún vuelo creado 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/VerVuelos2.png?token=GHSAT0AAAAAACJXRZTTHT5KQ6PJVNGCL4DCZKTFASQ)


Al contar con vuelos asociados, se desplegaran todos ellos los siguientes datos:

1. `Origen`: Representa el origen del vuelo.

2. `Destino`: Muestra el destino del vuelo.
3. `Numero de pasajeros`: Indica el número de pasajeros en el vuelo.
4. `Fecha de salida`: Muestra la fecha de salida del vuelo.
5. `Fecha de llegada`: Indica la fecha de llegada del vuelo.
6. `Asientos`: Muestra el número de asientos en la aeronave utilizada.
7. `Aeronave`: Representa el identificador de la aeronave utilizada en el vuelo.

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/verVuelos3.png?token=GHSAT0AAAAAACJXRZTTA4MGCDKPGTPUHTLCZKTE76Q)

**Asignar vuelos a las aeronaves**
Asignar vuelos a aeronaves es un proceso clave donde se eligen aviones disponibles para cumplir con vuelos específicos. Esto implica verificar si las aeronaves cumplen con los requisitos del vuelo, como capacidad y fechas disponibles. La asignación se realiza de manera eficiente para maximizar la utilización de las aeronaves. Después, se registran y confirman estas asignaciones con los equipos operativos y de tripulación. La adaptabilidad a cambios de último momento es esencial, y una asignación eficiente contribuye a la operación sin problemas y a la satisfacción de la aerolínea y los pasajeros.

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/AsignarVuelos1.png?token=GHSAT0AAAAAACJXRZTSNPM5EH7L7P4OQULWZKTFBIQ)

Puede existir el caso en que la aerolínea tenga vuelos asociados pero no aeronaves asociados, por lo que se le desplegaría la opción de ver los vuelos o ver las aeronaves; dependiendo de lo que tenga disponible pero en el otro parámetro le aparecerá un mensaje de opción no valida, por lo que no se podrá la asignación
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/AsignarVuelos2.png?token=GHSAT0AAAAAACJXRZTT5ZUFI5SCTWPFKDYGZKTFBZQ)

Al cumplir ambos parámetros el operario deberá seleccionar entre las aeronaves disponibles y los vuelos a fin de hacer dicha asignación 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/AsignarVuelos3.png?token=GHSAT0AAAAAACJXRZTTWGMGTWUCYHCLSGESZKTFCSA)

Después de elegir el vuelo y la aeronave el operario podrá oprimir el botón y el programa hará la asignación de vuelo y se le mostrará un mensaje confirmando las acción realizada

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/AsignarVuelos4.png?token=GHSAT0AAAAAACJXRZTTP3ODHHNA4X5HJXQKZKTFC6A)

**Eliminar Vuelos**

El usuario selecciona la opción Eliminar vuelo del menú secundario, al hacerlo, se le desplegara las opciones de seleccionar la aerolínea y seleccionar de la lista desplegable el vuelo que desea eliminar; si se cumple con todos los parámetros; el empleado podrá eliminar el vuelo y se le mostrara un mensaje que muestra que la acción se ha realizado correctamente 

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/eliminarVuelo2.png?token=GHSAT0AAAAAACJXRZTSQW45V6WCC4QVNG3IZKTFFKA)

Si por el contario la aerolínea no cuenta con vuelos o ya han sido eliminados todos; esta opción no será valida 

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/eliminarVuelo3.png?token=GHSAT0AAAAAACJXRZTTPJGII3RQCH5BMLGOZKTFEZA)

**Eliminar aerolínea**
Selecciona la opción de eliminar aerolínea de la lista desplegable del menú secundario; al lo que le debe sumar la selección de la aerolínea deseada de todas las aerolíneas registradas 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/eliminarAerolinea1.png?token=GHSAT0AAAAAACJXRZTSOLX5JVJ4LC7U334AZKTFFYA)

Al seleccionar una aerolínea de la lista desplegable; y presionar el botón de eliminar, el programa le mostrara un mensaje diciendo que la aerolínea se ha eliminado significando que la acción se realizo con éxito
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/eliminarAerolinea2.png?token=GHSAT0AAAAAACJXRZTSJAFRT4EWMH6YHSA6ZKTFGJA)

Si se quisiera volver a acceder a dicho opción para eliminar otra aerolínea se podría evidenciar que la aerolínea recién eliminada no es parte de la lista desplegable; confirmando que efectivamente se realizó la eliminación, junto con cualquier aeronave o vuelo asociado a dicha aerolínea 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/eliminarAerolinea3.png?token=GHSAT0AAAAAACJXRZTSHLENLFO6KWECEKG2ZKTFGSQ)

##### 2.2. Torre de Control 
**Crear puerta de embarque**
Para cumplir con dicha función de crear puertas de embarque; el empleado debe acceder al menú a través de torre de control; a lo que se desplegara un menú secundario y deberá elegir la opción de crear puerta; al acceder así le permitirá recibir la opción de dar el nombre a la puerta y donde se encuentra ubicada en la terminal del aeropuerto; y al pulsar el botón de crear; el programa le mostrara un mensaje de confirmación de la creación de una puerta 

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/crearPuerta1.png?token=GHSAT0AAAAAACJXRZTTGX2BYLB5QMFTOIR2ZKTFJ7Q)

**Asignar puerta de embarque**

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/asignarPuerta1.png?token=GHSAT0AAAAAACJXRZTSOUUW3KHT6ZMAPXROZKTFHFQ)

El operario deberá seleccionar entre todas las puertas una puerta disponible; una aerolínea del aeropuerto que le permitirá desplegar todos los vuelos de dicha aerolínea a fin de solo asignar vuelos asociados a una aerolínea especifica
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/asignarPuerta2.png?token=GHSAT0AAAAAACJXRZTTYWUZO6RF7NRYZTMMZKTFIIA)

Al hacer la asignación de dicha puerta le saldrá un mensaje en la pantalla confirmando la acción realizada
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/asignarPuerta4.png?token=GHSAT0AAAAAACJXRZTTEOM7K7PIOTYSQUFEZKTFJAQ)

**Eliminar Puerta de embarque**
Al seleccionar la opción de eliminar puerta de embarque se le mostrar todas las puertas creadas en la terminal aérea; a las que podrá escoger una y así mismo al presionar el botón de eliminar, se realizara la opción informándole al empleado que la acción se realizó con éxito

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/eliminarPuerta1.png?token=GHSAT0AAAAAACJXRZTTDOEGHZE6RMCCA2IQZKTFNSQ)

**Permiso de vuelo**
La función `atcPermission` se encarga de gestionar los permisos de control de tráfico aéreo (ATC) para un vuelo específico. Al recibir el identificador de vuelo, el nombre de la aerolínea y el tipo de permiso, la función busca la información correspondiente en la sesión de la aerolínea y el aeropuerto. Luego, utiliza el control de tráfico aéreo (ATC) para solicitar el permiso específico para la aeronave asociada. Es importante destacar que la función se ejecutará solo si hay un control de tráfico aéreo disponible. Este proceso ayuda a coordinar y gestionar la interacción entre las aeronaves y el control de tráfico aéreo en el sistema.

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/permisode%20vuelo1.png?token=GHSAT0AAAAAACJXRZTSSGFNEKTUE7VE4YWOZKTC7CQ)

**Notificar ubicación**
Al selecciona esta opción del menú, el operario podrá seleccionar el botón de notificar; lo que hará que todas las aeronaves envíen su ubicación y se le mostrara un mensaje en la pantalla notificando al operario que se realizó la acción con éxito y los aviones se notificaron 

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/notificarUbicacion1.png?token=GHSAT0AAAAAACJXRZTSRGEQWOGUYGA4BW76ZKTDARQ)

**Ver puertas**
La opción de ver puertas muestra la información de la puerta 

1. `Location`: se refiere a la posición o lugar específico de algo en el espacio. En términos generales, una "location" indica dónde se encuentra un objeto, evento o entidad geográfica

2. `id`: se refiere comúnmente a "identificador" o "identificación". En un contexto más amplio, un "ID" es un conjunto de caracteres o números únicos asignados a un objeto, entidad o individuo con el fin de distinguirlo de otros.

3. `Available`: Se utiliza para describir algo que está libre, accesible o listo para ser utilizado o aprovechado en un determinado contexto. Por ejemplo, un recurso puede estar "available" si está disponible para su asignación o uso
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/verPuertas1.png?token=GHSAT0AAAAAACJXRZTTF33JK5LDO5KJCCECZKTDEBA)
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/verPuertas2.png?token=GHSAT0AAAAAACJXRZTS7J5UDC7WGMBMZZC4ZKTDEPQ)

**Ver ubicaiones**
La última opción de la torre de control muestra la ubicación de todas las aeronaves; la cual se envio en el momento que se hizo uso de la opción notificar aeronaves; muestra el id de la aeronave y el espacio en el que esta del aeropuerto

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/ubicacion%20de%20aviones.png?token=GHSAT0AAAAAACJXRZTTRZENEU7D7TQYWTVAZKTDKWA)

### Acceso de pasajero
#### Inicio 
Al ingresar al programa como un pasajero; le muestra el menú de inicio que cuenta con una breve descripción del aeropuerto Alfonso Bonilla Aragón, junto con un breve video sobre las instalaciones y la pista de aterrizaje 

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/inicio1.png?token=GHSAT0AAAAAACJXRZTSM4OBDHM6AO5Q7AZMZKTDPAA)

En la opción del inicio, justo debajo del video, el programa cuenta con una breve descripción de los servicios que ofrece el aeropuerto

**Cafeteria**
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/inicio2.png?token=GHSAT0AAAAAACJXRZTTEYVRIYW3R6U7UZYGZKTDSPQ)

**Tiendas**
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/inicio3.png?token=GHSAT0AAAAAACJXRZTTO2IU2TDXLHMYLIIEZKTDU3Q)

**Parqueadero**
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/inicio4.png?token=GHSAT0AAAAAACJXRZTSLYEUH6G5DKQC7E24ZKTDVKQ)

#### Informacion del pasajero
Al acceder al menú secundario a través de la opción de información del pasajero; permitirá la usuario inscribirse para hacer cualquier tipo de acción dentro del aeropuerto

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/informacionPasajero1.png?token=GHSAT0AAAAAACJXRZTSQ6Y3TBJJCT6RGEC4ZKTDW6A)

Se le pedirá información al usuario que agregue información tal como:
1. `Nombre`: Representa el nombre del usuario.
2. `ID`: Muestra el identificador único del usuario.
3. `Número telefónico`: Indica el número de teléfono del usuario.
4. `Fecha de nacimiento`: Muestra la fecha de nacimiento del usuario.
5. `Género`: Representa el género del usuario.
6. `Correo electrónico`: Indica la dirección de correo electrónico del usuario.
7. `Número de equipaje de bodega`: Muestra el número de piezas de equipaje de bodega del usuario.
8. `Información médica de emergencia`: Indica el contacto de emergencia proporcionado por el usuario.
9. `Nacionalidad`: Representa la nacionalidad del usuario.
10. 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/informacionPasajero2.png?token=GHSAT0AAAAAACJXRZTTZUHF5764N6QLFBUIZKTDZYA)

#### Ver vuelos 
El usuario deberá seleccionar la opción de ver vuelos y seleccionar su aerolínea para desplegar todos sus vuelos 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/verVuelos1.png?token=GHSAT0AAAAAACJXRZTTCA46YTSZPEWJVLVUZKTA46A)
Si el usuario selecciona una aerolínea que no tiene ningún vuelo asociado no se le desplegara ningún vuelo y le mostrara una advertencia que dice que la aerolínea no cuenta con ningún vuelo creado 
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/VerVuelos2.png?token=GHSAT0AAAAAACJXRZTSP5RIKOHDMSGHNILOZKTA5WQ)

#### Reservar vuelos
Al seleccionar la opción de reservar el vuelo; después de haber visto de los vuelos disponibles; el usuario puedo reservar un vuelo seleccionando la aerolínea y el avión a dicho destino que desea

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/reservarvuelo2.png?token=GHSAT0AAAAAACJXRZTTC4ARUUCJBJ6NWMV4ZKTEDGQ)

#### Información sobre los países de destino
Esta opción del menú permite al viajero conocer la información básica de cualquier país que tenga planeado viajar, solo accediendo a través del nombre del país

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/paises1.png?token=GHSAT0AAAAAACJXRZTSK6JK4VZVS6TKJ4TGZKTEF2Q)
1. `Nombre del país`: Representa el nombre común del país.
2. `Moneda`: Indica la moneda utilizada en el país.
3. `Idioma`: Muestra el o los idiomas oficiales hablados en el país.
4. `Ciudad Capital`: Representa la capital del país.
5. `Región`: Indica la región geográfica a la que pertenece el país.
6. `Población`: Muestra la población total del país.
7. `Imagen de la Bandera`:
    - En caso de que no se encuentre una imagen válida, se muestra una advertencia indicando que no se encontró la bandera del país.

![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/paises2.png?token=GHSAT0AAAAAACJXRZTSXVRV7ENP4EL674LKZKTEGGQ)

#### Ver mis vuelos
Al contar con un vuelo asociado al viajero, se desplegaran los siguientes datos:

1. `Origen`: Representa el origen del vuelo.
2. `Destino`: Muestra el destino del vuelo.
3. `Numero de pasajeros`: Indica el número de pasajeros en el vuelo.
4. `Fecha de salida`: Muestra la fecha de salida del vuelo.
5. `Fecha de llegada`: Indica la fecha de llegada del vuelo.
6. `Asientos`: Muestra el número de asientos en la aeronave utilizada.
7. `Aeronave`: Representa el identificador de la aeronave utilizada en el vuelo.
![Menu de inicio](https://raw.githubusercontent.com/Rui091/cVersionPoo/main/vermisvuelos1.png?token=GHSAT0AAAAAACJXRZTTH4RFOEE6IYEZQQQGZKTEL5Q)


### 4. Solución de Problemas Comunes
##### 4.1. No se puede abrir el programa
Si experimenta problemas para abrir el programa, asegúrese de que su sistema cumple con los requisitos del sistema mencionados en la sección 1.1. Si el problema persiste, comuníquese con nuestro equipo de soporte técnico.

##### 4.2. Errores en la creación de aeronaves y reservas
Si encuentra errores en la creación de reservas y aeronaves, verifique que haya ingresado la información del usuario correctamente. Si el problema persiste, póngase en contacto con nuestro equipo de soporte técnico para obtener ayuda.
### 5. Diagrama UML

Enlace de drawio con la relacion entre las diferentes clases y suclases 
 https://app.diagrams.net/#G1cGocRfbN9pkQDUm0T99rlcJZp0B5Z3Np
### 6. Contacto y Soporte Técnico

Si tiene alguna pregunta o necesita asistencia, no dude en ponerse en contacto con nuestro equipo de soporte técnico en chino123@javerianacali.edu.co, marcor27@javerianacali.edu.co, o llamando al +573137049579.


