# República Dominicana GEOJSON

## GEOJSON
Es un formado que contiene datos GeoEspacial, de lo cual, podemos utilizar para representar dichos datos en un mapa Cartografico. La estructura que este posee es de tipo *JSON* -> "JavaScript Object Notation", esta representando por *KEY* y *VALUE*.

```
{
  key: "value",
  key1: "value1",
  key2: "value2"
}
```
Esta metodologia nos ayuda bastante, dado que podemos representar los datos MUNDI es con estas caracteristicas, que a su vez, representaremos unicamente el de la *Republica Dominicana*.

## Example
### Tabla


| object | codigoProvincia | Provincias | geometry | CualquierOtroValor1 | CualquierOtroValor2 |
|---|---|---|---|---|---|
| 01 | 01 | Distrito Nacional |MULTIPOLYGON[[-69.97480276199997, 18.545267730000035], [-69.97461923299994, 18.545253203000073], ...]] | 25 | 100
```
{
  "type": "FeatureCollection",
  "feature": [
            {
              "id": "0",
              "type": "Feature",
              "properties": {
                    "object": "01",
                    "codigoProvincia" : "01"
                    "Provincias": "Distrito Nacional",
                    "geometry": {
                              "type": "MultiPolygon",
                              "coordinates": [[[[-69.97480276199997, 18.545267730000035], [-69.97461923299994, 18.545253203000073],
                                                [-69.97430012599995, 18.54526127500003],  [-69.97404817999995, 18.545279595000068],
                                                [-69.97370266199994, 18.545317545000046], [-69.97347992699997, 18.54535878400003],
                                                [-69.97261315199995, 18.54564741100006],  [-69.97225842099994, 18.545781919000035],
                                                [-69.97203887699999, 18.545783049000022], [-69.97196703199995, 18.54575545800003],
                                                [-69.97184040599996, 18.545658761000027], [-69.97176789099996, 18.54553452400006],
                                                [-69.97175854299996, 18.54547235700005],  [-69.97175354499996, 18.545439117000058],
                                                [-69.97179414599998, 18.545294042000023], [-69.97189017999995, 18.54518489700007],
                                                [-69.97212734399994, 18.54500588600007],  [-69.97221639999998, 18.544883608000077],
                                                [-69.97222259499995, 18.54475846500003],  [-69.97219566599995, 18.544636594000053],
                                                [-69.97219385999995, 18.544629758000042]]],
                            "CualquierOtroValor1": ["DATOS NUMERICOS"],
                            "CualquierOtroValor2": ["DATOS NUMERICOS"]
                    }
              }
            }
  ]
}
```
## Mapa de la República Dominicana - [GEOJSON](https://github.com/jeancharlyjs/RepublicaDominicana-GEOJSON/blob/main/Republica%20Dominicana/geojson/DominicanRepublic.geojson)
![República Dominicana - Mapa](https://github.com/jeancharlyjs/RepublicaDominicana-GEOJSON/blob/main/imagenes/MapRepDominicana.png)

## Mapa Provincial de la República Dominicana - [GEOJSON]
![San Juan - Provincia - Mapa](https://github.com/jeancharlyjs/RepublicaDominicana-GEOJSON/blob/main/imagenes/San%20Juan%20-%20Provincia.png)
