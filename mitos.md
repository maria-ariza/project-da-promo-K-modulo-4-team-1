1. "Los usuarios más activos son los más exitosos"
•	Mito: Abrir la app más veces asegura más matches.
•	Datos: sum_app_opens vs. no_of_matches.
•	Visualización: Gráfico de dispersión para correlacionar la actividad y los matches, resaltando los "superusuarios".
________________________________________
2. "El ghosting ocurre solo en conversaciones largas"
•	Mito: Las conversaciones largas tienen más probabilidad de acabar en ghosting.
•	Datos: nrOfGhostingsAfterInitialMessage vs. averageConversationLength.
•	Visualización: Mapa de calor mostrando la relación entre duración y ghosting.
________________________________________
3. "Un solo mensaje es todo lo que necesitas"
•	Mito: Las conversaciones de un mensaje generan éxito.
•	Datos: nrOfOneMessageConversations vs. no_of_matches.
•	Visualización: Un gráfico circular con el porcentaje de éxito por longitud de conversación.
________________________________________
4. "Cuanto más hablas, más te quieren"
•	Mito: Más mensajes enviados aseguran más matches.
•	Datos: no_of_msgs_sent vs. no_of_matches.
•	Visualización: Gráfico de barras con categorías de mensajes enviados y su éxito.
________________________________________
5. "Los millennials son los reyes de Tinder"
•	Mito: Las personas jóvenes tienen más éxito.
•	Datos: user_age vs. no_of_matches.
•	Visualización: Gráfico de líneas mostrando el éxito por grupos de edad.
________________________________________
6. "El país influye en el éxito"
•	Mito: Algunos países son mejores para ligar que otros.
•	Datos: country vs. no_of_matches.
•	Visualización: Un mapa mundial interactivo mostrando "matches" por país.
________________________________________
7. "La educación garantiza más matches"
•	Mito: Cuanto mayor sea el nivel educativo, más atractiva es la persona.
•	Datos: education vs. no_of_matches.
•	Visualización: Gráfico de barras apiladas por nivel educativo.
________________________________________
8. "El filtro de edad es la clave del éxito"
•	Mito: Usar un rango de edad más amplio asegura más matches.
•	Datos: (ageFilterMax - ageFilterMin) vs. no_of_matches.
•	Visualización: Gráfico de dispersión con burbujas de tamaño proporcional a los matches.
________________________________________
9. "Compartir Instagram o Spotify te hace irresistible"
•	Mito: Las personas que comparten Instagram o Spotify consiguen más "matches".
•	Datos: Instagram / spotify vs. no_of_matches.
•	Visualización: Un gráfico de barras comparando usuarios que comparten y los que no.
________________________________________
10. "Las ciudades grandes tienen más éxito"
•	Mito: Vivir en una ciudad grande aumenta las posibilidades.
•	Datos: cityName vs. no_of_matches.
•	Visualización: Mapa interactivo de ciudades con tamaño proporcional a los matches.
________________________________________
Bonus: Ideas para hacer tus visualizaciones más llamativas
1.	Nombres creativos para cada gráfico: Ejemplo, "La maldición del mensaje único" para el gráfico de conversaciones cortas.
2.	Colores vivos y temáticos: Usa tonos relacionados con Tinder (rojo, rosado, naranja).
3.	Gráficos interactivos: Permite filtrar por país, edad o género para insights personalizados.
4.	Comparaciones curiosas: Relaciona datos como swipe_likes con swipe_passes para identificar "campeones del rechazo".
1. "Los usuarios más activos son los que logran mantener conversaciones más largas"
•	Mito: Abrir la app constantemente lleva a relaciones más significativas.
•	Datos: sum_app_opens vs. longestConversation.
•	Visualización: Gráfico de dispersión con una línea de tendencia.
________________________________________
2. "La duración promedio de las conversaciones está relacionada con el éxito en matches"
•	Mito: Las personas que tienen conversaciones más largas suelen tener más matches.
•	Datos: averageConversationLength vs. no_of_matches.
•	Visualización: Un gráfico de barras apiladas que compare longitudes promedio con cantidad de matches.
________________________________________
3. "El ghosting depende de la edad del usuario"
•	Mito: Los usuarios más jóvenes son más propensos a ser "ghosteados".
•	Datos: user_age vs. nrOfGhostingsAfterInitialMessage.
•	Visualización: Un gráfico de líneas mostrando la incidencia de ghosting por grupo etario.
________________________________________
4. "La cantidad de matches está directamente relacionada con la cantidad de mensajes enviados"
•	Mito: Más mensajes enviados significa más éxito en términos de matches.
•	Datos: no_of_msgs_sent vs. no_of_matches.
•	Visualización: Gráfico de dispersión con áreas sombreadas para destacar correlaciones.
________________________________________
5. "Los filtros de edad determinan el éxito"
•	Mito: Usar un rango más amplio de edad aumenta las probabilidades de éxito.
•	Datos: (ageFilterMax - ageFilterMin) vs. no_of_matches.
•	Visualización: Gráfico de barras mostrando el éxito relativo por amplitud del rango de edad.
________________________________________
6. "Las personas con mayor nivel educativo tienen más interacciones significativas"
•	Mito: Un nivel educativo más alto favorece conversaciones más largas.
•	Datos: education vs. averageConversationLength.
•	Visualización: Gráfico de barras por nivel educativo y duración promedio de conversación.
________________________________________
7. "El éxito en las grandes ciudades es mayor que en las pequeñas"
•	Mito: Las personas que viven en grandes ciudades tienen más matches y conversaciones más largas.
•	Datos: cityName vs. no_of_matches y longestConversation.
•	Visualización: Mapa de calor por densidad de matches en las ciudades.
________________________________________
8. "Los hombres y las mujeres usan Tinder de forma diferente"
•	Mito: Hay diferencias claras en el comportamiento según el género.
•	Datos: gender vs. sum_app_opens, no_of_matches, nrOfConversations.
•	Visualización: Gráfico de barras comparando actividad, matches y conversaciones por género.
________________________________________
9. "El número de matches disminuye con la edad del usuario"
•	Mito: Los usuarios mayores tienen menos éxito en la app.
•	Datos: user_age vs. no_of_matches.
•	Visualización: Gráfico de líneas con grupos etarios para observar tendencias.
________________________________________
10. "Las personas que comparten Instagram o Spotify tienen un perfil más atractivo"
•	Mito: Agregar redes sociales aumenta la probabilidad de matches y conversaciones más largas.
•	Datos: Instagram, spotify vs. no_of_matches, averageConversationLength.
•	Visualización: Gráfico de barras comparando usuarios con y sin redes sociales compartidas.
________________________________________
Ideas adicionales para darle seriedad al análisis:
1.	Desglose por categorías: Analiza tendencias según el país o rango de edad.
2.	Análisis temporal: Observa cómo las métricas cambian desde createDate (fecha de alta).
3.	Panel de insights: Resume los resultados clave en un dashboard interactivo.
4.	Correlaciones profundas: Busca relaciones entre variables usando diagramas de dispersión y coeficientes.

