# **_QueridasFunciones_**

## **_Cómo crear algunas funciones, mis primeros pasos utilizando JavaScript._**

### **_Antes de comenzar..._**

**_¿Qué son las funciones?_**

- **_Las funciones son uno de los bloques de construcción fundamentales en JavaScript._**
  
- **_Una función en JavaScript es similar a un procedimiento — un conjunto de instrucciones que realiza una tarea o calcula un valor, pero para que un procedimiento califique como función, debe tomar alguna entrada y devolver una salida donde hay alguna relación obvia entre la entrada y la salida._**
  
- **_Para usar una función, debes definirla en algún lugar del ámbito desde el que deseas llamarla._**

- **_Las funciones son sumamente importantes en Javascript, aquí en nuestro curso trataremos de practicar con varios ejercicios para que puedas aprender que es una función y su utilidad._**

### **_Definir funciones:_**

- **_La definición de una función (también llamada declaración de función o sentencia de función) consiste de la palabra clave (reservada)  ```function```, seguida por:_**

  - **_El nombre de la función (opcional)._**
  - **_Una lista de argumentos para la función, encerrados entre paréntesis y separados por comas (,)._**
  - **_Las sentencias JavaScript que definen la función, encerradas por llaves, { }._**

- **_Por ejemplo, el siguiente código define una función simple llamada square ("cuadrado"):_**
```
function square(number) {
  return number * number;
}
```
- **_La función square toma un parámetro, llamado number._**
  
- **_La función consta de una declaración que dice devuelva el parámetro de la función (es decir, ```number```) multiplicado por sí mismo._**
  
- **_La instrucción ```return``` especifica el valor devuelto por la función:_**
```
return number * number;
```
