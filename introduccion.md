# Introducción (¿Qué es WSL?)

El Subsistema de Windows para Linux (WSL) permite a los desarrolladores ejecutar un entorno de GNU/Linux, incluida la mayoría de las herramientas de línea de comandos, utilidades y aplicaciones, directamente en Windows, sin modificar y sin la sobrecarga de una máquina virtual tradicional o una configuración de arranque dual.

![WSL](https://files.virgool.io/upload/users/7514/posts/gkyzfiy2mrnl/ahcoxbg5wvqs.png)

## ¿Es mejor WSL u otras aplicaciones como VirtualBox?
WSL necesita **menos recursos (CPU, memoria y almacenamiento) que una máquina virtual completa**. Asimismo, WSL también te *permite ejecutar aplicaciones y herramientas de línea de comandos de Linux junto con la línea de comandos de Windows*, aplicaciones de escritorio y de Store, así como la posibilidad de acceder a los archivos de Windows desde Linux. Esto te permite usar las aplicaciones de Windows y las herramientas de línea de comandos de Linux en el mismo conjunto de archivos, si así lo deseas.
![comparativa](/img/image-1.png)

Anque parezca que WSL es mejor, creo que depende de para que lo quieras utilizar:

1. Si quieres emular un hardware completo es mejor otro hipervisor como VirtualBox.

2. Si quieres tener una distribución que no sea linux, WSL no es una buena opción.

3. Si quieres tener una interfaz gráfica, WSL no es una buena opción.

4. Si quieres ejectuar software que puede ser malicioso, es mejor el aislamiento de VirtualBox.
