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
       * solicitar la sucursal al que pertenece el empleado
       * solicitar la cantidad de empleados
       * solicitar el nombre(s) de empleado
       * solicitar el apellido paterno
       * solicitar el apellido materno
       * solicitar el rfc
       * solicitar el curp
       * solicitar el correo electronico
       * solicitar el numero de telefono
       * solicitar el area donde se encuentra
       * se hace ciclo if de los puestos
       * solicitar el salario semanal del empleado
       * solicitar el tiempo que lleva trabajando en la empresa
       * se hace sentencia if de acuerdo a los años que ha trabajado para sacar su isr
salida:
