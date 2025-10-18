### Tarea Arquitectura por eventos con REDIS
## Autor: Juan Felipe Ochoa

## ¿Qué es Redis?
Redis (REmote DIctionary Server) es un sistema de almacenamiento en memoria (in-memory data store) de clave–valor, muy rápido y de código abierto.

## ¿Para que sirve?
Redis almacena los datos en memoria RAM, lo que le da una velocidad altísima y una versatilidad como pocos otros. Se usa para caché de datos,
sistemas de mensajería, cola de tareas, contadores y rankings, gestión de sesiones, entre muchas otras utlidades.

## Para esta arquitectura
Se crean Listeners, un Producer y sus respectivas conexiones que aseguran la implementación de REDIS como un message broker que implementa el servicio de publish/subscribe.
