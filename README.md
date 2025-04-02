# StegAnalyzer Pro

![StegAnalyzer Pro](https://github.com/ccyl13/StegAnalyzer/blob/main/Steg.png?raw=true) <!-- Reemplaza con la ruta a tu logo si lo tienes, por ejemplo: ![StegAnalyzer Pro Logo](logo.png) -->
![StegAnalyzer Pro](https://github.com/ccyl13/StegAnalyzer/blob/main/StegAnalyzer.png?raw=true)


**Versión:** 1.0.7  
**Fecha de lanzamiento:** 30 de marzo de 2025  
**Desarrollado por:** Thomas O'Neill Álvarez  
**Licencia:** MIT  
**Repositorio:** [GitHub](https://github.com/ccyl13/StegAnalyzer)  
**Estado del proyecto:** Activo 🚀

---

## 📖 Tabla de Contenidos

- [Descripción](#descripción)
- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
  - [Paso 1: Clonar el Repositorio](#paso-1-clonar-el-repositorio)
  - [Paso 2: Instalar Dependencias](#paso-2-instalar-dependencias)
  - [Paso 3: Ejecutar la Aplicación](#paso-3-ejecutar-la-aplicación)
- [Uso](#uso)
- [Personalización](#personalización)
- [Estructura del Código](#estructura-del-código)
- [Limitaciones](#limitaciones)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)
- [Historial de Versiones](#historial-de-versiones)
- [Problemas y Soporte](#problemas-y-soporte)
- [Instrucciones para Gestionar este README](#instrucciones-para-gestionar-este-readme)

---

## 📝 Descripción

**StegAnalyzer Pro** es una herramienta avanzada diseñada para detectar esteganografía y caracteres ocultos en archivos digitales. Soporta múltiples formatos, incluyendo imágenes (PNG, JPG, BMP), archivos de texto (TXT) y documentos PDF. Construida con Python, utiliza una interfaz gráfica moderna basada en PyQt5, lo que la hace intuitiva y visualmente atractiva. La herramienta es ideal para profesionales de ciberseguridad, investigadores y entusiastas que deseen analizar archivos en busca de datos ocultos.

### ¿Qué hace StegAnalyzer Pro?
- **Detección de esteganografía:** Identifica mensajes ocultos en imágenes usando la técnica LSB (Least Significant Bit) con la biblioteca `stegano`.
- **Detección de caracteres ocultos:** Busca caracteres no imprimibles (como `\x00`) en archivos de texto y PDFs.
- **Generación de reportes:** Crea reportes HTML detallados con los resultados del análisis, incluyendo logs y tablas.
- **Interfaz gráfica:** Ofrece una experiencia de usuario fluida con gradientes, animaciones y un diseño profesional.

### ¿Por qué usar StegAnalyzer Pro?
- **Fácil de usar:** Interfaz gráfica intuitiva con botones claros y áreas de resultados en tiempo real.
- **Personalizable:** Colores, fuentes y estilos ajustables para adaptarse a tus preferencias.
- **Open Source:** Licencia MIT, lo que permite a la comunidad contribuir y usar el proyecto libremente.

---

## ✨ Características

- **Análisis de esteganografía:** Detecta mensajes ocultos en imágenes (PNG, JPG, BMP) usando LSB.
- **Detección de caracteres ocultos:** Identifica caracteres no imprimibles en archivos TXT y PDF.
- **Interfaz gráfica moderna:** Construida con PyQt5, con gradientes, bordes redondeados y un diseño oscuro elegante.
- **Reportes HTML:** Genera reportes detallados con tablas, logs y un diseño responsive.
- **Logs en tiempo real:** Registra cada acción con marcas de tiempo en un área dedicada.
- **Soporte para múltiples formatos:** Compatible con imágenes, texto y PDFs.
- **Progreso visual:** Barra de progreso animada durante el análisis.
- **Servidor local:** Sirve reportes HTML a través de un servidor local (puerto 8000) con opción de detenerlo.
- **Lanzador de escritorio:** Opción para crear un lanzador `.desktop` en Linux para ejecutarlo sin terminal.

---



---

## 🛠️ Requisitos

### Dependencias de Software
- **Python:** Versión 3.6 o superior.
- **Paquetes de Python:**
  - `PyQt5`: Para la interfaz gráfica.
  - `pillow`: Para el manejo de imágenes.
  - `stegano`: Para el análisis de esteganografía.
  - `PyPDF2`: Para el manejo de PDFs.
  - `lxml`: Opcional, para compatibilidad con algunas bibliotecas.
- **Sistema operativo:** Probado en Kali Linux, pero compatible con otros sistemas Linux, Windows y macOS con ajustes.
- **Fuentes:** `fonts-lato` (para el estilo de la interfaz).

### Requisitos de Hardware
- **Mínimo:** 2 GB de RAM, procesador de 1 GHz.
- **Recomendado:** 4 GB de RAM, procesador de 2 GHz o superior.

### Herramientas Adicionales
- `git`: Para clonar el repositorio.
- Navegador web: Para visualizar los reportes HTML.

---

## 📦 Instalación

### Paso 1: Clonar el Repositorio
1. Asegúrate de tener `git` instalado:
   ```bash
   sudo apt update
   sudo apt install git
   git clone https://github.com/ccyl13/StegAnalyzer.git
   
### Paso 2: Instalar Dependencias
1. Instala las dependencias de Python usando `pip`:
   ```bash
   sudo pip3 install PyQt5 pillow stegano PyPDF2 lxml --break-system-packages
2. Instala la fuente Lato para la interfaz:
   ```bash
   sudo apt install fonts-lato
3. Directorio de la herramienta:
   ```bash
   cd StegAnalyzer-Pro
4. Dale permisos de ejecución:
   ```bash
   sudo chmod +x StegAnalyzer.py

### Paso 3: Ejecuta la herramienta:
 ```bash
python3 StegAnalyzer.py


   
