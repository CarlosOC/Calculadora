# Calculadora
 
<p>
Este proyecto es una calculadora gráfica básica desarrollada con <strong>Qt</strong> en C++. Soporta las operaciones aritméticas básicas: suma, resta, multiplicación, división, y cambio de signo (<code>+/-</code>). Además, el proyecto utiliza una hoja de estilos personalizada para mejorar la apariencia de la interfaz gráfica.
<img src="https://github.com/CarlosOC/Calculadora/blob/main/Imagenes/Calculadora.png" alt="Calculadora" style="float:right; width:300px; margin-left:10px;">
</p>


## Características

- **Operaciones soportadas**:
  - Suma (`+`)
  - Resta (`-`)
  - Multiplicación (`*`)
  - División (`/`)
  - Cambio de signo (`+/-`)
- **Interfaz gráfica** desarrollada con `Qt Widgets` para una experiencia de usuario interactiva.
- **Validación de división entre 0**, mostrando un mensaje de error.

## Capturas de pantalla

_Incluye aquí capturas de pantalla del proyecto si es posible._

## Instalación y ejecución

Para ejecutar este proyecto en tu máquina local, sigue los siguientes pasos:

### Prerrequisitos

- **Qt**: Debes tener instalado el framework de Qt para compilar y ejecutar el proyecto.
- **CMake** o **qmake** para la configuración del proyecto.
- **Compilador C++** compatible (como `g++` o `clang++`).

### Clonar el repositorio

Primero, clona este repositorio:

```bash
git clone https://github.com/CarlosOC/Calculadora.git
cd calculadora-qt 
```

### Compilar el proyecto
Para compilar, abre Qt Creator o utiliza qmake o cmake desde la terminal. Asegúrate de que Qt esté correctamente configurado en tu entorno.

Usando Qt Creator:

Abre calculadora-qt.pro en Qt Creator.
Compila y ejecuta el proyecto desde la interfaz de Qt Creator.
Usando la terminal:

Genera los archivos de compilación:
```bash
qmake calculadora-qt.pro
make
```
### Ejecuta la calculadora:
./calculadora

### Archivos importantes
widget.h: Archivo de cabecera que define la clase principal Widget.
widget.cpp: Implementación de la lógica de la calculadora.
main.cpp: Punto de entrada de la aplicación.
stylesheet_03.css: Archivo de hoja de estilos personalizado para modificar la apariencia de la calculadora.

### Uso
Al ejecutar el programa, verás una interfaz gráfica con los siguientes botones:

### Números del 0 al 9.
Operaciones de suma (+), resta (-), multiplicación (*), y división (/).
Botón para cambiar el signo (+/-).
Botón = para obtener el resultado de la operación actual.
Botón C para limpiar la pantalla y reiniciar la calculadora.

### Estructura del proyecto
```
calculadora/
├── src/                    
│   ├── main.cpp            # Punto de entrada del programa
│   ├── widget.cpp          # Implementación de la calculadora
│   ├── widget.h            # Definición de la clase de la calculadora
│   ├── widget.ui           # Interfaz gráfica en formato XML
│   └── source.qrc          # Archivo de recursos del proyecto
│
├── resources/              
│   └── stylesheet_03.css   # Hoja de estilos personalizada (CSS)
│
└── QTCalculadora.pro      # Archivo del proyecto Qt
```
### Contribuciones
Si deseas contribuir al proyecto, no dudes en realizar un fork y enviar tus pull requests. Las sugerencias y mejoras siempre son bienvenidas.
Realiza un fork del repositorio.
Crea una nueva rama con tus cambios.
Realiza un pull request.

### Licencia
Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo LICENSE.

## Contacto

Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto conmigo:

- Correo electrónico: carlosoviedolr@gmail.com
- Linkedin: [https://www.linkedin.com/in/carlosnicolasoviedocodigoni/]

¡Espero que disfrutes trabajando en estos ejercicios tanto como yo disfruto enseñándolos!

Happy coding! 🚀
