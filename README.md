# La Ruta de Ash

Página de fans para ver de principio a fin el viaje de Ash en el anime de Pokémon: las 25 temporadas y el arco final, 1219 capítulos.

- Reproductor dentro de la página para los capítulos que el canal oficial **TV Pokémon** tiene gratis en YouTube.
- Ficha de cada capítulo: argumento (oculto para evitar spoilers), momentos clave, Pokémon que aparecen, «¿Quién es ese Pokémon?» y curiosidades.
- Buscador por título y por etiquetas: Pokémon, personajes, lugares y momentos (capturas, evoluciones, gimnasios, concursos…).
- Progreso guardado en el navegador, medallas por temporada y un código para pasar el progreso a otro dispositivo.
- Pokédex con los 1025 Pokémon: tipos, estadísticas, debilidades, evoluciones, descripciones y los capítulos de Ash en los que aparece cada uno.

## Publicarla con GitHub Pages

Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main`, carpeta `/ (root)` → Save.
La web queda en `https://dcille.github.io/pokemonTV/` (puede tardar un par de minutos la primera vez).

En el iPhone: ábrela en Safari → Compartir → **Añadir a pantalla de inicio**.

## Contenido

| Ruta | Qué es |
| --- | --- |
| `index.html` | La página completa (estilos, datos de temporadas y lógica). |
| `info/s*.json` | Fichas de cada temporada; se cargan al abrir un capítulo. |
| `info/tags.json` | Etiquetas de todos los capítulos para el buscador. |
| `info/dex.json` | Datos de los 1025 Pokémon de la Pokédex. |
| `thumbs/s*.jpg` | Miniaturas oficiales, una imagen por temporada con todas sus miniaturas. |
| `icons/`, `manifest.webmanifest` | Icono y datos para instalarla como app. |

## Créditos

- Vídeos y miniaturas: canal oficial TV Pokémon en YouTube. La página solo los enlaza e inserta con el reproductor de YouTube.
- Imágenes de los Pokémon: [repositorio de sprites de PokeAPI](https://github.com/PokeAPI/sprites), enlazadas directamente.
- Títulos, argumentos, curiosidades, etiquetas y datos de la Pokédex: [WikiDex](https://www.wikidex.net/), con licencia [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.es).

Página hecha por fans, sin relación con The Pokémon Company ni con Nintendo.
