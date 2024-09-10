# Proyecto-1-SO
Repositorio para SO

# Instrucciones de Configuración y Compilación

## Pre-requisitos

Asegúrate de tener instalados los siguientes componentes en tu sistema antes de compilar el proyecto:

- **gcc**: El compilador de C/C++. Puedes instalarlo en Ubuntu con el siguiente comando:

    ```bash
    sudo apt-get install gcc
    ```

## Compilación

Ingresar la siguiente línea de código en el directorio donde se encuentre el archivo:


    ```bash
    gcc -o minishell minishell.c -pthreads
    ```

Una vez completados estos pasos, se generará 1 ejecutable:

El ejecutable minishell, el cual contiene el intérprete de comandos. Se puede ejecutar usando:

    ```bash
    ./minishell
    ```

Los comandos disponibles y más información se puede encontrar en el PDF adjunto.
