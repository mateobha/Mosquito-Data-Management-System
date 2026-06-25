# Changelog

Todas las versiones notables de **Mosquito Data Management System** se documentan aquí.
El formato sigue [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/)
y este proyecto adhiere a [Versionado Semántico](https://semver.org/lang/es/).

## [1.0.1] - 2026-06-25

### Seguridad y autenticación
Se implementa cambio obligatorio de contraseña en el primer ingreso.
El usuario admin se crea con esta validación activa.
Se eliminan los usuarios por defecto usuario y viewer.
El admin ahora gestiona la creación de usuarios desde el panel.

### Control de permisos
Se restringen acciones para el rol viewer, incluyendo ocultar el botón Guardar.
Se ajustan permisos en datasets guardados y visualización de datos.

### Gráficos y mapa
Se agregan títulos descriptivos a gráficos y mapa.
Se mejora el layout del mapa.
Se incorpora control para evitar múltiples instancias de la aplicación.
Se añaden nuevos tests de flujo.

### Compilación e instalador
Se configura el script de Inno Setup para generar el instalador de Windows.
Se actualiza el .gitignore para excluir archivos de compilación.
Se realizan limpiezas menores en login_window.py y main.py.

[1.0.1]: https://github.com/mateobha/Mosquito-Data-Management-System/releases/tag/v1.0.1

## [1.0.0] - 2026-06-24

- Primera versión pública estable.
- Carga y validación de archivos Excel de ovitrampas con auto-mapeo de columnas.
- Tablero con KPIs: instaladas, recuperadas, positividad y total de huevos de _Ae. aegypti_.
- Gráficos interactivos de análisis temporal y por sector.
- Mapa interactivo con clusters y mapa de calor.
- Almacenamiento local de datasets y gestión de usuarios por roles.
- Instalador oficial para Windows 10+ (64 bits).

[1.0.0]: https://github.com/mateobha/Mosquito-Data-Management-System/releases/tag/v1.0.0
