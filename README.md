# Senda

Asistente de misiones para **World of Warcraft: Legion 7.3.5** (cliente 7.3.5).
Marca en el mapa y en el minimapa quién da misiones (!), dónde se entregan (?)
y dónde están los objetivos, de nivel 1 a 110.

![Iconos de objetivo](docs/iconos.png)

## Descargar e instalar

1. Baja **[Senda-0.11.1-addon.zip](https://github.com/Tukitaaa/Senda/raw/main/descargas/Senda-0.11.1-addon.zip)**.
2. Descomprímelo en `World of Warcraft\Interface\AddOns\` (debe quedar la carpeta `AddOns\Senda`).
3. Si el juego estaba abierto, ciérralo del todo y vuelve a abrirlo.

## Opciones

Todo se configura desde **Interfaz > Accesorios > Senda** o con el **botón de Senda en el minimapa** (clic izquierdo: opciones, clic derecho: mostrar/ocultar iconos, arrastrar para moverlo).

## Comandos

| Comando | Qué hace |
|---|---|
| `/senda opciones` | Abre el panel de opciones |
| `/senda boton` | Muestra u oculta el botón del minimapa |
| `/senda` | Activa o desactiva los pines |
| `/senda disponibles`, `entregas`, `objetivos` | Muestra u oculta cada tipo de pin |
| `/senda grises` | Muestra las misiones de nivel bajo |
| `/senda iconos` | Iconos de Senda o los clásicos |
| `/senda minimapa` | Pines en el minimapa |
| `/senda pendientes` | Muestra también el "?" de misiones sin terminar |
| `/senda compartir` | Compartir lo que aprendes (grupo, hermandad, amigos y otros con Senda) |
| `/senda archivo` | Dónde está tu archivo de datos |
| `/senda info` | Estado de la base de datos |

## Ayuda a mejorarlo

Senda aprende mientras juegas: quién da cada misión, dónde se entrega y qué
bichos sirven. Si [mandas tu archivo de datos](../../issues/new?template=aporte.yml),
lo que aprendió tu addon llega a todos en la siguiente versión.

Senda también comparte en vivo lo que aprende (solo posiciones de PNJ, objetos
y misiones, nada personal) con otros jugadores que usan Senda. Se apaga en el
panel de opciones o con `/senda compartir`.

## Licencia

(c) 2026 Tzors. Todos los derechos reservados. Puedes usar Senda en tu juego,
pero no copiarlo, modificarlo ni publicarlo sin permiso. Detalles en [LICENSE](LICENSE).

Los datos de misiones (carpeta `Data/Zones` del addon) vienen de
[TrinityCore](https://www.trinitycore.org) y mantienen su licencia GNU GPL v2.
World of Warcraft es una marca de Blizzard Entertainment, Inc. Senda no está
afiliado ni respaldado por Blizzard.
