# Guía de contribución

Este repositorio es contenido didáctico, no un proyecto de software tradicional. Las contribuciones más valiosas son las que mejoran la comprensión del material.

## Tipos de contribución

| Tipo | Cómo |
|---|---|
| Corrección conceptual o de código | Pull Request |
| Mejora o ampliación de una explicación | Pull Request |
| Error detectado en un notebook | Issue |
| Duda sobre el contenido | Issue con etiqueta `question` |
| Sugerencia de tema nuevo | Issue con etiqueta `enhancement` |

## Proceso para una Pull Request

1. Haz fork del repositorio
2. Crea una rama descriptiva: `fix/nombre-leccion` o `improve/nombre-seccion`
3. Realiza los cambios en el notebook o archivo correspondiente
4. Abre la PR describiendo qué cambia y por qué

## Criterios de calidad

- El contenido debe ser correcto y verificable
- Las explicaciones deben seguir el tono práctico del curso (conceptos aplicados, no teoría exhaustiva)
- Los notebooks deben ejecutarse sin errores con las dependencias del `pyproject.toml`
- No se aceptan cambios puramente estéticos sin justificación

## Lo que no se acepta

- Añadir dependencias sin justificación clara
- Cambios en el índice o estructura del curso sin discusión previa en un issue
- Contenido que se solape significativamente con lecciones existentes
