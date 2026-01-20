# -Python-Insider-Analytics-by-Gaturro2211

# 🐍 Python Insider Analytics | by Gaturro2211

> **Análisis de datos basado en el blog oficial de desarrolladores de Python.**
> Un proyecto de extracción estática para el monitoreo de actualizaciones tecnológicas.

---

## 📌 Tema del Proyecto: Ciclo de Vida de Python
Este repositorio analiza las publicaciones de **Python Insider**. El objetivo es identificar las tendencias de desarrollo del lenguaje. 

### ¿Qué descubrimos?
Tras procesar más de 20 registros, observamos que el tema predominante es el lanzamiento de versiones **Alpha** (específicamente la 3.15) y la disponibilidad inmediata de parches de seguridad.

---

## 📂 Laboratorio de Datos
Los archivos generados se encuentran en la carpeta `/data`:

1.  **[raw.csv](./data/posts_python_blog.csv)**: Datos originales (título y URL).
2.  **[clean.csv](./data/posts_python_blog_procesado.csv)**: Datos con métricas de longitud de caracteres.
3.  **[summary.csv](./data/top_palabras_titulos.csv)**: Conteo de las palabras más frecuentes como "Alpha" y "Available".

---

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.12
* **Librerías:** BeautifulSoup4 (Scrapeo Estático) & Pandas
* **Despliegue:** GitHub Pages
