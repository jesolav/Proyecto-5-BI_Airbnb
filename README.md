# Proyecto Profundización: Business intelligence

**Objetivo:** 
El objetivo de este proyecto fue realizar un análisis exploratorio de datos sobre los listados de Airbnb en la ciudad de Nueva York, utilizando Power BI para visualizar patrones clave y tendencias que afectan la disponibilidad de habitaciones, precios, y reseñas de los huéspedes. A través de este análisis, se busca proporcionar insights accionables que permitan a los anfitriones optimizar sus estrategias de precios, mejorar la experiencia del usuario y maximizar la rentabilidad de sus propiedades.

<details>
<summary> ⚙️ Herramientas y Recursos</summary>

-Google BigQuery / SQL (Manejo de tablas)
-Power BI / Fórmulas DAX (Análisis Exploratorio).

</details>


<details>
<summary> 📄 Resumen de las Tablas de Airbnb </strong></summary>


<details>
<summary> <strong> Tabla rooms (Dimensión) </strong></summary>

* id: un identificador único para cada habitación.
* name: el nombre del anuncio de Airbnb
* neighbourhood: acrónimo del barrio en el que se encuentra el anuncio de Airbnb neighbourhoodgroup: barrio en el que se encuentra el anuncio de Airbnb
* latitude: la coordenada de latitud del anuncio de Airbnb
* longitude: la coordenada de longitud del anuncio de Airbnb
* roomtype: el tipo de habitación que ofrece el anuncio de Airbnb
* minimum_nights: el número mínimo de noches necesarias para reservar el anuncio de Airbnb
</details>


<details>
<summary> <strong>  Tabla hosts (Dimensión) </strong></summary>

* hostid : un identificador único para cada host.
* hostname: el nombre del anfitrión del anuncio de Airbnb

</details>

<details>
<summary> <strong> Tabla reviews (Hechos): </strong></summary>

* id: un identificador único para cada habitación.
* hostid : un identificador único para cada host.
* price: el precio por noche del anuncio de Airbnb
* numberofreviews: el número total de reseñas que ha recibido el anuncio de Airbnb
* lastreview: la fecha de la última reseña que recibió el anuncio de Airbnb
* reviewspermonth: El número promedio de reseñas que recibe el anuncio de Airbnb por mes
* calculatedhostlistingscount: el número total de listados que tiene el anfitrión
* availability365: la cantidad de días que el anuncio de Airbnb está disponible para reservar en un año
</details>


</details>

## 💻 [Procesamiento y preparación para analisis de datos:] 

[1.1 Conectar/importar datos a herramientas](https://github.com/jesolav/Proyecto-5-BI_Airbnb/blob/8813c81042807e9279bc7471b676b4f54508ab8b/1.%20Procesar%20y%20preparar%20la%20base%20de%20datos/1.1%20Conectar-importar%20datos%20a%20herramientas.md)

[1.2 Análisis de nulos y duplicados](https://github.com/jesolav/Proyecto-5-BI_Airbnb/blob/8813c81042807e9279bc7471b676b4f54508ab8b/1.%20Procesar%20y%20preparar%20la%20base%20de%20datos/1.2%20An%C3%A1lisis%20de%20Nulos%20y%20Duplicados.md)

[1.3 Identificar Y Manejar Datos Fuera Del Alcance Del Análisis](https://github.com/jesolav/Proyecto-5-BI_Airbnb/blob/8813c81042807e9279bc7471b676b4f54508ab8b/1.%20Procesar%20y%20preparar%20la%20base%20de%20datos/1.3%20Identificar%20Y%20Manejar%20Datos%20Discrepantes%20En%20Variables%20Categ%C3%B3ricas.md)

## 🔎 [Análisis exploratorio:]


[2.1 Relacionar tablas PowerBI](https://github.com/jesolav/Proyecto-5-BI_Airbnb/blob/4e5f1683ae8a3e9debeb6e21d81ce600ac26715f/2.%20EDA/2.1%20Relacionar%20Tablas%20PowerBI.md)

[2.2 DAX y columnas calculadas](https://github.com/jesolav/Proyecto-5-BI_Airbnb/blob/4e5f1683ae8a3e9debeb6e21d81ce600ac26715f/2.%20EDA/2.2%20DAX%20y%20Columnas%20Calculadas.md)


## 💡 [Enlaces de interés:]

[4.1 Presentación]()

[4.2 Dashboard](https://github.com/jesolav/Proyecto-5-BI_Airbnb/blob/2e2f8d6fd8671618e51081e7ef4393918deca0b4/3.%20Dashboard/3.1%20Dashboard%20(imagenes).md) 

[4.3 Conclusiones y Recomendaciones]()




