# Accord

Aplicación web de aprendizaje musical. **Traste** es la primera ruta, dedicada a la guitarra para principiantes.

La ruta incluye cinco lecciones en español, afinador, tablatura, ejercicios a tempo ajustable y una pieza original. Se puede practicar con notas individuales mediante el micrófono o con los botones en pantalla. El progreso se guarda en el navegador.

## Ejecutar en local

Desde la raíz del repositorio, con Python 3:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Abre [http://localhost:8000](http://localhost:8000). El micrófono requiere permiso del navegador y un origen seguro, como localhost o un sitio HTTPS. El audio se analiza en el dispositivo.

## En desarrollo

Accord es el nombre común para las futuras rutas. Piano, ukelele, armónica y la traducción a otros idiomas forman parte de la dirección del proyecto. La versión actual incluye la ruta Traste en español.

## Grabaciones de guitarra

El afinador y los ejercicios reproducen diez notas de guitarra clásica de nailon tocadas con los dedos, una grabación por cada posición utilizada. Proceden de [Meta Nylon Guitar, de Meta Open Sound](https://github.com/facebookincubator/Meta-open-sound/tree/main/systems/instruments/meta-nylon-guitar), bajo [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Los archivos originales en formato Ogg se distribuyen en `audio/` con nombres que indican cuerda y traste.
