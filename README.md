# 🛒 Automated Amazon Price Tracker

Este proyecto es una herramienta de **Ingeniería de Datos** que automatiza la extracción, limpieza y monitoreo de precios de productos en Amazon. Permite generar un histórico de datos para análisis de tendencias y configurar alertas automáticas de caída de precios.

## 📋 Escenario de Uso
En el análisis de retail, el monitoreo de la competencia y la fluctuación de precios es vital. Este script resuelve el problema de la recolección manual de datos, creando un dataset estructurado de forma diaria y automática.



## 🛠️ Stack Tecnológico
* **Python 3.x**
* **BeautifulSoup4:** Para el parseo de HTML y navegación del DOM.
* **Requests:** Para la gestión de peticiones HTTP y headers de agente de usuario.
* **Pandas:** Para la validación y lectura del dataset generado.
* **SMTP (smtplib):** Para el envío de alertas automatizadas por correo electrónico.

## ⚙️ Funcionalidades
1. **Extracción Dinámica:** Obtención de títulos y precios saltando bloqueos básicos mediante la configuración de headers.
2. **Limpieza de Datos (Data Cleaning):** Procesamiento de strings para normalizar valores numéricos.
3. **Persistencia Automatizada:** El script crea un archivo CSV y añade nuevas entradas (append) con timestamps para seguimiento temporal.
4. **Scheduler Simple:** Implementación de un bucle de tiempo para ejecución periódica (cada 24 horas).
5. **Smart Alerts:** Envío de correos electrónicos automáticos cuando el precio alcanza un objetivo (Target Price).



## 🚀 Cómo utilizarlo
1. Clona el repositorio.
2. Instala las dependencias: `pip install beautifulsoup4 requests pandas`.
3. Ingresa la URL de Amazon que deseas monitorear en la variable `URL`.
4. Ejecuta el script para comenzar la recolección de datos.

## 📈 Conclusiones
Este proyecto demuestra habilidades en **recolección de datos no estructurados**, automatización de tareas y manejo de protocolos de comunicación (SMTP). Es la base ideal para un sistema de análisis de mercado más complejo o un bot de arbitraje.

---
**Contacto:** 
-  [Linkdin](www.linkedin.com/in/hassiel-garcía-719756260)
-  [Correo](angelhassielgarciabaca@gmail.com)
