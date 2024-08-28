Este informe describe el proceso seguido para la instalación del sistema operativo xv6 en un entorno de desarrollo basado en Visual Studio Code utilizando WSL. El objetivo es documentar cada paso para asegurar la correcta configuración y compilación del proyecto xv6.

Prerrequisitos
Antes de comenzar, aseguré que el entorno cumpliera con los siguientes requisitos:

WSL: Instalado y configurado.
Distribución de Linux: Ubuntu 20.04 LTS en WSL.
Visual Studio Code: Instalado y configurado con la extensión WSL.
Git: Instalado para clonar el repositorio de xv6.
QEMU: Emulador necesario para ejecutar xv6.

Pasos de Instalación
1. Clonar el repositorio de xv6
2. Configurar el entorno de compilación
3. Compilar y verificar la instalación
4. Compilación de QEMU
5. Ejecutar el xv6 con "make qemu"

Problemas
- Muchas Dependencias fueron necesitadas
- QEMU se ejecutaba pero no salia la interfaz, pero al final lo solucione al usar la carpeta "xv6-public"
- El toolchain fue complejo de instalar pero con paciencia y algunos tutoriales se pudo instalar