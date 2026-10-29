# Relleu 3D → STL

Eina web per triar una zona del món i descarregar un STL del seu relleu, llest per imprimir en 3D.
Tot s'executa al navegador: no hi ha servidor ni claus d'API.

## Ús
1. Cerca un lloc o navega pel mapa.
2. Dibuixa un rectangle sobre la zona.
3. Ajusta mida, exageració vertical, base i resolució.
4. Genera i descarrega `relleu.stl`.

## Publicar-ho amb GitHub Pages
Puja `index.html` al repositori → *Settings* → *Pages* → *Deploy from a branch* → `main` / `(root)`.

## Crèdits i dades
- Elevació: [Terrain Tiles](https://registry.opendata.aws/terrain-tiles/) (AWS Open Data; SRTM, ASTER, LiDAR nacionals i altres fonts).
- Mapa base: © [OpenTopoMap](https://opentopomap.org) (CC-BY-SA), © col·laboradors d'[OpenStreetMap](https://www.openstreetmap.org/copyright).
- Cerca: [Nominatim](https://nominatim.org). Respecta'n la [política d'ús](https://operations.osmfoundation.org/policies/nominatim/).
- Previsualització 3D: [three.js](https://threejs.org) (MIT).
- Mapes: [Leaflet](https://leafletjs.com).
