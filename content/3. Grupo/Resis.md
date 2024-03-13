---
Type: Player
Art: "![[Character Image Placholder]]"
Level: 1
AC: 10
Prof: "2"
HP: 8
HitDice: d6
Speed: 30
STR: 10
DEX: 11
CONST: 14
INT: 17
WIS: 13
CHA: 7
Race: Replicante
Alignment: Caótico Bueno
Gender: Fluido
Age: "19"
Location: NONE
Class: Mago
Subclass: "-"
AssociatedGroup: NONE
Likes: NONE
Dislikes: NONE
Pronouns: NONE
PersonalityTrait:
  - NONE
SocialTrait:
  - NONE
MentalTrait:
  - NONE
Proficiencies:
  - NONE
Resistances:
  - NONE
Languages:
  - NONE
DmgTkn: 0
TempHP: 0
Copper: 0
Silver: 0
Electrum: 0
Gold: 0
Platinum: 0
---

---
>[!column|flex 2]
>> [!infobox]
>> # `=this.file.name`
>> ![[Character Image Placeholder]]
>> ###### Stats
>>  |
>> ---|---|
>> **Nivel** |`=this.level` |
>>  **Velocidad** |`=this.Speed` |
>> **Competencia** | +`=this.Prof` |
>> **Iniciativa** | +`=(this.DEX - 10)/2` |
>> **CA** | `=this.AC`
>> **PG** | `=this.HP - this.DmgTkn + this.TempHP` |
>> **Dados de Golpe** | `=this.Level + this.HitDice`  |
>> **Percepción Pasiva** |
>>  
>> ###### Bio
>>   |
>> ---|---|
>> **Raza** | `=this.race` |
>> **Género** | `=this.gender` |
>> **Edad** | `=this.age` |
>> **Alineamiento** | `=this.alignment` |
>> ###### Info
>>   |
>> ---|---|
>> **Clase(s)** | `=this.Class` |
>> **Sub-Clase(s)** | `=this.Subclass`
>> **Grupo(s)** | `=this.AssociatedGroup` |
>> **Religión(es)** | `=this.AssociatedReligion` |
>> Localización Actual | `=this.Location` |
>>  ### Economía
| Cobre         | Plata         | Oro         | Platino         |
| -------------- | -------------- | ------------ | ---------------- |
| `=this.Copper` | `=this.Silver` | `=this.Gold` | `=this.Platinum` |
>
>> [!infobox] Tiradas de Salvación de Muerte
>> ### Tiradas de Salvación de Muerte
| Éxitos | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ------- | --- | --------------------------------- | --------------------------------- |
>>
| Fallos | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ----- | --- | --------------------------------- | --------------------------------- |
>>
>> ### Características
| Característica | Puntuación       | Mod                     | Comp.                              | ST                                  |
| ----- | ----------- | ----------------------- | --------------------------------- | ----------------------------------- |
| <font color="#ff0000">**FUE**</font>   | `=this.STR` | +`=(this.STR - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.STR - 10)/2`               |
| <font color="#ffff00">**DES**</font>   | `=this.DEX`  | +`=(this.DEX - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`               |
| <font color="#00b050">**CON**</font>   | `=this.CONST` | +`=(this.CONST - 10)/2` | <input type="checkbox" unchecked>   | +`=((this.CONST - 10)/2)` |
| <font color="#7030a0">**INT**</font>   | `=this.INT`          | +`=(this.INT - 10)/2`   | <input type="checkbox" unchecked>   | +`=((this.INT - 10)/2)`   |
| <font color="#245bdb">**SAB**</font>   | `=this.WIS`          | +`=(this.WIS - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`               |
| <font color="#de7802">**CAR**</font>   | `=this.CHA`          | +`=(this.CHA - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`               |
>> ### Pruebas de Característica
| Habilidad             |                                   | Mod                     |
| --------------------- | --------------------------------- | ----------------------- |
| Acrobacias (DES)      | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Atletismo (FUE)       | <input type="checkbox" unchecked> | +`=(this.STR - 10)/2`   |
| Conocimiento Arcano (INT)          | <input type="checkbox" unchecked> | +`=((this.INT - 10)/2)` |
| Engaño (CAR)       | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`   |
| Historia (INT)         | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`   |
| Interpretación (CAR)     | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`   |
| Intimidación (CAR)    | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`   |
| Investigación (INT)   | <input type="checkbox" unchecked> | +`=((this.INT - 10)/2)` |
| Juego de Manos (DES) | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Medicina (SAB)        | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`   |
| Naturaleza (INT)          | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`   |
| Percepción (SAB)      | <input type="checkbox" unchecked> | +`=((this.WIS - 10)/2)` |
| Perspicacia (SAB)         | <input type="checkbox" unchecked> | +`=((this.WIS - 10)/2)` |
| Persuasión (CAR)      | <input type="checkbox" unchecked> | +`=(this.CHA - 10)/2`   |
| Religión (INT)        | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`   |
| Sigilo (DES)         | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Supervivencia (SAB)        | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`   |
| Trato con Animales (SAB) | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`   |        



Resis nació, como muchos [[Replicante|replicantes]], en el [[Paraje Feérico]]. Por desgracia para elle, nació en la comunidad de la [[saga nocturna]] conocida como [[Frau Totenkinder]]. Esta saga usaba a la comunidad de replicantes para robar niños del plano material y sustituirlos, evitando así llamar la atención de posibles caza sagas. Este, por supuesto, fue el caso de Resis. Arrancade, de los brazos de sus padres originales, fue llevade al plano material de la esfera cristalina conocida como [[Ilardis]], mundo que pasaba una suerte de revolución industrial. De esta manera sustituyó, sin ser consciente de ello, a la hija de un joven matrimonio en las fronteras de la civilización del mundo.

Llegó a sus 5 años sin conocer estos hechos, pensando que era realmente la hija de Bartholomew y Lesas Tucker. Ahora siendo considerada chica, Resis creció rodeada de historias de los exploradores pistoleros, como era su padre,  de aquella zona fronteriza; así como las historias que le leía su madre, escritas por un famoso novelista, sobre pilotos de barcos que surcaban las estrellas e inteligentes académicos arcanos que velaban por el bien de las personas. Pero algo falló llegada a esta edad: Su forma de replicante se reveló durante unos segundos delante de su irascible padre, que no dio crédito a lo que vio. En [[Ilardis]] la superstición rezaba que los replicantes eran fruto de la unión con un [[doppleganger]], lo que llevó a Bartholomew a pensar que su mujer había sido suplantada. El padre adoptivo de Resis acabó con la vida de su madre delante de ella y decidió encerrar a la pobre muchacha en el sótano de casa.

El trauma generado por ver morir a su madre delante de ella y su confinamiento, rompió la mente de Resis en pedazos, que comenzaron a tomar forma a partir de las historias de las que se rodeó. Así nacieron [[Rex]], el indomable pistolero de las fronteras; [[Cid]], el piloto borrachuzo y gruñón; el profesor [[Genevor]], arcanista; y [[Lea]], lo que Resis podría haber sido. A pesar de los innumerables planes de Rex y Cid para escapar, Genevor y Lea centraron al sistema conocido como Resis en el estudio de los polvorientos libros de magia que su madre había guardado en el sótano antes de su muerte. A los 16 años, Lea se había convertido en la aprendiz del profesor Gen y comenzó a sangrar esos conocimientos al resto de personalidades. Viendo el poder con el que se habían hecho, Rex tomó el control del sistema y, grabando símbolos arcanos en unos viejos revólveres con el cañón roto almacenados en el sótano, los convirtió en su foco arcano. Rex, convertido en su forma física por primera vez gracias a las habilidades replicantes de Resis, esperó pacientemente a que Bartholomew trajese la comida diaria. Cuando abrió la puerta, Rex disparó dos descargas de fuego a las rodillas del padre y, a punto de ejecutarlo del todo, fue detenido por Lea, que le instó a escapar.

Tras dejar con vida al señor Tucker, Rex dedicó una pequeña temporada al oficio de pistolero, usando sus focos arcanos en vez de armas de verdad. Lea y Gen continuaron buscando maneras de ampliar sus conocimientos arcanos. Cid se sentía contrariado, ya que era el único que no estaba, según él, “haciendo lo suyo”. Con el tiempo, Totenkinder puso su mira en este sistema e, interesada en usar a Resis como uno de sus agentes, le convocó al [[Paraje Feérico]]. Sin embargo, antes de tener una audiencia con la saga, los replicantes de la misma ayudaron a Resis a escapar a través de uno de los portales de Frau Totenkinder. Al traspasar el portal de solo ida, se encontró que no se hallaba ya en [[Ilardis]]. Otro lugar, muy distinto a casa, se encontraba ante ellos. En este nuevo lugar, al que sus habitantes llamaban Faerun, Genevor comenzó a investigar y descubrió la existencia de viajes entre esferas cristalinas a través de algo conocido como [[Barco de Spelljamming]], además de la existencia de una especie de [[Academia Spelljammer|academia]]. Lea convenció a Cid que este era el momento de “hacer lo suyo” y le dio las riendas del sistema.
