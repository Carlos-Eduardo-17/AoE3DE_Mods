## Descripción

Repositorio dedicado a mods para Age of Empires 3 Definitive Edition.

## Mods

1. Mod Realista de Tiempo de Disparo (Rate of Fire) y asedio exclusivo:

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
    - Milicianos con lanzas
  - Edad del Comercio
    - Arcabuz de mecha (con 30 de Rof), arcos largos (con 6 de Rof), ballestas pesadas (de torno, con 15 de Rof).
    - Caballería limitada usaría arcabuz (con 40 de Rof)
    - Milicianos con lanzas
  - Edad de las Fortalezas
    - Mosquete de pedernal (de llava de chispa, con 15 de Rof), fusileros primitivos limitado (como jaeger, ranger, con rof de 30)
    - Caballería usaría mosquetón (con 20 de Rof) y/o pistolas de pedernal o rueda (con 15 de Rof)
    - Milicianos con mosquetes
  - Edad Industrial
    - Fusil de percusión (con 15 de Rof), tiradores espcializados (con rof de 20)
    - Caballería limitada usaría carabina de percusión (con 20 de Rof)
    - Milicianos con mosquetes
  - Edad Imperial
    - Armas de repetición (primero hay que identificar animaciones de unidades, por ejemplo: bandidos, forajidos, etc), francotiradores (con Rof a definir)
    - Caballería con armas de repetición (primero hay que identificar animaciones de unidades, por ejemplo: bandidos, forajidos, etc)
    - Milicianos con revólver (sí, la peace maker)
- EVOLUCIONES
  - Arquero → arcabucero → mosquetero → fusilero → infantería
  - Arquero de tiro largo → Arquero de tiro largo → fusilero primitivo → tirador especializado → francotirador
  - ballestero ligero → Ballestero pesado → mosquetero → fusilero → infantería
  - cañonero de mano → arcabucero → mosquetero → fusilero → infantería (o podría irse por una ruta de granadero)

* Las unidades podrían mejorarse desde base → veterano → guardia → imperial o real en una sola edad.
* Al Pasar de edad, desde Arsenal se pueden investigar mejoras para evolucionar unidades a base de su siguiente edad. Por ejemplo: Arqueros (pueden estar en veterano o cualquier nivel) a arcabuceros base.

2. Mod Recursos Extra

- Un intento vil de copiar al sistema de inventario de Stronghold.
- En el mercado se podría comprar y vender: madera procesada, metal para producción, pólvora.
- Una construcción parecida a una hacienda puede producir arcos, culatas de ballesta, culatas de arcabuz, mosquete y fusil, lanzas de madera, mangos para armas cuerpo a cuerpo, varillas para flechas, tablones para escudos y bases de artilleria, ruedas para artillería. Y en temas de metal: palas para ballesta, sistemas de disparo, cañones primitivos para espingarda y/o arcabuz, puntas de flecha, puntas de lanza, puntas de alabarda, hojas de espada, hojas de hacha, armaduras de metal, cañones primitivos para falconetes y bombardas, cascos de metal.
- Una construcción parecida a una fábrica produciría piezas de metal más avanzadas.
- Generar una unidad no solo costaría comida, monedas y/o madera, sino también recursos generados en los edificios mencionados.

3. Mod Munición Realista

- Cada unidad a distancia, llevaría una barra adicional a la de vida para indicar su munición.
- Sacar provecho al depósito de suministro (edificio que tendría un aura parecido al hospital de campaña pero que recargaría la barra de munición)
- Sacar provecho a las carretas de suministro (como carreta de centro urbano, unidad móvil que tendría un aura parecido al sacerdote pero que recargaría la barra de munición).
- La munición del depósito y de las carretas serían ilimitadas hasta destruirlas.

4. Mod Héroes

- En centro urbano se puede crear héroes según la civ y la edad (parecido al shogunato de los japoneses).
- Ó el Explorador puede ser reemplazado por un héroe según la civ y la edad (evolucionaría con cada edad).
- Los héroes tiene auras (así como los héroes japoneses)

5. Mod caballería

- Se necesitan criar cabaños en un establo, se crearían como se crean las cabras.
- Los caballos se llevaría al mercado para ser entrenados (consumidos como las cabras con los etiopes) y aumentaría la cantidad de caballos disponibles.
- Cada unidad militar de caballería costaría un caballo aparte de otros suministros.

6. Mod de comida:

- Las unidades sufren un pequeño daño cada minuto si no se acercan al mercado o a una carreta de suministros para comer (sería como el hospital de campaña y un sacerdote).
- Fuerza a las unidades a no estar alejadas de la base por mucho tiempo a menos de llevar una carreta de suministros.

7. Mod de área de construcción:

- Restriccion de construccion dentro del aura de un centro urbano.
- Cada centro urbano tardaría bastante en construirse y necesitaría muchos recursos (evitando explayarse rápidamente por todo el mapa.)
- Se anulan o se penalizan las carretas de regalo de la metropoli.

8. Murallas realistas:

- No se puede disparar ni atacar si hay una muralla en medio.
- La construccion de murallas de piedra sería limitada.
- Solo podrían atacar los destacamentos, centros urbanos, monitores y fuertes

9. Formaciones más útiles para unidades a distancia:

- Primera formación (volleyrangedattack)
  - Alcance corto, rof un poco lento (nervios), daño aumentado.
- Segunda formación (staggerrangedattack)
  - Alcance normal, rof normal, daño normal
- Tercera (en sí cuarta y quinta) formación
  - Alcance aumentado, rof un poco más rápido (calma por distancia), daño disminuido (mayor probabilidad de "fallar").

10. Sistema de acierto:

- Así como los monjes japoneses tienen una tasa de críticos, las unidades a distancia podrían tenerla.
- si se combina con el mod 9, el daño sería el mismo pero las problabilidades cambiarían (de mayor a menor)
- Se tendría un daño base (el menor posible) y un daño crítico.
- Evoluciones del mod 1 mejorarían la tasa de acierto.
