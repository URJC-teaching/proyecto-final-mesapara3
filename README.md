# Proyecto final

## Objetivo

Desarrollar una aplicación robótica que:

- Navegue de forma autónoma por al menos dos waypoints.
- Interactúe con el humano mediante el paquete HRI (Human-Robot Interaction).
- Utilice YOLO para la detección de objetos o personas.

## Configuración del sistema HRI

Consulta las instrucciones completas en el [repositorio de simple_hri](https://github.com/rodperex/simple_hri#launch-local-services).

Se recomienda usar el **modelo local** para evitar el consumo de tokens externos, para ello:

Lanzar los servicios locales:

```bash
ros2 launch simple_hri local_simple_hri.launch.py
```

Probar los servicios:

```bash
ros2 run simple_hri test_services
```
