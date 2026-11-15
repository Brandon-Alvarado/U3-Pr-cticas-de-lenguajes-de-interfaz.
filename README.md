# Prácticas de Lenguajes de Interfaz 

* **Materia:** Lenguajes de Interfaz[cite: 1]
* **Alumno:** Brandon Gael Alvarado Covarrubias[cite: 1]
* **Horario:** 10:00 a 11:00[cite: 1]
* **Docente:** Dr. José Luis Medina Jiménez[cite: 1]

---

## 1. Validación de cadena vacía
* **Archivo:** [`Cadena_Vacia.asm`](./Cadena_Vacia.asm)
* **Descripción:** Solicita al usuario que ingrese una cadena de texto y luego verifica si la cadena está vacía o no[cite: 1]. Si la cadena está vacía, se muestra el mensaje `"VACIA"`; de lo contrario, se muestra `"NO VACIA"`[cite: 1].
* **Comprobación:** Se ejecuta el programa y se ingresa una cadena de texto[cite: 1]. Si la cadena está vacía, se muestra el mensaje `"VACIA"`; de lo contrario, se muestra `"NO VACIA"`[cite: 1].

## 2. Direcciones de retorno
* **Archivo:** [`direcciones de retorno.asm`](./direcciones%20de%20retorno.asm)
* **Descripción:** Este programa muestra las direcciones de retorno de las funciones `main`, `procUno` y `procDos`[cite: 2].
* **Comprobación:** Al ejecutar el programa, se imprimen las direcciones de retorno en hexadecimal, demostrando cómo se almacenan y recuperan en la pila durante las llamadas a funciones[cite: 2].

## 3. Macros
* **Archivo:** [`macros.asm`](./macros.asm)
* **Descripción:** Muestra el uso de macros; en este caso se muestran dos macros, una para mostrar un mensaje y otra para multiplicar dos números[cite: 3].
* **Comprobación:** Al ejecutar el programa se muestra un mensaje de bienvenida, luego un mensaje de despedida y finalmente el resultado de la multiplicación de dos números (`4 * 5 = 20`)[cite: 3].

## 4. Parámetros por pila y limpieza
* **Archivo:** [`Parametros_Limpieza.asm`](./Parametros_Limpieza.asm)
* **Descripción:** Demuestra el uso de parámetros pasados por pila y la limpieza de la misma[cite: 4].
* **Comprobación:** Al depurar, se observa que `EAX = 75` y `EBX` sigue valiendo `999`[cite: 4].

## 5. Programación de procedimientos
* **Archivo:** [`Procedimientos.asm`](./Procedimientos.asm)
* **Descripción:** Uso de procedimientos en lenguaje ensamblador, demostrando cómo se pueden llamar y retornar de ellos[cite: 5].
* **Comprobación:** Se ejecuta el programa y se observa que se imprimen los mensajes de inicio, dentro del procedimiento y fin del programa en el orden correcto, confirmando que los procedimientos funcionan correctamente[cite: 5].
