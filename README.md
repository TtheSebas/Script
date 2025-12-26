# Práctica 9: Programación de Scripts en Bash Shell

[cite_start]**Institución:** Escuela Politécnica Nacional 
[cite_start]**Facultad:** Ingeniería en Sistemas   
[cite_start]**Materia:** Laboratorio de Sistemas Operativos 
[cite_start]**Semestre:** 2023-A 
[cite_start]**Tema:** Scripts en Linux 

## 📋 Descripción General
Este repositorio contiene el desarrollo de la Guía de Laboratorio N°9. [cite_start]El objetivo es la creación y ejecución de scripts en el Shell de Linux (Bash), implementando variables, control de flujo, bucles, arreglos y funciones.

## 📂 Contenido del Proyecto

### 1. Scripts de Procedimiento (Ejercicios Complejos)
[cite_start]Estos scripts corresponden a la sección 3 de la guía y resuelven problemas específicos mediante tareas programadas.

* **`juego.sh` (Piedra, Papel o Tijera):**
    * Script interactivo que compite contra la PC seleccionando una opción aleatoria.
    * [cite_start]Se ejecuta en un bucle infinito con una pausa de 5 minutos entre partidas.
    * *Uso:* Seleccionar opción (1, 2 o 3) y ver el resultado.

* **`calculadora.sh` (Calculadora Iterativa):**
    * Realiza operaciones básicas (suma, resta, multiplicación, división).
    * Permite reutilizar el resultado anterior para la siguiente operación.
    * [cite_start]Valida la división por cero y espera 0.5 minutos entre cálculos.

* **`menu_archivos.sh` (Gestión de Archivos):**
    * Menú recurrente (cada 10 minutos) con 7 opciones.
    * [cite_start]Utiliza funciones para crear, borrar, listar y buscar archivos o directorios.

### 2. Scripts de Marco Teórico (Ejemplos)
[cite_start]Colección de 15 scripts básicos realizados siguiendo las figuras de la guía para demostrar la sintaxis de Bash:

* **Conceptos Básicos:** `hola.sh` (Fig. 1), `variables.sh` (Fig. 2), `parametros.sh` (Fig. 3).
* **Aritmética:** `suma.sh` (Fig. 4 - uso de `let` y `bc`).
* **Arreglos:** `ciudad.sh` (Fig. 5), ejemplos de relleno y rangos (Fig. 6).
* **Condicionales:** `myScript.sh` (Fig. 7 - numérico), `if.sh` (Fig. 8 - cadenas).
* **Selectores:** `cate.sh` (Fig. 9 y 10 - estructura case).
* **Bucles:** `myloop.sh` (Fig. 11 - while), `for.sh` (Fig. 12), `until.sh` (Fig. 13), `select.sh` (Fig. 14).
* **Funciones:** `funcion.sh` (Fig. 15).

## 🚀 Instrucciones de Ejecución

[cite_start]Para ejecutar cualquiera de los scripts contenidos en este repositorio, es necesario otorgar permisos de ejecución previamente.

1.  **Dar permisos a todos los scripts:**
    ```bash
    chmod +x *.sh
    ```

2.  **Ejecutar un script específico:**
    ```bash
    ./nombre_del_script.sh
    ```

---
**Nota:** Los tiempos de espera (`sleep`) en los ejercicios de procedimiento están configurados en segundos (300s, 30s, 600s) para cumplir con los requisitos de tiempo de la guía.
