# Manual de usuario

## 1. Inicio de sesión

Al abrir la aplicación aparece la pantalla de acceso. Ingresa el usuario y la
contraseña proporcionados por tu administrador.

> Las credenciales iniciales se entregan por el canal de soporte. **Cámbialas en el
> primer uso** desde la administración de usuarios (rol administrador).

Roles disponibles:
- **Administrador:** acceso total, incluida la gestión de usuarios.
- **Analista:** carga y análisis de datos.
- **Visor:** solo consulta.

## 2. Cargar datos desde Excel

1. En el tablero, usa la opción de **cargar archivo Excel**.
2. Selecciona la hoja si el archivo tiene varias.
3. La aplicación detecta automáticamente las columnas requeridas. Si alguna no se
   reconoce, confírmala o corrígela en el **diálogo de mapeo de columnas**.

Columnas esperadas (entre otras): código de ovitrampa, semana epidemiológica,
fechas de instalación e inspección, ovitrampa instalada/recuperada, total de huevos
de *Ae. aegypti* y coordenadas X/Y.

## 3. Tablero e indicadores (KPIs)

Tras cargar los datos verás indicadores clave: número de ovitrampas instaladas,
recuperadas, índice de positividad y total de huevos.

## 4. Pestañas de análisis

- **Datos:** tabla con los registros y filtros (por semana, sector, etc.).
- **Gráficos:** selecciona entre varios gráficos interactivos para analizar
  tendencias temporales y comparaciones por sector.
- **Mapa:** visualiza las ovitrampas geolocalizadas con agrupamiento (clusters) y
  mapa de calor de positividad.

## 5. Guardar y recuperar datasets

Puedes guardar el conjunto de datos cargado para volver a abrirlo después desde el
**historial de datasets guardados**. Los datos se almacenan localmente en tu equipo.

## 6. Gestión de usuarios (solo administrador)

Desde la administración de usuarios puedes crear, editar o eliminar cuentas y asignar
roles. Cambia las contraseñas por defecto cuanto antes.

## 7. Dónde se guardan los datos

La aplicación guarda su información localmente en tu perfil de Windows
(`%LOCALAPPDATA%`), incluyendo la base de datos local y los datasets guardados.

## 8. Soporte

Para dudas o reportes: **mateo.bha@outlook.com**.
