# Mi Proyecto  
# 🔍 Análisis de Presencia Digital de Comercios  
## *Del problema local a la investigación regional*

![Tandil](https://github.com/MCCastroMaluta/Portfolio-Python-es/blob/master/Images/Portada.png)

---

## 🛠️ **Stack Tecnológico**

### 🔧 **Herramientas y Proceso**
- 🐍 **Python** – Análisis de datos  
- 📊 **Pandas** – Manipulación de datasets  
- 📈 **Matplotlib / Seaborn** – Visualizaciones  
- 🌐 **Apify API** – Web scraping de Google Maps  
- 📓 **Jupyter Notebook** – Desarrollo y presentación  

**Proceso:** Extracción → Limpieza → Exploración → Visualización → Conclusiones

---

## 🎯 **La Historia Detrás del Análisis**

### 🛠️ El Problema Inicial  
> **350 km de distancia** para un repuesto de bordeadora STIHL FSE60

🏪 **Un día recorriendo Tandil...**  
- ❌ Búsquedas online sin éxito  
- 🚶‍♂️ Recorrido físico por la ciudad  
- 💡 ¡Eureka! Un comercio conocía dónde conseguirlo  
- 🤔 La pregunta: *¿Cuántos comercios tienen información completa online?*

---

## 🔬 **Metodología de Investigación**

### 🌐 **Fuente de Datos: Google Maps via API Apify**
- 🎯 Objetivo: Analizar la presencia digital de comercios locales 
- 📍 Alcance: 5 ciudades del centro de Buenos Aires 
- 👥 Rango poblacional: 16,000 - 160,000 habitantes

---

### 🏙️ **Ciudades Analizadas**

| Ciudad             | Habitantes | Región     | Clasificación       |
|--------------------|------------|------------|---------------------|
| Tandil             | 150,162    | Centro BA  | Ciudad grande 🏙️    |
| Olavarría          | 125,751    | Centro BA  | Ciudad grande 🏙️    |
| Azul               | 75,905     | Centro BA  | Ciudad mediana 🏘️   |
| Benito Juárez      | 22,292     | Centro BA  | Ciudad pequeña 🏡    |
| Rauch              | 16,635     | Centro BA  | Ciudad pequeña 🏡    |

---

## 📊 **Variables y Métricas Analizadas**

### 🎯 **Métricas Clave**

| Métrica               | Descripción                              | Objetivo                          |
|-----------------------|------------------------------------------|-----------------------------------|
| 📱 Presencia en RRSS  | % comercios con Facebook/Instagram       | Evaluar digitalización social     |
| 🌐 Sitio Web          | % comercios con página web registrada    | Medir presencia web oficial       |
| 📍 Datos Completos    | % perfiles con información completa      | Analizar completitud en Google Maps |
| 📞 Información de Contacto | Teléfonos y direcciones disponibles | Evaluar accesibilidad             |
| ⭐ Reviews y Ratings  | Cantidad y calificación promedio         | Medir actividad en la plataforma  |

### 📋 **Variables de Análisis**
- ✅ Completitud de datos en Google Maps  
- 🌐 Presencia web (sitios oficiales)  
- 📱 Redes sociales (Facebook, Instagram, otras)  
- 🏪 Distribución por ciudad  

---

## 🎯 **Objetivos Específicos del Análisis**

### 🔍 **Preguntas de Investigación**

1. ¿Qué porcentaje de comercios tiene presencia digital por ciudad?  
2. ¿Qué categorías comerciales están más digitalizadas?  
3. ¿La digitalización impacta en la percepción de calidad?

### 💡 **Objetivos de Impacto**
- 🔍 Diagnóstico de la situación actual  
- 💡 Identificación de oportunidades de mejora  
- 📈 Cuantificación del impacto digital  
- 🎯 Recomendaciones estratégicas

---

## 📁 **Dataset y Metodología**

### 📊 **Características del Dataset**
- **Fuente:** Google Maps scrapeado con Apify API  
- **Volumen original:** 8,277 registros comerciales  
- **Registros finales analizados:** 5,859 (tras eliminación de duplicados y limpieza)  
- **Estructura:** 16 columnas de datos  
- **Procesamiento:** Limpieza profunda con normalización, eliminación de duplicados y corrección de caracteres especiales

### 🔍 **Categorías Comerciales Analizadas**

| Sector                     | Palabras Clave Buscadas                                      |
|----------------------------|--------------------------------------------------------------|
| 🛒 Comercio General        | Online, Comercio, Ventas, Tienda, Bazar, Regalería           |
| 💻 Tecnología              | Tecnología, Electrónica, Computación, Telefonía, Web         |
| 🏗️ Construcción & Hogar   | Construcción, Muebles, Hogar, Blanquería, Electrodomésticos  |
| 🚗 Automotriz              | Vehículos, Repuestos, Maquinaria                             |
| 🏃‍♂️ Servicios & Otros     | Servicios, Deportivo, Inmobiliario, Ecommerce, Venta Online   |
| 👔 Indumentaria            | Ropa                                                         |

---

## 📈 **Estructura del Análisis**

### 📋 **Secciones del Notebook**

1. 🚀 Introducción y Contexto  
2. 🔧 Preparación de Datos  
3. 📊 Análisis Descriptivo  
4. 🌐 Análisis de Presencia Digital  
5. 🏙️ Comparativa Regional  
6. 💡 Insights y Conclusiones  

---

## 📋 Resumen Ejecutivo del Análisis

Este bloque sintetiza los principales indicadores del estudio, basado en **5,859 registros comerciales** depurados tras limpieza y eliminación de duplicados.

| Indicador                             | Valor                                               |
|--------------------------------------|-----------------------------------------------------|
| 🏙️ Total de ciudades analizadas      | 5 ciudades                                          |
| 🏪 Total de comercios analizados     | 5,859 registros                                     |
| 🌐 Presencia web promedio            | 25.40%                                              |
| 🏆 Ciudad con mayor presencia web    | Tandil (35.29%)                                     |
| ⚠️ Ciudad con menor presencia web    | Benito Juárez (18.05%)                              |
| 📦 Categoría más frecuente           | Tienda De Ropa (464 registros)                      |
| 🔗 Porcentaje con Dominio Propio     | 53.77%                                              |
| ⭐ Puntaje promedio (Máximo 5)        | 4.52                                                |
| 📉 Porcentaje sin calificar          | 23.81%                                              |

> Este resumen permite visualizar rápidamente el estado de la digitalización comercial en la región, destacando brechas, fortalezas y oportunidades de mejora.

---

## 🧾 **Conclusión General**

El análisis revela una digitalización comercial desigual entre ciudades y categorías:

- 🏙️ Ciudades más grandes como Tandil y Olavarría muestran mayor presencia web y mejor completitud de datos.  
- 🏪 Categorías como Tienda de Ropa y Agencia Inmobiliaria lideran en registros completos y presencia digital.  
- 🌐 Dominio Propio representa más del 50% de los sitios web, lo que indica inversión en identidad digital.  
- 📱 Instagram y Facebook son las redes sociales más utilizadas, aunque con menor peso que los sitios personalizados.  
- 📈 Los puntajes de calificación se concentran entre 4.0 y 4.5, con un pico en 5.0, lo que refleja una percepción positiva general.  
- ⚠️ Más del 30% de los comercios no están calificados, lo que sugiere falta de información en muchos casos.

> En conjunto, los datos muestran una cultura digital en crecimiento, pero con brechas claras que deben ser atendidas para lograr una digitalización más equitativa y robusta.

---

## 📌 **Recomendaciones Estratégicas**

1. **Agrupar categorías similares** para facilitar el análisis y mejorar la visibilidad de rubros dispersos.  
2. **Fomentar el uso de dominio propio** entre comercios pequeños para fortalecer su identidad digital.  
3. **Capacitar a comerciantes en plataformas visuales** como Instagram y Facebook, aprovechando su alcance.  
4. **Promover la calificación de comercios** en Google Maps para mejorar la percepción de calidad y confianza.  
5. **Priorizar la digitalización en ciudades pequeñas**, donde la brecha es más pronunciada y el impacto puede ser mayor.

---

## 🚀 **¡Explorá el Análisis Completo!**

> *"De la necesidad de un repuesto a entender la digitalización comercial regional"*

**💼 Portfolio:** [Mi Portfolio](https://www.datascienceportfol.io/mccastromaluta)  
**📓 Notebook:** [Ver análisis completo](https://github.com/MCCastroMaluta/Portfolio-Python-es/tree/master/Notebooks)  
**🔗 Repositorio:** [Mi GitHub](https://github.com/MCCastroMaluta/Portfolio-Python-es/tree/master)  
**📧 Contacto:** mccastromaluta@gmail.com  
**📍 Ubicación:** Tandil, Buenos Aires, Argentina

---

*📝 Este análisis busca transformar una experiencia personal en insights útiles para la comunidad comercial regional y contribuir al desarrollo del ecosistema digital local.*