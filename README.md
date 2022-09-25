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

