# T3A6---Ejercicio-con-POO

## Etapa 1, Descripcion del problema.
Desarrolla la solución para los siguientes ejercicios:

Utiliza la metodología de las 6D y el paradigma de la Programación Orientada a Objetos para resolver el siguiente enunciado:

Una fábrica textil desea llevar el control de la nómina de sus empleados en la matriz ubicada en Teziutlán y dos sucursales más (sucursal cdmx, sucursal malecónVeracruz). Para calcular la nómina debe indicarse la cantidad de empleados, número de contrato, tipo de empleado, años de antigüedad, las horas laborales de contrato y el salario base, además de su información básica (nombre, apellidos, RFC, CURP, email y teléfono).
Además del sueldo base se debe agregar un bono por antigüedad bajo las siguientes condiciones:
* De 0 a 2 años de antigüedad no se asigna bono.
* De 3 a 5 años de antigüedad se asigna un bono del 3% y si el trabajador es administrativo entonces el bono será del 4%.
* De 6 a 10 años de antigüedad recibe un bono adicional del 8% y si el trabajador es administrativo, entonces el bono será del 12%.

Realizar el cálculo respectivo del ISR sobre el sueldo bruto acorde a la siguiente imagen:

![](https://github.com/Matshota16/T3A6---Ejercicio-con-POO/blob/8fca7d976f52216f0b773c0e41d60244961b016d/Ejemplo-de-Como-Calcular-el-ISR.png)

## Etapa 2, diseño del problema.

* entrada-

solicitar los datos del empleado:
* solicitar la sucursal al que pertenece el empleado.
* solicitar la cantidad de empleados.
* solicitar el nombre(s) del empleado.
* solicitar el apellido paterno.
* solicitar el apellido materno.
* solicitar el rfc.
* solicitar el curp.
* solicitar el correo electronico.
* solicitar el numero de telefono.
* solicitar el area donde se encuentra.
* se hace ciclo if de los puestos.
* solicitar el salario semanal del empleado.
* solicitar el tiempo que lleva trabajando en la empresa.
* se hace sentencia if de acuerdo a los años que ha trabajado para sacar su isr.
-salida:


~~~~~
+------------------------------------------------------------------+
|  10 NUNMEROS IMPARES Y SU PRODUCTO                               |
+------------------------------------------------------------------+
| 1.ingrese la sucursal:   la sucursal es   sucursal cdmx          |
| 2.ingrese el numero de empleados:  el numero de empleados es 300 |
| 3.ingrese el nombre del empleado:    Mateo                       |
| 4.ingrese el apellido paterno:    cordova                        |
| 5.ingrese el apellido materno:   Nativo                          |
| 6.ingrese el rfc:           12345678                             |
| 7.ingrese el curp: mate12334drfgfdh                              |
| 8.ingrese el correo electronico: Sr.NavikOficial16@gmail.com     |
| 9.ingrese el numero de telefono: 1223334422                      |
| 10.ingrese el numero de contrato del empleado: 12                |
|11. introduce la seleccion a la que pertenece: contador           |
|12.ingrese cuanto gana semanalmente: 1200                         |
|13.ingrese los años que lleva el empleado en la empresa:  1       |
|14. su salario neto es: 1137.40264                                |
|15. su nomina por la empresa es: 1137.40264                       |
+------------------------------------------------------------------+
~~~~~~~~

## Etapa 3.
  ![](https://github.com/Matshota16/T3A6---Ejercicio-con-POO/blob/3d5eb73df8f467c38bc336e532b6be259f2404cc/T3A6.png)
