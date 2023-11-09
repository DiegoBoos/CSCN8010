## Configuración

1. Eres bienvenido a `hacer un fork` de este repositorio para obtener tu propia copia en tu cuenta personal. `Clona` este fork en tu computadora portátil.

2. Se recomienda crear una nueva carpeta que contendrá los cuadernos de clase con tus propias ediciones. De esta manera, tendrás los cuadernos originales en la carpeta `class_notebooks` y tus cuadernos modificados en tu propia carpeta. Esto es especialmente útil ya que los archivos son cuadernos Jupyter, cuya metainformación y salidas de celdas pueden hacer que `git diff` para sincronizar cambios sea un poco complicado a veces.

3. Crea un entorno virtual, ejecuta los siguientes comandos desde la carpeta raíz:
    1. Inicializa un entorno virtual: `python -m venv venv/CSCN8010_classic_ml`
    2. Activa el entorno virtual:
        1. Linux o Mac: `source ./venv/CSCN8010_classic_ml/bin/activate`
        2. Windows Powershell: `.\venv\CSCN8010_classic_ml\Scripts\Activate.ps1`
    3. Instala los paquetes de Python: `pip install -r requirements.txt`
    4. Instala ipykernel: `python -m ipykernel install --user --name=CSCN8010_classic_ml --display-name=CSCN8010_classic_ml`

4. Configuración de vscode para trabajar con Cuadernos y Entornos Virtuales:
    1. vscode necesita reiniciarse después de configurar los entornos virtuales por primera vez. De lo contrario, los entornos no serán visibles en vscode.
    2. Para ejecutar cuadernos de Python en vscode, primero debes instalar la extensión Python de Microsoft (se hace a través del menú Extensiones en la barra lateral izquierda).
    3. Luego, abre un cuaderno y selecciona el kernel correcto (ya sea python_cpu o tensorflow_cpu, dependiendo de lo que el cuaderno esté utilizando). La selección del kernel se realiza en la parte superior derecha en vscode.
    4. Ten en cuenta que si ves líneas naranjas onduladas debajo de los nombres de los paquetes en la declaración de importación, cambia el intérprete al del entorno virtual escribiendo en el comando de paleta Python: Seleccionar Intérprete ([stackoverflow](https://stackoverflow.com/a/72721797/10006823)).

5. Prueba tu entorno ejecutando el archivo de prueba en la carpeta `class_notebooks`.
