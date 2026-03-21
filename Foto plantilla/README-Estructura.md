# Estructura recomendada de fotos de plantilla

- Usa una carpeta por raza.
- Dentro, usa una carpeta por posicion.
- Dentro de cada posicion, nombra las imagenes como `01.png`, `02.png`, `03.png`...

Ejemplo:

```
Foto plantilla/
  Orcos/
    blitzer-orco/
      01.png
      02.png
    untrained-troll/
      01.png
      02.png
```

La app intenta primero esta estructura nueva por carpetas.
Si no encuentra imagen, hace fallback al sistema antiguo por nombre plano.
