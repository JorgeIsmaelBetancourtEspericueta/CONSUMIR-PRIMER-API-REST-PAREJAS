# Proyecto API REST  

**Realizado por el equipo:**  
- **Betancourt Espericueta Jorge Ismael** - *21400655*  
- **Portugal De La Paz Yves Manuel** - *21400748*  

## Descripción  
En este proyecto, exploramos y probamos nuestras APIs desarrolladas con API REST. Utilizamos Insomnia para facilitar el consumo y prueba de las APIs. 
Además, realizamos pruebas de conexión entre un servidor y un cliente, empleando dos laptops para simular ambos roles.  

## Funcionalidades  
- **GET**: Obtener todas las tareas.  
- **GET (ID específico)**: Obtener una tarea en específico.  
- **POST**: Crear una nueva tarea enviando un JSON en el *Body*.  
- **PUT**: Actualizar una tarea enviando un nuevo título en el *Body*.  

## Conexión entre equipos  
Para conectarnos al `localhost` de otro equipo, es necesario conocer la IP del equipo servidor. En Insomnia, podemos probar la conexión con una 
petición `GET` utilizando la siguiente estructura: http://X.X.X.X:3001/apiV1/task

Donde:  
- `X.X.X.X` es la IP del **servidor**.  
- `3001` es el **puerto** en el que está corriendo la API.  
