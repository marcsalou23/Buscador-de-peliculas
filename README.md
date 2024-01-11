# Buscador de Películas

Esta aplicación web es un buscador de películas desarrollado en React que te permite buscar información sobre tus películas favoritas. Puedes ingresar el nombre de la película en el campo de búsqueda y obtener resultados instantáneos. Además, la aplicación ofrece la opción de ordenar los resultados.

## Funcionalidades

- **Búsqueda Instantánea**: La aplicación actualiza los resultados de búsqueda a medida que escribes en el campo de búsqueda, proporcionando una experiencia de búsqueda instantánea.

- **Ordenar Resultados**: Puedes ordenar los resultados de búsqueda con un simple clic en la opción de orden en la interfaz.

- **Validaciones de Búsqueda**: La aplicación realiza validaciones en tiempo real para garantizar que la búsqueda sea válida. Se proporcionan mensajes de error si la búsqueda es vacía, contiene números o tiene menos de 3 caracteres.

## Instalación

1. Clona este repositorio en tu máquina local.

   ```bash
   git clone https://github.com/tuusuario/buscador-de-peliculas.git](https://github.com/marcsalou23/Buscador-de-peliculas/blob/main/README.md
   cd buscador-de-peliculas
   ```

2. Instala las dependencias utilizando npm.

   ```bash
   npm install
   ```

3. Inicia la aplicación.

   ```bash
   npm start
   ```

   La aplicación estará disponible en [http://localhost:3000](http://localhost:3000) en tu navegador.

## Uso

1. Ingresa el nombre de la película que deseas buscar en el campo de búsqueda.

2. Opcionalmente, marca la casilla de ordenar para cambiar el orden de los resultados.

3. Haz clic en el botón "Buscar" o simplemente presiona Enter para obtener los resultados.

## Estructura del Proyecto

- `src/App.css`: Estilos CSS para la aplicación.
- `src/hooks/useMovies.js`: Hook personalizado para gestionar la lógica relacionada con las películas.
- `src/components/Movies.jsx`: Componente de React para mostrar la lista de películas.
- `src/App.js`: Componente principal que integra la lógica y la interfaz de usuario.

## Contribuciones

Si encuentras algún problema o tienes alguna mejora que sugerir, no dudes en abrir un problema o enviar una solicitud de extracción. ¡Las contribuciones son bienvenidas!

