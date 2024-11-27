# k8s-postgres

En este video, te guío paso a paso para configurar Postgres con persistencia en Kubernetes utilizando Kind en macOS. Comenzamos preparando el entorno con la instalación y configuración de Kind, y luego avanzamos a implementar una solución completa para Postgres.

Exploramos a detalle todos los recursos necesarios, como:

- Namespace: para organizar los recursos.
- PersistentVolume y PersistentVolumeClaim: para asegurar la persistencia de datos.
- ConfigMap y Secret: para gestionar configuraciones y credenciales de forma segura.
- StatefulSet: para garantizar la estabilidad de la base de datos.
- Services: para exponer Postgres dentro del clúster.
- Y cómo exportar un puerto en Kind para que Postgres sea accesible desde tu host.
