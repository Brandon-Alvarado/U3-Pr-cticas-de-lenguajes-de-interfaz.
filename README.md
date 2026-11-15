# Prácticas de Lenguajes de Interfaz 

* **Materia:** Lenguajes de Interfaz
* **Alumno:** Brandon Gael Alvarado Covarrubias
* **Horario:** 10:00 a 11:00
* **Docente:** Dr. José Luis Medina Jiménez

---
## 1. Programación de procedimientos
* **Archivo:** [`Procedimientos.asm`](./Codigos/Procedimientos.asm)
* **Descripción:** Uso de procedimientos en lenguaje ensamblador, demostrando cómo se pueden llamar y retornar de ellos
* **Comprobación:** Se ejecuta el programa y se observa que se imprimen los mensajes de inicio, dentro del procedimiento y fin del programa en el orden correcto, confirmando que los procedimientos funcionan correctamente

## 2. Validación de cadena vacía
* **Archivo:** [`Cadena_Vacia.asm`](./Codigos/Cadena_Vacia.asm)
* **Descripción:** Solicita al usuario que ingrese una cadena de texto y luego verifica si la cadena está vacía o no[. Si la cadena está vacía, se muestra el mensaje `"VACIA"`; de lo contrario, se muestra `"NO VACIA"`
* **Comprobación:** Se ejecuta el programa y se ingresa una cadena de texto. Si la cadena está vacía, se muestra el mensaje `"VACIA"`; de lo contrario, se muestra `"NO VACIA"`
  
## 3. Parámetros por pila y limpieza
* **Archivo:** [`Parametros_Limpieza.asm`](./Codigos/Parametros_Limpieza.asm)
* **Descripción:** Demuestra el uso de parámetros pasados por pila y la limpieza de la misma
* **Comprobación:** Al depurar, se observa que `EAX = 75` y `EBX` sigue valiendo `999`

## 4. Direcciones de retorno
* **Archivo:** [`direcciones de retorno.asm`](./Codigos/direcciones%20de%20retorno.asm)
* **Descripción:** Este programa muestra las direcciones de retorno de las funciones `main`, `procUno` y `procDos`
* **Comprobación:** Al ejecutar el programa, se imprimen las direcciones de retorno en hexadecimal, demostrando cómo se almacenan y recuperan en la pila durante las llamadas a funciones

## 5. Macros
* **Archivo:** [`macros.asm`](./Codigos/macros.asm)
* **Descripción:** Muestra el uso de macros; en este caso se muestran dos macros, una para mostrar un mensaje y otra para multiplicar dos números
* **Comprobación:** Al ejecutar el programa se muestra un mensaje de bienvenida, luego un mensaje de despedida y finalmente el resultado de la multiplicación de dos números (`4 * 5 = 20`)



