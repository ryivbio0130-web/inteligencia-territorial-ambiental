# Instalación de la Wiki en GitHub

## Opción A: GitHub Wiki
1. Crear el repositorio del proyecto.
2. Confirmar que la función Wiki esté habilitada y disponible en el plan del repositorio.
3. Crear la página `Home` y luego las páginas con los títulos indicados en cada archivo `.md`, o clonar el repositorio Git de la Wiki y copiar los `.md`.
4. **Los archivos Excel deben alojarse en el repositorio principal**, preferiblemente en `docs/anexos/`; sustituir sus enlaces en las páginas por URLs al repositorio, ya que la Wiki y el repositorio principal son almacenes distintos.
5. Verificar que los enlaces entre páginas y los diagramas Mermaid funcionen.

## Opción B: documentación en repositorio privado (sin GitHub Wiki)
1. Crear `docs/` y copiar allí los archivos `.md` y `.xlsx`.
2. Cambiar los enlaces internos `(...Nombre-de-Pagina)` por `(...Nombre-de-Pagina.md)` en el repositorio si no resuelven automáticamente.
3. Usar `Home.md` como índice o vincularlo desde el README principal.

## Publicación responsable
No incluir tokens API, contraseñas, coordenadas sensibles ni datos restringidos. No afirmar que las pruebas se ejecutaron si no existen logs o archivos de salida.
