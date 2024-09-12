# Prueba Técnica

Utilizando la **PokeAPI** (https://pokeapi.co/), crea el siguiente proyecto que contenga lo siguiente:

## Menú de navegación:
Debe incluir los siguientes elementos:
- Logo de Pokémon
- **Home**
- **Favoritos**
- Link a la **PokeAPI** (https://pokeapi.co/)

## Página de Inicio:
La página de inicio debe mostrar la siguiente información en **cards**:

- Nombre del Pokémon
- Imagen (sprite) del Pokémon en su versión **shiny** si es que la tiene. En caso de no tener versión shiny, mostrar la imagen por defecto.
- Naturaleza del Pokémon. Cada naturaleza debe mostrarse con un color diferente, por ejemplo: fuego en color rojo, veneno en color morado, etc.
- Mostrar un mínimo de 4 estadísticas (stats), como por ejemplo: HP, Ataque, Defensa, Ataque Especial, etc.
- Cada card debe tener un botón para agregar el Pokémon a favoritos.

## Página de Favoritos:
- En esta página se deben mostrar los Pokémon que fueron seleccionados como favoritos en la página principal.
- Debe haber la posibilidad de eliminar Pokémon de la lista de favoritos.

## Tecnologías a utilizar:
- **React** o **Astro**
- **Tailwind CSS** (obligatorio)
- Peticiones a la API mediante **fetch** o **axios**

## Requerimientos de funcionalidad:
- Mostrar las cards en grupos de 20 y utilizar **infinite scroll** para cargar más elementos.
- Persistencia de los favoritos al cerrar la página (usando `localStorage` o una solución similar).

## Modularización de componentes:
- El proyecto debe estar organizado en **componentes reutilizables**. Algunos ejemplos de componentes que puedes crear son:
  - **Navbar**: Componente para el menú de navegación.
  - **PokemonCard**: Componente que mostrará la información de cada Pokémon (nombre, imagen, naturaleza, stats, etc.).
  
La modularización permitirá mantener el código limpio y organizado, lo cual es clave para proyectos escalables.


> [!NOTE]
> - ## Repositorio y despliegue:
> - El proyecto debe estar alojado en un repositorio de **GitHub**.
> - El proyecto debe estar desplegado en **Netlify** o **GitHub Pages** para poder ser evaluado.

> [!IMPORTANT]
> ## Notas adicionales:
> - Es obligatorio que la página sea completamente **responsiva**, adaptándose a vista móvil, tablet y desktop mediante **flexbox** o **grid** y **Tailwind CSS**.
> - El diseño será considerado como un criterio importante de evaluación.
