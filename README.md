# Pokedex API

Este proyecto es una implementación de una API de MuleSoft que interactúa con PokeAPI para obtener información sobre Pokémon. Utiliza MuleSoft para la integración y gestión de API, y está documentado con RAML.

## Descripción del Proyecto

- **MuleSoft:** Herramienta de integración y gestión de API.
- **PokeAPI:** Fuente de datos de información sobre Pokémon.
- **RAML:** Lenguaje de modelado RESTful utilizado para documentar la API.

## Contenido del Proyecto

- **RAML:** Archivo `pokedex-api.raml` que define la estructura y los endpoints de la API.
- **Flujo MuleSoft:** `pokedexFlow.xml` que contiene la lógica de integración y manejo de solicitudes.
- **Configuración Maven:** `pom.xml` para la gestión de dependencias.

## Ejecución

Para ejecutar el proyecto, importa el proyecto en Anypoint Studio, actualiza las dependencias de Maven y ejecuta el flujo. La API estará disponible en `http://localhost:8081/pokedex/api/{id}` o `http://localhost:8081/pokedex/api?name={name}`.

## Herramientas Utilizadas

- **MuleSoft Anypoint Studio:** Plataforma de integración y desarrollo.
- **Maven:** Herramienta de gestión de proyectos y dependencias.
- **Java 8 o superior:** Requisito para ejecutar MuleSoft.


## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.
