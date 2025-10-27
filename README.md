EDD2025: Proyecto de Gestión de Pasajeros (Actividad 3)
Este repositorio contiene la solución para la Actividad 3 del curso de Estructuras de Datos, que consiste en la simulación de un sistema de gestión de pasajeros para una aerolínea utilizando Listas Enlazadas y Memoria Dinámica en lenguaje C.

⚙️ Características Técnicas
Lenguaje: C.

Estructura de Datos: Lista Enlazada Simple.

Gestión de Memoria: Uso de malloc() para la asignación dinámica de cada pasajero y free() para liberar toda la memoria nodo por nodo al finalizar el programa (evitando fugas).

Ubicación del Código: El archivo fuente principal es gestion_pasajeros.c, ubicado en la carpeta obligatoria Actividad3/.

💼 Lógica de Negocio Implementada
El programa simula las siguientes reglas de la aerolínea:

Capacidad y Overbooking: El sistema calcula el límite de tiquetes vendibles permitiendo un 10% adicional a la capacidad máxima del avión (concepto de overbooking).

Prioridad (FIFO): Los pasajeros se registran y abordan bajo la regla: "El primero en ser registrado es el primero en abordar."

Abordaje: La simulación respeta la capacidad real del avión, dejando fuera a los pasajeros que excedan dicho límite, aunque hayan comprado tiquete.
