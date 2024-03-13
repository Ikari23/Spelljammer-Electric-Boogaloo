# Espectador

![](https://o.remove.bg/downloads/1c410899-d1a1-481e-a2cf-fdb49038d35a/image-removebg-preview.png)

Un espectador es un contemplador menor al que se invoca desde otro plano de existencia mediante un ritual mágico, cuyos componentes incluyen cuatro tallos oculares de contemplador que desaparecerán, consumidos por la magia del ritual. Es por esto que los espectadores tienen cuatro tallos, dos de cada lado del gran ojo que ocupa el centro de un cuerpo de 4 pies (1,2 m) de diámetro.

**_Guardianes mágicos_.** Los espectadores vigilan un lugar o tesoro a elección de sus invocadores durante 101 años, impidiendo a cualquier criatura, salvo a quien lo invocó, acercarse al lugar o utilizar el tesoro, a no ser que su invocador ordenara lo contrario. Si lo que guardaban desaparece o es destruido antes de que pasen sus años de servicio, el espectador desaparecerá. De ninguna otra manera abandonará su tarea.

**_Destellos de locura_.** Aunque puede hablar, un espectador se comunica principalmente mediante telepatía. Es respetuoso mientras cumple su cometido, y hablará sin problemas sobre sus órdenes y sobre su invocador. Sin embargo, incluso la más nimia de las conversaciones deja entrever pequeñas excentricidades den su personalidad, producto de muchos años aislado. Podría inventarse enemigos, hablar de él mismo en tercera persona o imitar la voz de su invocador.

Al igual que los contempladores, cada espectador se considera el paradigma de su raza, y odia profundamente al resto de espectadores. Si por algún casual dos de estas criaturas se encontraran, lo más probable es que luchen hasta la muerte.

**_Libres de su carga_.** Cuando un espectador cumple su tarea, es libre de hacer lo que quiera. Muchos deciden instalarse en el lugar que antes protegían, especialmente si quienes los invocaron han muerto. Dado que su vida carece de sentido, la locura que mostraban durante su servicio se agudiza.

```statblock
name: Espectador
size: Aberración
type: Mediano
subtype: (Contemplador),
alignment: legal neutral
ac: 14 (armadura natural)
hp: 39
hit_dice: 6d8 + 12
speed: 0 pies, volar 30 pies (levitar)
stats: [8, 14, 14, 13, 14, 11]
skillsaves:
  - Percepción: 6
condition_immunities: Derribado
senses: visión en la oscuridad 120 pies, Percepción pasiva 16
languages: Habla de las profundidades, Infracomún, telepatía 120 pies
cr: 3
actions:
  - name: Mordisco
    desc: Ataque con arma cuerpo a cuerpo: +1 a impactar, alcance 5 pies, un objetivo. Impacto: 2 (1d6 - 1) de daño perforante.
  - name: Rayos oculares
    desc: El contemplador dispara hasta dos de los siguientes rayos oculares mágicos contra una o dos criaturas que pueda ver y se encuentren a 90 pies o menos de distancia. Solo puede usar cada rayo una vez por turno. 1. _Rayo de confusión_. El objetivo deberá superar en una tirada de salvación de Sabiduría CD 13 o no podrá llevar a cabo reacciones hasta el final de su siguiente turno. además, durante su próximo turno el objetivo no podrá moverse y tendrá que usar su acción para hacer un ataque cuerpo a cuerpo o a distancia contra una criatura determinada aleatoriamente dentro de su alcance. si el objetivo no pude atacar no hará nada durante su próximo turno. 2. _Rayo paralizador_. La criatura deberá superar una tirada de salvación de Constitución CD 13 o quedará paralizada durante 1 minuto. El objetivo puede repetir la tirada de salvación al final de cada uno de sus turnos, librándose del efecto si tiene éxito. 3. _Rayo aterrador_. La criatura objetivo deberá superar una tirada de salvación de Sabiduría CD 13 o estará asustada durante 1 minuto. El objetivo puede repetir la tirada de salvación (con desventaja si puede ver al contemplador) al final de cada uno de sus turnos, librándose del efecto si tiene éxito. 4. _Rayo hiriente_. El objetivo deberá hacer una tirada de salvación de Constitución Cd 13, sufriendo 16 (3d10) de daño necrótico si la falla, o la mitad del daño si la supera.
  - name: Crear comida y agua
    desc: El contemplador crea mágicamente suficiente agua y comida para mantenerse a sí mismo durante 24 horas.
reactions:
  - name: Reflejar conjuro
    desc: Si el contemplador supera una tirada de salvación contra un conjuro, o un conjuro falla a la hora de impactarle, esta aberración podrá elegir otra criatura que se encuentre a 30 pies o menos de él y que pueda ver (incluso al propio lanzador del conjuro). El conjuro afectará a dicha criatura en lugar de al contemplador. Si el conjuro obliga a hacer una tirada de salvación, la criatura elegida deberá realizar la suya propia. Si, en cambio, el conjuro era un ataque, habrá que repetir la tirada de ataque contra el nuevo objetivo.
  - ...
```