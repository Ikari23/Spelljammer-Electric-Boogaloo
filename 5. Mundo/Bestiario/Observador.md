# Observador

![](https://o.remove.bg/downloads/92410674-53b4-46e9-a24c-30a1ff0419eb/image-removebg-preview.png)

Un observador es una manifestación a pequeña escala de los sueños de un contemplador. Se asemeja al contemplador que le dio vida, pero su cuerpo mide solo 8 pulgadas de ancho y tiene únicamente cuatro apéndices oculares. Sigue a su creador como un cachorro agresivo y, en ocasiones, forma pequeños grupos que patrullan la guarida de su amo en busca de alimañas que matar y criaturas solitarias que acosar.

Los observadores no hablan ningún idioma, pero pueden imitar las palabras y frases que escuchan, repitiéndolas con voz aguda y tono burlón. A los contempladores les entretiene observar a estos pequeños seres, por lo que toleran su presencia como mascotas malcriadas. Algunos contempladores insisten a sus magos esbirros para que tengan un observador como familiar, ya que son capaces de ver a través de los ojos de estas criaturas.

Los observadores salvajes (es decir, que no viven con un contemplador) son territoriales, se alimentan de insectos y animales pequeños y son conocidos por jugar con la comida. Un observador salvaje solitario evita los enfrentamientos con criaturas Medianas o más grandes, pero un grupo de ellos podría enfrentarse a presas de mayor tamaño. Algunos observadores siguen a quienes se adentran en su territorio, incordiándolos sin cesar e imitando ruidosamente lo que dicen, pero los dejan tranquilos si se van de la zona y huyen de cualquier cosa a la que no puedan matar.


```statblock
name: Observador
size: Aberración
type: Diminuto
subtype: (Contemplador),
alignment: neutral malvado
ac: 13
hp: 13
hit_dice: 3d4 + 6
speed: 0 pies, volar 30 pies (levitar)
stats: [3, 17, 14, 3, 10, 7]
saves:
  - Sab: 2
skillsaves:
  - Percepción: 4
  - Sigilo: 5
condition_immunities: Derribado
senses: visión en la oscuridad 60 pies, Percepción pasiva 14
languages: -
cr: 1/2
traits:
  - name: Imitación
    desc: El contemplador puede imitar sonidos de voz sencillos que haya oído previamente, en cualquier idioma. Cualquier criatura que oiga estos sonidos se dará cuenta de que son imitaciones si supera una prueba de Sabiduría (Perspicacia) CD 10.
actions:
  - name: Mordisco
    desc: Ataque con arma cuerpo a cuerpo: +5 a impactar, alcance 5 pies, un objetivo. Impacto: 1 de daño perforante.
  - name: Rayos oculares
    desc: "El observador dispara dos de los siguientes rayos oculares mágicos al azar (tira 2d4 y repite los duplicados) contra una o dos criaturas a las que pueda ver a 60 pies o menos de él: 1: Rayo ofuscador. La criatura objetivo deberá superar una tirada de salvación de Sabiduría con CD 12 o quedará hechizada hasta el principio del siguiente turno del observador. Mientras el objetivo esté hechizado por este efecto, su velocidad se reduce a la mitad y tiene desventaja en las tiradas de ataque. 2: Rayo aterrador. La criatura objetivo deberá superar una tirada de salvación de Sabiduría con CD 12 o quedará asustada hasta el principio del siguiente turno del observador. 3: Rayo escarchado. El objetivo deberá superar una tirada de salvación de Destreza con CD 12 o sufrirá 10 (3d6) de daño de frío. 4: Rayo telequinético. Si el objetivo es una criatura Mediana o más pequeña, deberá superar una tirada de salvación de Fuerza con CD 12 o será alejada hasta 30 pies de distancia del observador. Si el objetivo es un objeto Diminuto que no lleve o vista nadie, el observador lo moverá hasta 30 pies en cualquier dirección. El observador también puede controlar objetos con este rayo, por ejemplo, manipular una herramienta sencilla o abrir un contenedor."
reactions:
  - name: Agresivo
    desc: El contemplador puede moverse hasta su velocidad hacia una criatura hostil a la que pueda ver.
  - ...
```