# modelacion_actividad_integradora
**Andres Eduardo Nowak de Anda A01683430**

## Requirements
### Server:
- websockets
- agentpy

Para poder importar websockets y agentpy se instala de la manera
```pip3 install websockets agentpy```

### Unity:
- [NativeWebSocket] (https://github.com/endel/NativeWebSocke)
- [NavMeshComponents] (https://github.com/Unity-Technologies/NavMeshComponents)

para instalar nativeWebsocket siga las instrucciones en su github y para poder instalara navMeshComponents solo necesita clonar el repositorio de github, eliminar la carpeta NavMeshComponents que obtiene al agregar el unity package y agregar el directorio que clono

## Run program
meterse a la carpeta server y ahi correr
```python server.py```
este es el que crea el websocket para que el unity pueda correr

y para el unity es primero haber instalado todo y despues meterse a la escena llamada simulation y correr el programa.