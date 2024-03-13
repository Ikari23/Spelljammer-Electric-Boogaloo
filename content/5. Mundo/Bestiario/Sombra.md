# Sombra
![sombra](https://5etools-mirror-1.github.io/img/bestiary/MM/Shadow.jpg)

Las sombras son muertos vivientes que parecen oscuras y desproporcionadas sombras humanoides.

**_Inclinaciones oscuras._** Las sombras surgen de la oscuridad para alimentarse de la vitalidad de las criaturas vivas. Son capaces de consumir a cualquier ser vivo, pero se sienten especialmente atraídas por criaturas que nunca han sido corrompidas por el mal. Una persona que lleva una vida pía y bondadosa confina sus instintos más bajos y sus tentaciones más fuertes a la oscuridad en la que moran las sombras. A medida que este muerto viviente consume la fuerza y el vigor de una víctima, su sombra se va volviendo más oscura y comienza a moverse por su cuenta. Al morir, la sombra de la víctima se libera y se transforma en una nueva y hambrienta sombra muerta viviente ávida de otras vidas que consumir.

Si por algún motivo esa criatura volviera a la vida, su sombra será consciente de ello. En estos casos, puede que la sombra busque a su "progenitor" para castigarle o asesinarle. Al margen de sí persigue o no a su contrapartida viva, la criatura de la que surgió no proyectará sombra alguna hasta que el monstruo sea destruido.

**_Muerto viviente._** Una sombra no necesita respirar, comer, beber ni dormir.

```statblock
name: Sombra
size: Muerto Viviente
type: Mediano
alignment: , caótico malvado
ac: 12
hp: 16
hit_dice: 3d8 + 3
speed: 40 pies
stats: [6, 14, 13, 6, 10, 8]
skillsaves:
  - Sigilo: 4
damage_vulnerabilities: radiante
damage_resistances: ácido, frío, relámpago, trueno; contundente, cortante y perforante de ataques no mágicos
damage_immunities: necrótico, veneno
condition_immunities: agarrado, apresado, asustado, cansancio, derribado, envenenado, paralizado, petrificado
senses: visión en la oscuridad 60 pies, Percepción pasiva 10
cr: 1/2
traits:
  - name: Amorfo
    desc: "La Sombra puede moverse a través de espacios de tan solo 1 pulgada de ancho sin apretarse."
  - name: Esconderse en las Sombras
    desc: "Mientras se encuentra bajo luz tenue o en oscuridad, el Sombra puede Esconderse usando una acción adicional."
  - name: Sensibilidad a la Luz Solar
    desc: "La Sombra tiene desventaja en las tiradas de ataque y las pruebas de Sabiduría (Percepción) que dependan de la vista hechas bajo la luz del sol."
actions:
  - name: Consumir Fuerza
    desc: "Ataque de conjuro cuerpo a cuerpo: +4 a impactar, alcance 5 pies, una criatura Impacto: 9 (2d6 + 2) de necrótico, y la puntuación de Fuerza del objetivo se reduce en 2 (1d4). Si su Fuerza se reduce a 0, morirá. De lo contrario, esta reducción permanece hasta que la criatura finaliza un descanso corto o largo. Si un humanoide no malvado muere a consecuencia de este ataque, una nueva sombra se alzará de su cadáver después de 2 (1d4) horas."
```
