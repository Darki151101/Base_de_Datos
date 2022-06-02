
## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2)

Es un tipo de sistema de gestión de datos diseñado para habilitar y dar soporte a las tareas de inteligencia empresarial (BI), especialmente las analíticas.

2. Realiza un diseño del modelo en estrella (valor 2)

![image](https://user-images.githubusercontent.com/99523872/171659243-4713f801-a4f8-455e-b0a0-0ba776f70902.png)


3. Realiza un diseño del modelo copo de nieve (valor 2)

![image](https://user-images.githubusercontent.com/99523872/171660017-01e87c64-b92b-48f1-9695-bf49d1031901.png)


## Práctica 7
### Funciones en SQL
Objetivo: Demostrar el uso y aplicación en una base de datos para mejorar la gestión

Ejercicio:

1. Calcula el número total de productos que hay en la tabla productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/99523872/171661291-bcffef8c-5785-45d5-8a9e-502724f1f071.png)

![image](https://user-images.githubusercontent.com/99523872/171661379-02780419-ce99-4d30-b329-12629c017db7.png)

2. Muestra el número total de productos que tiene cada uno de los fabricantes. El listado
también debe incluir los fabricantes que no tienen ningún producto. El resultado
mostrará dos columnas, una con el nombre del fabricante y otra con el número de
productos que tiene. Ordene el resultado descendentemente por el número de
productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/99523872/171666083-413627eb-44f8-4b24-823d-5b87a99ad2bc.png)

![image](https://user-images.githubusercontent.com/99523872/171666198-3145bd6e-ff28-4023-a4e9-b0a93f1e7e8d.png)

3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)

![image](https://user-images.githubusercontent.com/99523872/171671248-486c1d1d-e78b-414a-9ab6-b43d1995450d.png)

![image](https://user-images.githubusercontent.com/99523872/171671366-0d0f923d-5ccb-41a5-911d-e372c0cf8469.png)

4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)

![image](https://user-images.githubusercontent.com/99523872/171671513-b2cbadf4-936e-440d-8083-29461f72be36.png)

![image](https://user-images.githubusercontent.com/99523872/171671624-04dcf7e8-93f3-416d-bf69-752264092fe1.png)

## Práctica 8.
### Disparadores (Triggers)

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Si el nuevo valor de la nota que se quiere insertar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere insertar es mayor que 10, se
  guarda como 10.

● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Si el nuevo valor de la nota que se quiere actualizar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere actualizar es mayor que 10, se
  guarda como 10.
  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.
