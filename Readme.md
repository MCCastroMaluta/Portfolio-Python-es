# Mi Proyecto
# 🔍 Análisis de Presencia Digital de Comercios 
## *Del problema local a la investigación regional*

![Tandil](https://github.com/MCCastroMaluta/Portfolio-Python-esp/blob/main/images/Portada.png)

## 🛠️ **Stack Tecnológico**

### 🔧 **Herramientas y Proceso**
- 🐍 **Python** - Análisis de datos
- 📊 **Pandas** - Manipulación de datasets  
- 📈 **Matplotlib/Seaborn** - Visualizaciones
- 🌐 **Apify API** - Web scraping de Google Maps
- 📓 **Jupyter Notebook** - Desarrollo y presentación

**Proceso:** Extracción → Limpieza → Exploración → Visualización → Conclusiones

## 🎯 **La Historia Detrás del Análisis**

### 🛠️ El Problema Inicial
> **350 km de distancia** para un repuesto de bordeadora STIHL FSE60

🏪 **Un día recorriendo Tandil...**
- ❌ Búsquedas online sin éxito
- 🚶‍♂️ Recorrido físico por la ciudad  
- 💡 **¡Eureka!** Un comercio conocía dónde conseguirlo
- 🤔 **La pregunta:** *¿Cuántos comercios tienen información completa online?*

---

## 🔬 **Metodología de Investigación**

### 🌐 **Fuente de Datos: Google Maps via API Apify**
```
🎯 Objetivo: Analizar la presencia digital de comercios locales
📍 Alcance: 5 ciudades del centro de Buenos Aires
👥 Rango poblacional: 16,000 - 160,000 habitantes
```

### 🏙️ **Ciudades Analizadas**

| Ciudad         | Habitantes | Región     | Clasificación |
|----------------|------------|------------|---------------|
| **Tandil**     | 150,162    | Centro BA  | Ciudad grande 🏙️ |
| **Olavarría**  | 125,751    | Centro BA  | Ciudad grande 🏙️ |
| **Azul**       | 75,905     | Centro BA  | Ciudad mediana 🏘️ |
| **Benito Juárez** | 22,292  | Centro BA  | Ciudad pequeña 🏡 |
| **Rauch**      | 16,635     | Centro BA  | Ciudad pequeña 🏡 |

**Rango poblacional total:** 16,635 - 150,162 habitantes

---

## 📊 **Variables y Métricas Analizadas**

### 🎯 **Métricas Clave**

| Métrica | Descripción | Objetivo |
|---------|-------------|----------|
| 📱 **Presencia en RRSS** | % comercios con Facebook/Instagram | Evaluar digitalización social |
| 🌐 **Sitio Web** | % comercios con página web registrada | Medir presencia web oficial |
| 📍 **Datos Completos** | % perfiles con información completa | Analizar completitud en Google Maps |
| 📞 **Información de Contacto** | Teléfonos y direcciones disponibles | Evaluar accesibilidad |
| ⭐ **Reviews y Ratings** | Cantidad y calificación promedio | Medir actividad en la plataforma |

### 📋 **Variables de Análisis**
- ✅ **Completitud de datos** en Google Maps
- 🌐 **Presencia web** (sitios oficiales)
- 📱 **Redes sociales** (Facebook, Instagram, otras)
- 🏪 **Distribución por ciudad**
- 📈 **Patrones regionales**

---

## 🎯 **Objetivos Específicos del Análisis**

### 🔍 **Preguntas de Investigación**

1. **📊 Presencia Digital por Ciudad**
   - ¿Qué porcentaje de comercios tiene presencia digital por ciudad?
   - ¿Hay diferencias según el tamaño poblacional?

2. **🏪 Digitalización por Categoría**
   - ¿Qué categorías comerciales tienen mayor digitalización?
   - ¿Cuáles son las más rezagadas?

3. **⭐ Engagement Digital**
   - ¿Los negocios con sitio web tienen más reseñas?
   - ¿Existe correlación entre presencia digital y rating?

4. **📈 Calidad del Servicio**
   - ¿Cuáles son los puntajes promedio por ciudad?
   - ¿La digitalización impacta en la percepción de calidad?

### 💡 **Objetivos de Impacto**
- 🔍 **Diagnóstico** de la situación actual de digitalización comercial
- 💡  **Identificación** de oportunidades de mejora por sector
- 📈 **Cuantificación** del impacto de la presencia digital
- 🎯 **Recomendaciones** estratégicas para comerciantes

---

## 📁 **Dataset y Metodología**

### 📊 **Características del Dataset**
- **Fuente:** Google Maps scrapeado con **Apify API**
- **Volumen:** 8,277 registros comerciales
- **Estructura:** 16 columnas de datos
- **Procesamiento:** Limpieza profunda con normalización, eliminación de duplicados y corrección de caracteres especiales

### 🔍 **Categorías Comerciales Analizadas**

| Sector | Palabras Clave Buscadas |
|--------|-------------------------|
| **🛒 Comercio General** | Online, Comercio, Ventas, Tienda, Bazar, Regalería |
| **💻 Tecnología** | Tecnología, Electrónica, Computación, Telefonía, Web |
| **🏗️ Construcción & Hogar** | Construcción, Muebles, Hogar, Blanquería, Electrodomésticos |
| **🚗 Automotriz** | Vehículos, Repuestos, Maquinaria |
| **🏃‍♂️ Servicios & Otros** | Servicios, Deportivo, Inmobiliario, Ecommerce, Venta Online |
| **👔 Indumentaria** | Ropa |

---

## 📈 **Estructura del Análisis**

### 📋 **Secciones del Notebook**

1. **🚀 Introducción y Contexto**
   - Historia del problema
   - Objetivos del análisis

2. **🔧 Preparación de Datos**
   - Importación y limpieza
   - Exploración inicial

3. **📊 Análisis Descriptivo**
   - Estadísticas generales
   - Distribuciones por ciudad

4. **🌐 Análisis de Presencia Digital**
   - Completitud de información
   - Análisis de sitios web y RRSS

5. **🏙️ Comparativa Regional**
   - Patrones por ciudad
   - Correlaciones poblacionales

6. **💡 Insights y Conclusiones**
   - Hallazgos principales
   - Recomendaciones

---

## 🚀 **Principales Insights**

> Los resultados revelan diferencias significativas entre ciudades en cuanto a digitalización comercial

### 🔍 **Hallazgos Esperados**
- 📊 Métricas de completitud de información por ciudad
- 🌐 Estado actual de la digitalización comercial regional
- 🏪 Patrones de comportamiento según tamaño de ciudad
- 💡 Oportunidades de mejora identificadas para comerciantes

### 📈 **Visualizaciones Incluidas**
- 📊 Gráficos de barras comparativos entre ciudades
- 🥧 Distribuciones porcentuales de presencia digital
- 🗺️ Análisis geográfico regional
- 📈 Correlaciones población vs digitalización



---

## 🚀 **¡Explorá el Análisis Completo!**

> *"De la necesidad de un repuesto a entender la digitalización comercial regional"*

**📓 Notebook:** [Ver análisis completo]  (https://github.com/MCCastroMaluta/Portfolio-Python-esp/blob/main/dataPrep.ipynb)
**🔗 Repositorio:** [Mi github](https://github.com/MCCastroMaluta/Portfolio_data/tree/main/Python_esp)  
**📧 Contacto:** mccastromaluta@gmail.com  
**📍 Ubicación:** Tandil, Buenos Aires, Argentina

---

*📝 Este análisis busca transformar una experiencia personal en insights útiles para la comunidad comercial regional y contribuir al desarrollo del ecosistema digital local.*
