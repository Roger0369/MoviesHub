## MovieHub - Proyecto de Página de Streaming - MovieHub

# 1. Resumen de máximo 3 líneas de tu proyecto

MovieHub es una página web de simulación de películas streaming, con una pantalla de inicio de sesión y un catálogo de películas. El objetivo es mostrar películas e información relacionada a cada película, además de tener funcionalidades de ofrecer sugerencias de películas similares, guardar películas en favoritos y permitir al usuario ocultar las que no le gustan mostrando un mensaje de confirmación antes de ocultar la película.

# 2. Requerimientos técnicos - Todo lo que usaste

- Lenguajes y tecnologías utilizadas:
  - HTML
  - CSS
  - JavaScript

- Recursos multimedia:
  - Video (`video.mp4`)
  - Imágenes en formato `.webp`

# 3. ¿Cómo instalar?

# Método 1: Visualización en línea
Accede al proyecto mediante el siguiente enlace:


# 💻 Método 2: De manera local
1. Descarga o clona el repositorio desde:  
   `https://github.com/Roger0369/MoviesHub`
2. Abre el archivo `index.html` con tu navegador (Chrome, Edge, etc.)
3. Iniciarás en la pantalla de login.

# 4. Mockup de la aplicación
![mockup](https://github.com/user-attachments/assets/882256be-b418-4548-a725-503030dbe0c7)

# 5. Capturas de pantalla

1. **Pantalla de Login**  
   Simulación de inicio de sesión con usuario `Liderly` y contraseña `123456`.
![Screenshot 2025-04-06 101542](https://github.com/user-attachments/assets/12645b11-eece-44e0-a6c4-e517841d778c)

2. **Catálogo de Películas**  
   Visualización general con posters, descripciones y botones de interacción.
![Screenshot 2025-04-06 101605](https://github.com/user-attachments/assets/3e72889b-906e-4f66-995a-6177389b16b0)

3. **Detalle de Película**  
   Cada película cuenta con una página individual con información extendida.
![Screenshot 2025-04-06 101654](https://github.com/user-attachments/assets/ab1bc7ec-3af7-4939-8216-5b6c666a66b4)

4. **Películas Sugeridas**  
   Se muestran recomendaciones similares a la película seleccionada.
![Screenshot 2025-04-06 101658](https://github.com/user-attachments/assets/0fc6cf13-1980-4a71-8276-4d5f15ae6d6a)

5. **Películas Ocultas**  
   Las películas que no gustan se pueden ocultar dinámicamente del catálogo.
![Screenshot 2025-04-06 101712](https://github.com/user-attachments/assets/e355390e-a517-47df-9d6d-1dc23581a663)


# 6. Proceso de desarrollo

###  Fase 1: Login
- Se creó un formulario de login (sin autenticación real por ahora).
- Archivos: `index.html`, `styles.css`, `script.js`

###  Fase 2: Catálogo de Películas
- Se creó la carpeta `catalog` con los archivos `index.html`, `styles.css`, `script.js`, `movies.js`
- Cada película tiene su propio archivo HTML detallado
- Carpeta `img/` para almacenar las imágenes de posters.
- Mediante javascript se crean las tarjetas de películas tomando la información de movies.js
- Se definen los estilos de cada página

###  Fase 3: Creación de Lógica
- Se implementa la funcionalidad de los botones: Ver/Más información, Añadir a favoritos, Ocultar películas 
- Se crean la funciones de cada botón, se realizan pruebas de que funcionen correctamente a lo esperado y se implementan cambios 


## 7. Sprint Review
¿Qué salió bien?
- Estructura inicial del login y catálogo
- Simulación de recomendaciones
- Añadir a favoritos
- Ocultar película

¿Qué puedo hacer diferente?
- Mejorar el diseño que se más responsivo
- Que tenga más funcionalidades como filtros por categoría por ejemplo
- Planeación y dividir las funcionalidades en partes pequeñas o módulos 

¿Qué no salió bien?  
- La función de ocultar películas se puede mejorar
- El login no está conectado a una base de datos
- Hay pocas opciones de catalogo de peliculas

