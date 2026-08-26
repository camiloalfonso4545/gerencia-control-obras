# La ruta del semestre

Mapa navegable del curso **Gerencia y Control de Obras** — Ingeniería Civil, UPTC,
período 2026-II.

Cada clase es una parada sobre una vía: al acercarse aparecen el tema, el resumen
de lo visto, por qué importa y el material de apoyo descargable de esa sesión.

**Página publicada:** https://camiloalfonso4545.github.io/gerencia-control-obras/

## Cómo se usa

- **Vista libre** — arrastre para moverse por el mapa, rueda del mouse para acercar.
- **Recorrido guiado** — las flechas llevan de una clase a la siguiente y encuadran
  cada parada completa.
- **Ajustar** — devuelve la vista a la ruta entera.

## Estructura

```
index.html      la página completa: estructura, estilos y lógica en un solo archivo
recursos/       los archivos que los estudiantes descargan desde la página
```

## Cómo se actualiza

El contenido de las clases vive en la constante `CLASES`, al comienzo del bloque
`<script>` de `index.html`. Cada clase es un objeto; agregar una es agregar un
elemento al arreglo, y la vía, las señales y los conectores se recalculan solos.

El globo de material de apoyo solo aparece si la clase declara `recursos`, y cada
archivo listado debe existir de verdad dentro de `recursos/`.

---

Texto base del curso: Guía del PMBOK® 8.ª edición (PMI, 2025).
Docente responsable: Jorge Andrés Sarmiento Rojas.
