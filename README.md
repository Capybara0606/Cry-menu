# Cry menú

Beta en español para organizar los almuerzos de una persona durante siete días.

- Tabla de platillo, día, ingredientes y receta con cantidades por porción.
- Lista de compra calculada a partir de todas las recetas.
- Compra y platos preparados guardados en localStorage de este navegador.
- Copia o descarga de lista e impresión con recetas completas.
- Diseño adaptable a móvil; tabla desplazable horizontalmente.

## Probar

Sin instalación ni compilación. Abre `dist/index.html` o ejecuta:

```sh
python3 -m http.server 8080 --directory dist
```

Visita http://localhost:8080. No requiere claves ni servicios externos. Las fuentes de Google son opcionales: hay fuentes de sistema de respaldo.

## Publicar en GitHub Pages

El workflow incluido publica `dist/`. En Settings → Pages selecciona **GitHub Actions** como fuente; se despliega al subir cambios a `main` o al ejecutar el workflow manualmente.

## Alcance

Plan omnívoro general, sin personalización de alergias ni recomendaciones nutricionales individuales. Los pesos de cereales son en seco y los de legumbres, cocidos y escurridos. Los datos se guardan únicamente en el navegador y no se sincronizan entre dispositivos. Las cantidades de compra son las necesarias para las recetas; adapta los envases a lo disponible.
