# BiakFit · redes

Los posts de Instagram, preparados y pendientes de aprobación.

Está aquí y no en `biakfit-web` por dos razones: la web es el sitio de
verdad y no quiero que unas imágenes semanales anden cerca de algo que
puede romperla, y así las imágenes tienen URL pública para el día que la
programación se automatice.

## El flujo

1. **Sábado por la mañana** se prepara el lote de la semana siguiente:
   imágenes y textos.
2. Llega un **correo a biak@biakfit.com** con los tres posts: imagen,
   texto tal cual se publica, hashtags y el día y hora propuestos.
3. Beto contesta **ok** o dice qué cambiar.
4. Con el ok, los posts entran en **Buffer**.

## Días y horas

| Día | Hora | Suele ser |
|---|---|---|
| Lunes | 7:30 | El día que uno decide que esta semana sí |
| Miércoles | 19:00 | Después de trabajar |
| Sábado | 10:30 | Mañana sin prisa |

A los dos meses, con los datos de Buffer delante, se mueven. Hasta
entonces, fijos: tres bien puestos valen más que cinco irregulares.

## Cómo se hacen

Las imágenes **no se dibujan**: salen del propio material de la app.

- Los posts de ejercicio usan el dibujo del catálogo, su nombre y su
  primera clave técnica, ya traducidos.
- Los de texto son un titular en Baloo 2 sobre los colores de la marca, con
  Draki.

Todo sale de `tools/redes/lote_N.json` en el repositorio de la app, que es
la única fuente: de ahí salen las imágenes, el texto que se publica y el
correo. Se regenera con:

```bash
python3 tools/redes_lote.py 1
```

## El estilo

Está escrito en `docs/REDES.md` de la app. La regla que lo resume: **si un
post funcionaría igual de bien en la cuenta de cualquier otra app de
fitness, está mal escrito**.

Nunca un cuerpo como objetivo, nunca prisa, nunca culpa, nunca promesas de
resultados en X semanas, y Draki no regaña.

## Lotes

- [Lote 1](lote_1.md) — cuatro semanas, doce posts.
