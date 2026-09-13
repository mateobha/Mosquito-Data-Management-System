# Guía de instalación

## Requisitos del sistema

- **Sistema operativo:** Windows 10 o superior (64 bits).
- **Espacio en disco:** ~1 GB libre.
- **Permisos:** de administrador (para instalar en *Archivos de programa*).

## Descarga

1. Ve a la página oficial de descargas:
   **https://github.com/mateobha/Mosquito-Data-Management-System/releases/latest**
2. Descarga el archivo `MosquitoDataManagementSystem_Setup_v1.0.0.exe`.

> ⚠️ Descarga el instalador **solo** desde este repositorio oficial.

## Verificar la integridad

Antes de ejecutar el instalador, confirma su hash SHA-256 en PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 "$HOME\Downloads\MosquitoDataManagementSystem_Setup_v1.0.0.exe" | Format-List
```

El valor debe coincidir **exactamente** con el `SHA-256` publicado en la release.
Si no coincide, **no ejecutes el archivo** y contacta a soporte.

## Instalación

1. Haz doble clic en `MosquitoDataManagementSystem_Setup_v1.0.0.exe`.
2. Si Windows SmartScreen muestra un aviso (por ser un editor sin firma EV),
   selecciona **Más información → Ejecutar de todas formas**.
3. Acepta el control de cuentas de usuario (UAC).
4. Sigue el asistente: acepta la licencia, elige la carpeta y marca si deseas un
   acceso directo en el escritorio.
5. Al finalizar, inicia la aplicación.

## Desinstalación

Ve a **Configuración de Windows → Aplicaciones → Aplicaciones instaladas**, busca
*Mosquito Data Management System* y selecciona **Desinstalar**.

## Solución de problemas

- **La app no abre / pantalla en blanco en mapas o gráficos:** la app ya fuerza un
  modo de compatibilidad de GPU; reinicia el equipo e inténtalo de nuevo.
- **Antivirus bloquea el instalador:** añade una excepción tras verificar el hash.
- **Otros problemas:** escribe a mateo.bha@outlook.com.
