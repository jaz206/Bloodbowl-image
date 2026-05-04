# Estructura recomendada de fotos de plantilla

## Estructura canonica nueva

La estructura correcta, a partir de ahora, es:

```text
Foto plantilla/
  <Team.name exacto de Firebase>/
    <Player.position exacto de Firebase>/
      00.png
      01.png
      02.png
```

## Convencion de nombres

- Carpeta de equipo: usa el nombre exacto del equipo en la BBDD
- Carpeta de posicion: usa el nombre exacto de la posicion en la BBDD
- Ficheros:
  - `00.png` = imagen generica
  - `01.png`, `02.png`, `03.png`... = variantes unicas

## Ejemplos

```text
Foto plantilla/
  Amazons/
    Eagle Warrior/
      00.png
      01.png
      02.png
    Jaguar Warrior/
      00.png
      01.png

  Dwarfs/
    Dwarf Blocker/
      00.png
      01.png
    Troll Slayer/
      00.png
```

## Compatibilidad temporal

La web sigue tolerando durante la migracion algunas carpetas legacy antiguas en espanol o con slugs.
Pero para fotos nuevas, usa siempre la estructura canonica nueva.

## Objetivo

Que la app pueda reconocer las fotos de inmediato sin depender de mappings especiales.
