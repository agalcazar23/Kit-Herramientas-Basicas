<div align="center">

# 🛠️ KIT DE HERRAMIENTAS | SECCIÓN 3
# 🔑 Hashcat: El recuperador de contraseñas más rápido del mundo

[![GitHub Release](https://img.shields.io/github/v/release/hashcat/hashcat?style=flat-square&color=6366f1)](https://github.com/hashcat/hashcat)
[![Platform](https://img.shields.io/badge/Plataformas-Windows_|_Linux_|_macOS-blue?style=flat-square)](https://hashcat.net)
[![License](https://img.shields.io/badge/Licencia-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)

---

**Hashcat** es una herramienta de recuperación de contraseñas basada en código abierto, líder en el sector, que permite descifrar hashes mediante más de 300 algoritmos diferentes utilizando la potencia de la CPU y la GPU.

[🌐 Sitio Web Oficial](https://hashcat.net) • [📂 Código Fuente](https://github.com/hashcat/hashcat) • [📖 Documentación](https://hashcat.net/wiki/)

</div>

### 💎 ¿Por qué Hashcat es la herramienta definitiva?

> [!IMPORTANT]
> **Rendimiento Extremo:** Hashcat fue el primero en implementar un motor basado en GPGPU, lo que permite realizar miles de millones de intentos por segundo, superando por mucho a cualquier software basado solo en procesador.

| 🚀 VELOCIDAD | 🧩 VERSATILIDAD | ⚖️ ESTÁNDAR |
| :--- | :--- | :--- |
| Optimizado para NVIDIA, AMD e Intel. | Soporta desde MD5 hasta WPA/WPA2 y bases de datos. | Herramienta base para auditores de seguridad y forenses. |

---

### 🛠️ Capacidades Técnicas Resumidas

| Función | Descripción Técnica |
| :--- | :--- |
| **Multi-Dispositivo** | Capacidad de utilizar múltiples GPUs, CPUs y otros aceleradores en el mismo sistema de forma combinada. |
| **Ataques de Máscara** | Permite definir patrones específicos (ej: "Empieza por A y termina en 2024") para reducir el tiempo de búsqueda. |
| **Brain Mode** | Sistema de red para evitar la duplicación de intentos en ataques de diccionario masivos. |
| **Soporte de Reglas** | Lenguaje propio para aplicar transformaciones a diccionarios (leetspeak, sufijos, etc.) en tiempo real. |

---

### 🚀 Guía de Despliegue Rápido

1. **Identificación:** Obtén el hash de la contraseña que necesitas recuperar (puedes usar herramientas como `hashid` para identificar el tipo).
2. **Preparación:** Coloca tu diccionario de palabras (`wordlist`) o define tu máscara de ataque.
3. **Ejecución:** Lanza el comando base (Ej: `hashcat -m 0 hash.txt diccionario.txt`).
4. **Finalización:** El sistema utilizará toda la potencia disponible para encontrar la coincidencia y mostrarla en pantalla o en el archivo `.potfile`.

---

### 📥 Recursos de Descarga Directa

| Sistema Operativo | Enlace de Instalación |
| :--- | :--- |
| **🪟 Windows** | [Descargar Binarios (.7z)](https://hashcat.net/hashcat/) |
| **🐧 Linux** | [Repositorios (apt/pacman) o Código Fuente](https://github.com/hashcat/hashcat) |
| **🍎 macOS** | [Instalación vía Homebrew (`brew install hashcat`)](https://formulae.brew.sh/formula/hashcat) |

---

> [!TIP]
> **Bonus Ético:** Recuerda que esta herramienta debe ser utilizada exclusivamente para auditorías de seguridad autorizadas o recuperación de claves propias. La potencia de Hashcat es inmensa, úsala con responsabilidad.

---
<p align="right">Daniel González Hidalgo</p>
