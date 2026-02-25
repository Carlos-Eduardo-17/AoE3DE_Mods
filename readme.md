## Descripción

Repositorio dedicado a mods para Age of Empires 3 Definitive Edition.

## Mods

1. Mod Realista:

- Armas de fuego tardan entre 15 (para mosquetes) y 30 segundos (para fusiles).
- PENDIENTE:
  - Determinar tipos de armas que cada soldado lleva para asignar un Rof consistente.
  - Definir Rof de artillería.
  - Infantería y caballería solo asedian establecimientos de madera.
  - Solo artillería puede atacar edificios de piedra.
- CLAVE:
  - Editar los flags (etiquetas) de cada unidad para identificarlos mejor y luego aplicar Rof genérico.
  - Subir costes de suministros y tiempo para subir de edad con el fin de tener que crear militares en cada edad.
  - Ordenar tecnologías de cada civilización en el archivo techtree.xml para luego aplicar cambios desde un techtreemods.xml
- MEJORA: Reacomodar unidades por edad, algo parecido a:
  - Edad de la Exploración
    - Arcos (con 6 de Rof), arcos largos (con 6 de Rof), ballestas (de estribo, con 9 de Rof) y cañones de mano y/o espingarda (con 30 de Rof).
    - Caballería solo puede usar arco (con 8 de Rof).
  - Edad del Comercio
    - Arcabuz de mecha (con 30 de Rof), arcos largos (con 6 de Rof), ballestas pesadas (de torno, con 15 de Rof).
    - Caballería limitada usaría arcabuz (con 40 de Rof)
  - Edad de las Fortalezas
    - Mosquete de pedernal (de llava de chispa, con 15 de Rof), fusileros primitivos limitado (como jaeger, ranger, con rof de 30)
    - Caballería usaría mosquetón (con 20 de Rof) y/o pistolas de pedernal o rueda (con 15 de Rof)
  - Edad Industrial
    - Fusil de percusión (con 15 de Rof), tiradores espcializados (con rof de 20)
    - Caballería limitada usaría carabina de percusión (con 20 de Rof)
  - Edad Imperial
    - Armas de repetición (primero hay que identificar animaciones de unidades, por ejemplo: bandidos, forajidos, etc), francotiradores (con Rof a definir)
    - Caballería con armas de repetición (primero hay que identificar animaciones de unidades, por ejemplo: bandidos, forajidos, etc)
- EVOLUCIONES
  - Arquero → arcabucero → mosquetero → fusilero → infantería
  - Arquero de tiro largo → Arquero de tiro largo → fusilero primitivo → tirador especializado → francotirador
  - ballestero ligero → Ballestero pesado → mosquetero → fusilero → infantería
  - cañonero de mano → arcabucero → mosquetero → fusilero → infantería (o podría irse por una ruta de granadero)

* Las unidades podrían mejorarse desde base → veterano → guardia → imperial o real en una sola edad.
* Al Pasar de edad, desde Arsenal se pueden investigar mejoras para evolucionar unidades a base de su siguiente edad. Por ejemplo: Arqueros (pueden estar en veterano o cualquier nivel) a arcabuceros base.
