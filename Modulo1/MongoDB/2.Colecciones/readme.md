
# Colecciones

Se puede crear una colección, dando click en el botón + 

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/3.png)

Ingresar los campos requeridos: Nombre de la colección y se presiona el botón Create Collection.

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/3.1.png)

Se crea la colección top_music

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/4.png)

- - -


## Opciones para insertar de documentos a una colección



- [x] Cargar un documento ( uno por uno )

1. >Seleccionar la opción Insert document

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/9.png)

2. >Ingresar datos, manteniendo la estructura JSON, para guardar presionar el botón Insert.

```other
{
  "_id": {
    "$oid": "6494c137f8dee4e4a31313a2"
  },
  "title": "Flowers",
  "artist": "Miley Cyrus",
  "top_genre": "pop",
  "energy": 90,
  "danceability": 73,
  "duration": 200,
  "popularity": 98,
  "bpm":2
}
```

![Imagen](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/10.png)

3. >Presiona el botón Insert, enseguida se agregará un nuevo documento a la coleccion.

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/11.png)

_ _ _

- [x]  Cargar documentos de forma masiva a una colección


Para cargar varios documentos en una colección se puede utilizar la importación por medio de un documento CSV o JSON. En este ejemplo cargamos la información a través de una documento CSV.

> 1. *Dar click en el botón ADD DATA*
> 2. *Seleccionar el tipo*
> 3. *Seleccionar documento de datos*
> 4. *Presionar importar*

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/5.png)

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/6.png)

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/7.png)

Una vez realizados los pasos anteriores, se cargarán los datos en la colección

![Image.png](https://github.com/angelesbrrls/cienciasdedatos/blob/main/Modulo1/MongoDB/assets/8.png)


_ _ _


[Anterior](https://github.com/angelesbrrls/cienciasdedatos/tree/main/Modulo1/MongoDB/1.Base%20de%20datos) | [Siguiente](https://github.com/angelesbrrls/cienciasdedatos/tree/main/Modulo1/MongoDB/3.Operaciones)