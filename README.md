# Hekatan OpenSees Web

Vista previa web de **Hekatan OpenSees**: la misma interfaz (menús que insertan comandos, ejemplos, editor y reporte)
con los **informes ya calculados** de cada ejemplo.

- **Ver:** <https://giorgioburbanelli89.github.io/hekatan-opensees-web/>
- Menú **Ejemplos** → voladizo, pórticos, muros, galpón, taludes, **Cimentaciones y suelo-estructura** y un **tutorial para crear un ejemplo nuevo**.
- Los menús Modelo, Materiales, Elementos, Cargas, Análisis, Gráficas y Resultados insertan los comandos de OpenSees en el editor.

## Vídeos

Serie de 8 vídeos (menos de 90 s, subtítulos ES/EN): <https://github.com/GiorgioBurbanelli89/hekatan-opensees-web/releases/tag/videos-v1>

## Alcance

La web **no calcula en vivo**: el motor de OpenSees no se redistribuye. Los informes se generaron con la app de escritorio
(<https://github.com/GiorgioBurbanelli89/hekatan-opensees-wpf>), cuyo AutoRun recalcula al escribir y que puede **Corroborar**
los valores contra el `OpenSees.exe` oficial. Si editas un script en la web, se avisa que el informe mostrado es el del ejemplo original.

## Créditos

Solver de Massimo Petracca y Guido Camata sobre OpenSees (UC Berkeley, PEER). Interfaz y reportes: Hekatan Engineers (MIT).
