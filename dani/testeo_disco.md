<div align="center">

# 🛠️ KIT DE HERRAMIENTAS | SECCIÓN 5
# 🔑 TestDisk & PhotoRec: La suite esencial de recuperación y diagnóstico

[![GitHub Release](https://img.shields.io/github/v/release/cgsecurity/testdisk?style=flat-square&color=6366f1)](https://github.com/cgsecurity/testdisk)
[![Platform](https://img.shields.io/badge/Plataformas-Windows_|_Linux_|_macOS-blue?style=flat-square)](https://www.cgsecurity.org)
[![License](https://img.shields.io/badge/Licencia-GPLv2-green?style=flat-square)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

---

**TestDisk & PhotoRec** es una potente suite de herramientas de código abierto, líder en el sector, esencial para el diagnóstico de discos, la recuperación de particiones perdidas, la reparación de sectores de arranque y la extracción de datos en crudo.

[🌐 Sitio Web Oficial](https://www.cgsecurity.org/wiki/TestDisk_ES) • [📂 Código Fuente](https://github.com/cgsecurity/testdisk) • [📖 Documentación](https://www.cgsecurity.org/wiki/TestDisk_Paso_A_Paso)

</div>

### 💎 ¿Por qué TestDisk & PhotoRec es la herramienta definitiva?

> [!IMPORTANT]
> **Prevención y Recuperación de Desastres:** TestDisk es fundamental para reparar tablas de particiones dañadas a bajo nivel, permitiendo que el sistema vuelva a arrancar. PhotoRec ignora el sistema de archivos dañado para extraer información directamente de los bloques en crudo (RAW).

| ⚡ RECUPERACIÓN | 🛠️ REPARACIÓN | 🛡️ FORENSE |
| :--- | :--- | :--- |
| Recupera particiones NTFS, FAT, ext y más. | Repara sectores de arranque dañados. | Herramienta potente para análisis de datos físicos. |

---

### 🛠️ Capacidades Técnicas Resumidas

| Función | Descripción Técnica |
| :--- | :--- |
| **Multi-Plataforma** | Funciona nativamente en la mayoría de sistemas operativos como Windows, Linux, macOS y DOS. |
| **Soporte de Sistemas de Archivos** | Cubre la inmensa mayoría de formatos (NTFS, exFAT, ext2/3/4, HFS+, Btrfs, etc.). |
| **Recuperación en Crudo** | PhotoRec soporta la extracción de cientos de firmas de archivos ignorando la tabla de particiones. |
| **Análisis Lógico** | Reconstruye sectores de arranque a partir de copias de seguridad o datos lógicos en la unidad. |

---

### 🚀 Guía de Despliegue Rápido

1. **Ejecución:** Lanza `testdisk` o `photorec` desde la terminal con privilegios de administrador.
2. **Selección de Disco:** Elige la unidad física que deseas analizar (ignora las particiones lógicas si el disco está dañado).
3. **Tipo de Partición:** Selecciona el tipo de tabla de particiones (normalmente `Intel` para MBR o `EFI GPT` para modernos).
4. **Análisis:** Inicia la búsqueda profunda de particiones perdidas o el escaneo de firmas de archivos.
5. **Guardado:** Escribe la nueva tabla de particiones en la unidad (TestDisk) o extrae los archivos rescatados (PhotoRec).

---

### 📥 Recursos de Descarga Directa

| Sistema Operativo | Enlace de Instalación |
| :--- | :--- |
| **🪟 Windows** | [Descargar Binarios Oficiales (.zip)](https://www.cgsecurity.org/wiki/TestDisk_Download) |
| **🐧 Linux** | [Repositorios (apt/pacman) o Descarga Directa](https://www.cgsecurity.org/wiki/TestDisk_Download) |
| **🍎 macOS** | [Instalación vía Homebrew (`brew install testdisk`)](https://formulae.brew.sh/formula/testdisk) |

---

> [!TIP]
> **Recordatorio Crítico:** Cuando recuperes archivos con PhotoRec, asegúrate de guardarlos en un disco físico **DIFERENTE** al que estás analizando. De lo contrario, sobrescribirás los bloques de datos que intentas salvar.

---

<p align="right">Daniel González Hidalgo</p>

Daniel Romero Marin
