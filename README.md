# Taller2_Gesti-n_Datos
</br></br>
Integrantes:</br></br>
Juan Sebastian Pineda</br></br>
Camilo Cano Ortega</br></br>
Daniel Duque</br></br>

</br></br>

# a. Descripción general de la colección de datos escogida.
</br></br>
Se utilizo la colección "sample_restaurants" especificamente la tabla "restaurants". que contiene las siguientes columnas
</br></br>
*   _id: ID del registro, </br></br>
*   address: Objeto con las propiedades: building, coord Array, street,zipcode </br>
*   borough: Zona de la ciudad </br>
*   cuisine: Tipo de cocina en la que se especializa el restaurante </br>
*   grades: Array de objetos, donde cada objeto es una calificación que se le dio al restaurante compuesta de un score, grade y la fecha en la que se realizó
*   name: Nombre del restaurante </br>
*   restaurant_id: ID del restaurante </br>

# b. Definición de las 3 preguntas de negocio que se quieren responder.
</br>
1.   Tipos de cocina con mejores calificaciones
</br></br>
Decidimos identificar que tipos de comida son más populares entre la gente, para compreder esto utilizamos el identificador de cocina y los scores que tuvo en promedio cada tipo de restaurante, el proceso se encuentra a continuación.
</br></br>
2.   Progreso de los restaurantes/ tipo de cocina con respecto al tiempo
</br></br>
Decidimos identificar el progreso de los restaurantes a traves de los años.Para esto se extrajeron las caracteristicas grade, year, name y cuisine  ,el proceso se encuentra a continuación.
</br></br>
3.   Definir cuales son los restaurante/tipos de cocina con mejor desempeño
</br></br>
Dando respuesta a las dos preguntas anteriores podemos dar analizar el desempeño de los restaurantes no solo teniendo en cuenta el score promedio sino tambien su cambio a travez de los años
</br></br>

# Analisis 
</br></br>

**Top 5 tipos de cocina por score**
</br></br>

Los resultados encontrados es que el top 5 de comidas preferidas son iranies, hawaiana, china/japonesa, polynesia y creole. Es posible que estos resutados se den por dos motivos (aparte de la calidad misma de la cocina) que consideramos, en primer lugar que aquellos restaurantes muy particulares, se pueden beneficiar de poca dispersion de reviews y de un sesgo de selección.
</br></br>

Las poca dispersión de reviews puede ser por pocos restaurantes representantes de este tipo de cocina, es decir, si solo hay un representante de cocina iranie y este restaurante es muy bueno, se entendera la categoría de comida iranie como muy buena, generando una conclusion un poco distorsionante.
</br></br>

En segundo lugar es posible que haya sesgo de seleccion, y la gente que decide ir a consumir algun tipo de esta comida haya realizado una busqueda fuerte y haya creado espectativas positivas frente a esta cocina (o la conozcan con anticipación) y generen una calificación superior a la que daría un tipo de cocina promedio.
</br></br>

Aún así es muy posible que estos restaurantes manifiesten efectivamente muy buena calidad y sean reconocidos de esta forma por parte de los clientes.
</br></br>


**Top 5 tipos de cocina peor calificados por score**
</br></br>

Los resultados que se encuentran aca pueden verse distorcionados de la misma manera que los resultados anteriores, aún asi hay unos casos particulares interesantes de analizar:
</br></br>

En primer lugar los hotdogs y hotdogs/pretzels estan muy mal calificados, y es un tipo de comida que se considera como comida de calle y puede tener algo de mala fama de manera previsible.
</br></br>

En segundo lugar la comida Creole era una de las mejor evaluadas, pero la conjucion Creole/Cajun se muestra como una de las peores, lo cual puede ser indicativo de uno o varios restaurantes Cajun de mala calidad o mal considerados.
</br></br>

Este tipo de restaurantes podrían ser una oportunidad de negocio pero pensando en clientes que no sean muy exigentes y que tengan pocas consideraciones acerca de la calidad del producto, y mas bien tratar de competir con precio. O por el contrario son buenas oportunidades para apuntarle a un producto de muy buena calidad en alguno de estos estilos de cocina pero con la inversion suficiente para subvertir la opinion del público general
