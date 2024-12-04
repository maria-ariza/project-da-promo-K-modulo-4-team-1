•	_id: Identificador único de cada usuario.
•	sum_app_opens: Cantidad total de veces que el usuario ha abierto la aplicación.
•	no_of_days: Número de días en los que el usuario ha utilizado la aplicación.
•	nrOfConversations: Número total de conversaciones que el usuario ha tenido.
•	longestConversation: Duración de la conversación más larga (en minutos o mensajes, según el contexto).
•	longestConversationInDays: Duración de la conversación más larga en días.
•	averageConversationLength: Duración promedio de las conversaciones (en minutos o mensajes).
•	averageConversationLengthInDays: Duración promedio de las conversaciones en días.
•	medianConversationLength: Mediana de la duración de las conversaciones (en minutos o mensajes).
•	medianConversationLengthInDays: Mediana de la duración de las conversaciones en días.
•	nrOfOneMessageConversations: Número de conversaciones que consistieron en un solo mensaje.
•	percentOfOneMessageConversations: Porcentaje de las conversaciones totales que fueron de un solo mensaje.
•	nrOfGhostingsAfterInitialMessage: Número de veces que el usuario fue "ghosteado" tras enviar el mensaje inicial.
•	no_of_matches: Número total de matches que el usuario ha obtenido.
•	no_of_msgs_sent: Número total de mensajes enviados por el usuario.
•	no_of_msgs_received: Número total de mensajes recibidos por el usuario.
•	swipe_likes: Número de "likes" que el usuario recibió al deslizar hacia la derecha.
•	swipe_passes: Número de "passes" (rechazos) que recibió el usuario.
•	birthDate: Fecha de nacimiento del usuario.
•	ageFilterMin: Edad mínima establecida en el filtro de búsqueda del usuario.
•	ageFilterMax: Edad máxima establecida en el filtro de búsqueda del usuario.
•	cityName: Ciudad donde se encuentra el usuario.
•	country: País donde se encuentra el usuario.
•	createDate: Fecha de alta del usuario en la aplicación.
•	education: Nivel educativo del usuario.
•	gender: Género del usuario.
•	interestedIn: Género(s) de las personas en las que el usuario está interesado.
•	Instagram: Indica si el usuario ha vinculado o compartido su perfil de Instagram (sí o no).
•	spotify: Indica si el usuario ha vinculado o compartido su perfil de Spotify (sí o no).
•	jobTitle: Profesión del usuario.
•	user_age: Edad actual del usuario.


Descripción del Dataset de Tinder

General
•	Total de Filas: 1209
•	Total de Columnas: 31
•	Duplicados: 0 duplicados, lo que representa un 0.0%.
•	Nulos: No hay columnas con datos nulos (100% completas).

Variables Principales
1.	_id
•	Identificador único de cada usuario.
•	Tipo: object.
•	Valores únicos: 1209.
2.	sum_app_opens
•	Suma total de veces que un usuario abrió la aplicación.
•	Tipo: int64.
•	Media: 4593.92, Máximo: 92628.
3.	no_of_days
•	Número de días en los que el usuario abrió la app.
•	Tipo: int64.
•	Media: 327.33, Máximo: 2319.
4.	nrOfConversations
•	Número total de conversaciones que el usuario inició.
•	Tipo: int64.
•	Media: 241.91, Máximo: 12642.
5.	longestConversation
•	Duración de la conversación más larga (en mensajes).
•	Tipo: int64.
•	Media: 139.11, Máximo: 2264.
6.	longestConversationInDays
•	Duración de la conversación más larga en días.
•	Tipo: int64.
•	Media: 166.40, Máximo: 2284.
7.	averageConversationLength
•	Duración promedio de las conversaciones (en mensajes).
•	Tipo: float64.
•	Media: 9.81, Máximo: 461.
8.	averageConversationLengthInDays
•	Duración promedio de las conversaciones en días.
•	Tipo: float64.
•	Media: 3.66, Máximo: 92.71.
9.	medianConversationLength
•	Mediana de la duración de las conversaciones (en mensajes).
•	Tipo: int64.
•	Media: 4.27, Máximo: 920.
10.	medianConversationLengthInDays
•	Mediana de la duración de las conversaciones en días.
•	Tipo: float64.
•	Media: 0.52, Máximo: 185.19.

Datos Sobre la Actividad
•	nrOfOneMessageConversations: Conversaciones de un solo mensaje (Promedio: 75.72).
•	percentOfOneMessageConversations: Porcentaje de estas conversaciones (Promedio: 30.97%).
•	nrOfGhostingsAfterInitialMessage: Veces que el usuario fue "ghosteado" después del primer mensaje (Promedio: 29.51).
•	no_of_matches: Matches obtenidos (Promedio: 542.21, Máximo: 23758).
•	no_of_msgs_sent: Mensajes enviados (Promedio: 1884.51).
•	no_of_msgs_received: Mensajes recibidos (Promedio: 1793.08).

Demográficos y Filtros
•	birthDate: Fecha de nacimiento.
•	user_age: Edad del usuario (Promedio: 24.39).
•	ageFilterMin / ageFilterMax: Edades mínima y máxima en filtros.
•	Media: 20.46 (Min), 95.21 (Max).

Información Adicional
•	cityName / country: Ubicación (muchos datos son "unknown").
•	education: Nivel educativo, con mayoría sin estudios superiores (1000 de 1209 usuarios).
•	gender / interestedIn: Género e intereses (Mayoría hombres interesados en mujeres).
•	instagram / spotify: Indicadores booleanos de si comparten redes sociales.

Estadísticas Destacadas
•	Mayor uso en hombres (1059 de 1209).
•	Profesión desconocida para 757 usuarios.
•	Alta concentración de actividad en pocos días y muchos mensajes enviados.


