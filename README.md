# [Linux Fundamentals]

## Descripción

*En este proyecto aprendí por qué Linux es tan común hoy en día, interactue con mi primera maquina de Linux, ejecuté algunos de los comandos más fundamentales, tuve una introducción a cómo navegar por el sistema de archivos y cómo podemos usar comandos como find y grep para hacer que la búsqueda de datos sea aún más eficiente y aprendí sobre algunos de los operadores importantes del terminal. El objetivo de este laboratorio fue familiarizarse con la navegación del sistema de archivos, la interacción con comandos esenciales y la manipulación básica de datos a través de la terminal.*

---

## Herramientas y Conceptos Evaluados
*   **Plataforma:** TryHackMe
*   **Sistema Operativo / Entorno:** Linux Ubuntu
*   **Herramientas Clave:** Arquitectura de directorios Linux, comandos de navegación, lectura de archivos y búsqueda de datos.

---

## Despliegue del Laboratorio

### Interacción con la Terminal y Navegación Básica
El primer objetivo fue entender dónde estoy posicionada en el sistema y cómo moverme entre directorios sin usar una interfaz gráfica.

*   **Comando `pwd` (Print Working Directory):** Utilizado para verificar la ruta absoluta actual en el sistema.
*   **Comando `ls` (List):** Utilizado para listar los archivos y carpetas dentro del directorio actual.
*   **Comando `cd` (Change Directory):** Utilizado para navegar hacia carpetas específicas.

---

## Conocer los Operadores más Importantes

*  **Operador `&` :** Permite ejecutar comandos en segundo plano desde la terminal.
*  **Operador `&&` :** Permite combinar varios comandos en una sola línea de la terminal.
*  **Operador `>` :** Es un redirector, podemos tomar la salida de un comando y dirigirla a otro sitio.
*  **Operador `>>` :** Realiza la misma función que > pero agrega la salida en lugar de reemplazar, nada se sobrescribe.
  
    ```bash
    # echo /whoami | ls/cat/pwd | find/greep
    # &/&&/>/>>
