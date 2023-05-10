# Análisis Exploratiorio y Modelo de Lenguaje Natural para la Categorización de Comentarios de VivaAerobús

## Elevator Pitch

¿Qué pasaría si pudieras entender lo que realmente quieren tus clientes sin tener que leer cada comentario uno por uno? Con nuestro enfoque innovador de Análisis Exploratorio y Modelo de Lenguaje Natural, estamos transformando la forma en que se categorizan los comentarios, permitiéndote obtener información valiosa de manera rápida y precisa.

Imagina poder identificar de manera automática las preocupaciones más comunes de tus clientes, descubrir tendencias emergentes y conocer las áreas de mejora más importantes. Nuestro análisis exploratorio utiliza técnicas avanzadas para desentrañar los patrones ocultos en los comentarios, brindándote una visión profunda de lo que realmente importa para tus pasajeros.

Pero eso no es todo. Con nuestro modelo de lenguaje natural, llevamos el análisis un paso más allá al comprender el significado y la intención detrás de cada comentario. Podemos clasificarlos en categorías relevantes, como servicio al cliente, comodidad, puntualidad y más, proporcionándote información precisa y detallada en tiempo real.

Imagina el impacto que esto podría tener en la toma de decisiones estratégicas de VivaAerobús. Al tener una comprensión clara de las necesidades y expectativas de tus clientes, podrás tomar medidas proactivas, mejorar el servicio y ofrecer una experiencia excepcional que superará todas las expectativas.

El análisis exploratorio y el modelo de lenguaje natural están aquí para cambiar el juego en la categorización de comentarios de VivaAerobús. Únete a nosotros en este viaje hacia la excelencia en el servicio y la satisfacción del cliente sin igual.

## Pitch

¿Qué pasaría si pudieras entender lo que realmente quieren tus clientes sin tener que leer cada comentario uno por uno?

En nuestro proceso de análisis exploratorio y modelo de lenguaje natural para la categorización de comentarios de VivaAerobús, utilizamos una base de datos que incluía comentarios reales de los clientes, junto con su puntuación NPS, fecha de publicación y, en algunos casos, una calificación en lugar del NPS.

Para garantizar la calidad de los datos, nos aseguramos de eliminar cualquier fila con columnas vacías, lo que nos permitió trabajar con información completa y confiable. Además, realizamos la conversión de las calificaciones a puntuaciones NPS, lo que nos permitió obtener una medida estandarizada y comprensible del nivel de satisfacción del cliente.

Dado que nuestra base de datos incluía comentarios en diferentes idiomas, implementamos un proceso de traducción automática para asegurarnos de que todos los mensajes estuvieran en español. Esto nos permitió trabajar con una muestra homogénea y comprensible para el análisis.

Para mejorar la calidad de los datos de texto, eliminamos las stopwords, que son palabras comunes que no aportan información relevante. Luego, tokenizamos los comentarios, dividiéndolos en unidades más pequeñas para su procesamiento. Utilizamos una red neuronal con capas densas y dropout para entrenar un modelo que pudiera predecir el NPS score de un comentario dado. Obtuvimos resultados prometedores, con una precisión categórica del 100% y una pérdida inferior al 10%.

Además de la categorización de comentarios, también nos interesó analizar la evolución del NPS a lo largo del tiempo. Realizamos series de tiempo para comprender la frecuencia y la variación del valor NPS en diferentes períodos. Además, generamos mapas de calor que mostraban el promedio del NPS en diferentes áreas, brindando información visualmente impactante sobre las fortalezas y debilidades de la compañía en términos de satisfacción del cliente.

Para un análisis más profundo, incorporamos topología, lo que nos permitió descubrir patrones y relaciones más complejas en los datos. Esta técnica nos brindó una comprensión más completa de las interacciones y los factores que influyen en el NPS.

Además, aplicamos la técnica de extracción del tema principal del comentario utilizando Latent Dirichlet Allocation (LDA), lo que nos permitió identificar los temas dominantes dentro de los comentarios. Aunque obtuvimos buenos resultados, reconocemos que el uso de datos sin etiquetar y la falta de un modelo preentrenado podrían mejorar aún más esta técnica en el futuro.

Finalmente, creamos un dashboard interactivo en Looker Studio, proporcionando a VivaAerobús una herramienta intuitiva para explorar y visualizar los resultados del análisis. Esto les permitirá tomar decisiones más informadas y estratégicas para mejorar continuamente la experiencia de sus pasajeros.

Nuestro enfoque de análisis exploratorio y modelo de lenguaje natural combinado con herramientas interactivas de visualización está revolucionando la forma en que VivaAerobús entiende y utiliza los comentarios de sus clientes. Únete a nosotros en este viaje hacia la excelencia en la satisfacción del cliente y la toma de decisiones basada en datos sólidos.
