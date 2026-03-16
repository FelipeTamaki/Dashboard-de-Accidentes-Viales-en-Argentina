# Dashboard de Accidentes Viales en Argentina

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un **dashboard interactivo para analizar accidentes viales en Argentina**.  
El objetivo es identificar **patrones, tendencias y factores asociados a los accidentes** a través de visualizaciones de datos.

El dashboard permite explorar los datos según distintas dimensiones como **provincia, tipo de vehículo, horario, clima, tipo de víctima y modo del accidente**, facilitando el análisis del fenómeno de forma visual e interactiva.

El análisis busca generar **insights que puedan ayudar a entender mejor la distribución de los accidentes y posibles factores de riesgo**.

---

## Dataset

El dataset contiene registros de accidentes viales con información sobre:

- Fecha del accidente (año, mes y día)
- Provincia y departamento
- Tipo de vehículo involucrado
- Tipo de víctima
- Condición climática
- Estado del semáforo
- Medio de transporte
- Tipo de vía
- Edad de víctimas e imputados

El conjunto de datos analizado contiene aproximadamente **26.000 accidentes registrados**.

---

## Análisis realizado

El dashboard permite analizar diferentes dimensiones del problema.

### Panorama general

Se presentan indicadores clave como:

- **Cantidad total de accidentes**
- **Mes con mayor cantidad de accidentes**
- **Horario con mayor ocurrencia**
- **Edad promedio de víctimas e imputados**

También se incluyen visualizaciones sobre:

- evolución de accidentes por **mes**
- variación de accidentes por **año**
- distribución de accidentes por **provincia**

---

### Análisis geográfico

Se utiliza un **treemap por provincia** para identificar la concentración territorial de accidentes.  
Se observa que **Buenos Aires concentra la mayor cantidad de accidentes**, seguido por otras provincias con menor participación relativa.

---

### Análisis por tipo de accidente

Se analiza la **proporción de modos de accidente**, donde predominan:

- colisiones entre vehículos
- vuelcos o despistes
- colisiones vehículo-persona
- colisiones vehículo-objeto

---

### Análisis por condiciones climáticas

La mayoría de los accidentes ocurre en **condiciones climáticas buenas**, lo que sugiere que el volumen de tránsito puede ser un factor más determinante que el clima.

---

### Análisis por tipo de vehículo

Los resultados muestran que:

- **Motocicletas** presentan la mayor cantidad de accidentes
- **Automóviles** aparecen en segundo lugar
- otros vehículos tienen menor participación relativa

También se analiza la relación entre **tipo de vehículo y tipo de vía**.

---

### Análisis por tipo de víctima

Los **conductores** representan la mayor proporción de víctimas, seguidos por:

- acompañantes
- peatones
- pasajeros

---

## Herramientas utilizadas

- **Power BI**
- **DAX**
- Modelado de datos
- Visualización de datos

---

## Estructura del proyecto

Accidentes-Viales-Dashboard
│
├── dashboard.pbix
├── dataset_accidentes.csv
└── README.md


---

## Conclusiones

El análisis permite identificar algunos patrones relevantes:

- fuerte concentración de accidentes en ciertas provincias  
- mayor ocurrencia en horarios específicos  
- alta participación de motocicletas en los accidentes  
- predominancia de colisiones entre vehículos  

El dashboard permite **explorar los datos de forma interactiva y detectar áreas donde podrían implementarse políticas de prevención y seguridad vial**.
