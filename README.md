# News IA · RRHH

Resumen diario de noticias de IA en cuatro bloques, en este orden:

1. **España** — IA e innovación.
2. **Europa** — IA y regulación europea.
3. **Mundo** — grandes novedades globales.
4. **RRHH** — IA y tecnología que impactan en recursos humanos.

## Cómo funciona hoy

Una rutina de Claude Code ("Noticias IA España + RRHH (diario)") se ejecuta cada día a las 9:55 (Europe/Madrid):
busca las noticias, actualiza la página [Radar IA diario](https://claude.ai/artifact/7JZ1gGea5F7HWZmyQJ95M4)
y envía un push a la app de Claude con el enlace.

## Contenido

- `plantillas/radar-ia.html` — plantilla de la página diaria. El contenido del día va entre `<!-- NOTICIAS:INICIO -->` y `<!-- NOTICIAS:FIN -->`.
- `plantillas/correo.html` — prototipo del correo (estilos en línea, para clientes de email). Pendiente de usar.
- `resumenes/AAAA-MM-DD.md` — histórico de resúmenes.

## Pendiente

- Guardar el histórico diario aquí y enviar el correo (vía GitHub Actions).
