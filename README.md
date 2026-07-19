# Entradas · Teatro Colón — Plano de Sala 3D

**Conocé tu ubicación antes de comprar la entrada.**

Visualización 3D interactiva de la sala principal del Teatro Colón (Buenos Aires): recorré la
herradura completa con sus 7 niveles, hacé clic en cualquier butaca y mirá el escenario en primera
persona desde esa ubicación exacta.

> [!NOTE]
> Proyecto educativo y sin fines comerciales. No es un sitio oficial del Teatro Colón ni vende
> entradas; el modelo es una aproximación procedural, no un plano técnico.

## Qué incluye

- **La sala a escala real**, construida desde las dimensiones publicadas: herradura de
  29,25 m × 32,65 m, 28 m de altura, boca de escenario de ~16,30 m, escenario de 35,25 × 34,50 m
  con pendiente de 3 cm/m y disco giratorio de 20,30 m, foso de orquesta, cúpula de Soldi y araña central.
- **Todas las secciones del plano de sala oficial**, nivel por nivel: Platea (filas 1–14 y 15–22),
  palcos bajos/balcón/altos (centro, central y laterales), Platea Balcón, Palco Cazuela, Cazuela,
  Tertulia, Galería, Paraíso y las ubicaciones de pie, con sus rangos oficiales de butacas
  impares/pares.
- **~2.150 butacas seleccionables** (renderizadas con instancing) con numeración impar/par.
- **Vista en primera persona desde cada butaca**, con distancia al escenario, altura, ángulo lateral
  y un **porcentaje de escenario visible** calculado geométricamente: se lanzan rayos desde el ojo
  del espectador contra parapetos, voladizos, muros del proscenio y telones del modelo.
- **Modos de cámara**: vista general orbitable, plano cenital (misma orientación que el PDF oficial),
  vista desde el escenario y corte por nivel.

## Cómo correrlo

```bash
npm install
npm run dev
```

Después abrí la dirección local que muestra Vite.

## Controles

| Acción                          | Control                                        |
| ------------------------------- | ---------------------------------------------- |
| Rotar alrededor de la sala      | Clic (o tacto) y arrastrar                     |
| Zoom                            | Rueda del mouse                                |
| Ver ficha de una butaca         | Clic en la butaca                              |
| Entrar a la vista de la butaca  | «Ver desde esta butaca» o el botón «Vista»     |
| Mirar alrededor desde la butaca | Arrastrar en la vista de butaca                |
| Salir de la butaca              | <kbd>Esc</kbd> o «← Salir de la butaca»        |
| Corte por nivel                 | Botones «Hasta nivel N» (arriba a la derecha)  |

## Fuentes

- [Plano de sala oficial del Teatro Colón (PDF)](https://teatrocolon.org.ar/files/colon/plano-sala-principal.pdf)
- [El Teatro — teatrocolon.org.ar](https://teatrocolon.org.ar/el-teatro/)
- [Teatro Colón en WikiArquitectura](https://es.wikiarquitectura.com/edificio/teatro-colon/)

Las proporciones generales, alturas y la distribución de secciones respetan esas fuentes; la
posición individual de cada butaca y la ornamentación son generadas proceduralmente.

## Créditos y licencia

Este proyecto está construido sobre la base y el concepto de vista-por-butaca de
**StadiView**, creado por **thebuggeddev** — copyright © 2026 thebuggeddev
([GitHub](https://github.com/thebuggeddev) · [X](https://x.com/thebuggeddev) ·
[thebuggeddev@gmail.com](mailto:thebuggeddev@gmail.com)).

Disponible bajo la [licencia PolyForm Noncommercial 1.0.0](LICENSE.md): podés estudiarlo,
compartirlo y adaptarlo para usos no comerciales conservando los avisos de copyright y licencia.
El uso comercial requiere una [licencia comercial aparte](COMMERCIAL-LICENSE.md). Las bibliotecas
de terceros mantienen sus propias licencias: ver [avisos de terceros](THIRD_PARTY_NOTICES.md).
