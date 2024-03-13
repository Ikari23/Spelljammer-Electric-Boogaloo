# Giff
![Giff](https://5etools-mirror-1.github.io/img/bestiary/MPMM/Giff.webp)

Es fácil detectar a los giffs en una habitación: estos fornidos personajes miden 7 pies y tienen cabeza de hipopótamo. En el [[Espacio Salvaje]] y los puertos asociados, los giffs se encuentran más a menudo como mercenarios espaciales. Estas tropas son famosas por su entrenamiento marcial y su afición a los explosivos, y suelen ir armados con relucientes pistolas y mosquetes. Este perfil representa a uno de estos mercenarios.

Todos los aspectos de la sociedad de estos giffs espaciales están organizados según criterios militares. Desde el nacimiento hasta la muerte, cada uno tiene un rango militar. Los ascensos no dependen de la edad, sino que son concedidos por un superior como premio al valor.

Los mosquetes y las granadas son las especialidades de muchos regimientos de giffs. Cuanto más grande sea la explosión, más brillante sea el destello y más espeso el humo que produzca, mayor será la gloria para el que empuña el arma. Se sabe que los mercenarios giff aceptan la paga en barriles de pólvora en lugar de oro, gemas u otra moneda.

```statblock
name: Giff
size: Humanoide
type: Mediano
alignment: , cualquier alineamiento
ac: 16 (coraza)
hp: 60
hit_dice: 8d8 + 24
speed: 30 pies
stats: [18, 14, 17, 11, 12, 12]
senses: Percepción pasiva 11
languages: Común
cr: 3
traits:
  - name: Carga de Cabeza
    desc: "El Giff puede intentar derribar a una criatura; si el Giff se mueve al menos 20 pies en una línea recta que termina a 5 pies de una criatura Grande o más pequeña, esa criatura debe tener éxito en una tirada de salvación de Fuerza CD 14 o recibirá 7 (2d6) de daño contundente y será derribada."
  - name: Conocimiento de Armas de Fuego
    desc: "El dominio del Giff de sus armas le permite ignorar la propiedad de carga de mosquetes y pistolas."
actions:
  - name: Ataque múltiple
    desc: "El Giff realiza dos ataques con su espada larga, su mosquete o su pistola."
  - name: Espada larga
    desc: "Ataque con arma cuerpo a cuerpo: +6 a impactar, alcance 5 pies, un objetivo. Impacto: 8 (1d8 + 4) de daño cortante, o 9 (1d10 + 4) de daño cortante si se usa a dos manos."
  - name: Mosquete
    desc: "El GAtaque de arma a distancia: +4 a impactar, alcance 40/120 pies, un objetivo. Impacto: 8 (1d12 + 2) de daño perforante."
  - name: Pistola
    desc: "El Giff reAtaque de arma a distancia: +4 a impactar, alcance 30/90 pies, un objetivo. Impacto: 7 (1d10 + 2) de daño perforante."
  - name: Granada de fragmentación (1/día)
    desc: El Giff lanza una granada hasta 60 pies. Cada criatura a 20 pies de la detonación de la granada debe realizar una tirada de salvación de Destreza CD 15, lo que inflige 17 (5d6) de daño perforante si falla, o la mitad de ese daño con un éxito."
```

Los compañeros de los giffs, que constituyen el grueso de la tripulación de la mayoría de los buques giff, son marineros disciplinados.

```statblock
name: Compañero Giff
size: Humanoide
type: Mediano
alignment: , cualquier alineamiento
ac: 12
hp: 75
hit_dice: 10d8 + 30
speed: 30 pies, nadar 30 pies
stats: [18, 14, 17, 11, 12, 12]
senses: Percepción pasiva 11
languages: Común
cr: 3
traits:
  - name: Firmeza del Camino
    desc: "En la cubierta de un barco, el giff tiene Ventaja en las Pruebas de Característica y en las Tiradas de Salvación realizadas contra efectos que le dejarían Derribado o le empujarían por la borda."
  - name: Conocimiento de Armas de Fuego
    desc: "El dominio del Giff de sus armas le permite ignorar la propiedad de carga de mosquetes y pistolas."
actions:
  - name: Ataque múltiple
    desc: "El Giff realiza dos ataques con su espada larga, su mosquete."
  - name: Espada larga
    desc: "Ataque con arma cuerpo a cuerpo: +6 a impactar, alcance 5 pies, un objetivo. Impacto: 8 (1d8 + 4) de daño cortante, o 9 (1d10 + 4) de daño cortante si se usa a dos manos."
  - name: Mosquete
    desc: "Ataque con arma a distancia: +4 a impactar, alcance 40/120 pies, un objetivo. Impacto: 8 (1d12 + 2) de daño perforante."
  - name: Granada de fuerza
    desc: "El Giff lanza una granada hasta 60 pies. Cada criatura a 20 pies de la detonación de la granada debe realizar una tirada de salvación de Destreza CD 15, lo que inflige 17 (5d6) de daño de fuerza si falla, o la mitad de ese daño con un éxito. Despoués de que el giff lance la granada, tira un d6: con un resultado de 4 o menos, al giff no le quedan más grandas."
```