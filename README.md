# Software de simulación de Radar OTH (Sobre-horizonte)

Entrega del proyecto PIDDEF 03-2020.

En este repositorio se encuentran:

   - Core del Simulador de Radar
   - Backend del Simulador de Radar


## Instalación

Las instrucciones completas de instalación estan disponibles en [Instrucciones de Instalación](https://allanes.github.io/piddef-03-2020-documentacion).


## Iniciar los servicios

En **Windows**, ejecutar el archivo `iniciar_servicios.bat`.

En **Linux**, ejecutar el archivo `linux_iniciar_servicios.sh`.

### Manualmente

Se deben iniciar dos terminales en la carpeta raíz "app-simulador-radar", una para el servidor de Backend y otra para el de Frontend.

- Terminal 1:

   ```
   cd simulador_core
   source .venv/bin/activate
   python3 src/simulador_core/backend_api.py
   ```

- Terminal 2:

   ```
   cd frontend-radar
   npm run start
   ```

Para abrir la _página de Inicio_, usar [este link](http://localhost:3000).


## Links útiles

- Página principal: <http://localhost:3000/>

- Documentación: <http://localhost:5000/documentacion>

- Correr simulación interactiva desde el Backend: <http://localhost:5000/docs>

- Correr simulación interactiva desde el Jupyter Notebook: [Archivo de Jupyter Notebook](src/simulador_core/guia_de_uso_core.ipynb>`_  (funciona sólo desde un IDE como Visual Studio Code).

- Correr simulación de ejemplo llamando al Core::
   
      python src\simulador_core\main.py


