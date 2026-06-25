# Mosquito Data Management System v1.0.0

Sistema de escritorio para el monitoreo de ovitrampas de *Aedes aegypti* en el
Distrito Metropolitano de Quito (DMQ). Desarrollado para el INSPI.

## 📦 Requisitos
- Windows 10 o superior (64 bits)
- ~1 GB de espacio en disco
- Permisos de administrador para instalar

## ⬇️ Instalación
1. Descarga `MosquitoDataManagementSystem_Setup_v1.0.0.exe` desde los *Assets* de esta release.
2. Verifica el hash SHA-256 (ver abajo).
3. Ejecuta el instalador y sigue el asistente.

Guía detallada: [docs/instalacion.md](docs/instalacion.md)

## 🗂️ Archivo
- **Nombre:** `MosquitoDataManagementSystem_Setup_v1.0.0.exe`

## 🔐 Hash SHA-256
```
5A855B7B8D232CBFF3FA28721D37772C11DA4859D26A4CCCEB1A1D21B64C2CFA
```
Verifícalo con:
```powershell
Get-FileHash -Algorithm SHA256 "MosquitoDataManagementSystem_Setup_v1.0.0.exe" | Format-List
```

## 📝 Notas de versión
- Primera versión pública estable.
- Carga/validación de Excel con auto-mapeo de columnas.
- Tablero con KPIs, gráficos interactivos y mapa con clusters/mapa de calor.
- Almacenamiento local de datasets y gestión de usuarios por roles.

## ⚠️ Advertencia
Descarga el instalador **únicamente** desde este repositorio oficial:
https://github.com/mateobha/Mosquito-Data-Management-System/releases
No ejecutes binarios obtenidos de otras fuentes.

## 🛟 Soporte
mateo.bha@outlook.com
