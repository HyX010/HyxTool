- ██╗  ██╗██╗   ██╗██╗  ██╗          ████████╗ ██████╗  ██████╗ ██╗      -
- ██║  ██║╚██╗ ██╔╝╚██╗██╔╝          ╚══██╔══╝██╔═══██╗██╔═══██╗██║      -
- ███████║ ╚████╔╝  ╚███╔╝              ██║   ██║   ██║██║   ██║██║      -
- ██╔══██║  ╚██╔╝   ██╔██╗              ██║   ██║   ██║██║   ██║██║      -
- ██║  ██║   ██║   ██╔╝ ██╗             ██║   ╚██████╔╝╚██████╔╝███████╗ -
- ╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝             ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝ -

      Digital Forensics Tools - X: @Hy_X01 | Discord: .Hy_X1

![Version](https://img.shields.io/badge/version-1.0-magenta)
![.NET](https://img.shields.io/badge/.NET-9.0-purple)
![License](https://img.shields.io/badge/license-MIT-pink)

> **Hyx Tool** es una herramienta CLI interactiva que automatiza el análisis forense digital utilizando las herramientas de **Eric Zimmerman**. Diseñada para ser rápida, intuitiva y con una estética única.

---

[-] Características
-  **Descarga automática** de herramientas forenses
-  **Detección de archivos existentes**
-  **Herramientas integradas**:
  - MFT Parser (`MFTECmd`)
  - SRUM Parser (`SrumECmd`)
  - Windows Timeline (`WxTCmd`)
  - AppCompatCache Parser
  - Timeline Explorer (visualizador de CSVs)

- 🔐 **Verificación de permisos de administrador**

---

- 📋 Requisitos

- Windows 10/11 (64 bits)
- [.NET 9 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/9.0) (necesario para Timeline Explorer)

---

[-] Instalación

### Opción 1: Descargar ejecutable
1. Ve a [Releases](https://github.com/tuusuario/HyxTool/releases)
2. Descargá `HyxTool.exe`
3. Ejecutalo **como administrador**


[Tool]
Menú principal:

- ═══════════════════════════════════════
-  1 - MFTParser
-  2 - SRUMParser
-  3 - WxTCmd (Windows Timeline)
-  4 - AppCompatCacheParser
-  5 - Abrir Timeline Explorer
-  6 - Salir
- ═══════════════════════════════════════


⚠️ Nota importante
Hyx Tool es un wrapper que automatiza el uso de las herramientas de Eric Zimmerman. Todo el crédito por las herramientas forenses va para él.

Ejecutar siempre como administrador para acceder a C:\$MFT y otros archivos del sistema.
