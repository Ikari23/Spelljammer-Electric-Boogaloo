# Bandido
![bandido](https://5etools-mirror-1.github.io/img/MM/Bandit.png)

Los bandidos se unen en bandas que, en ocasiones, están dirigidas por matones, veteranos o lanzadores de conjuros. No todos los bandidos son malvados, pues la tiranía, sequías, enfermedades o hambrunas pueden obligar a gente honesta a llevar una vida de bandidaje.

Los piratas son los bandidos del mar. Pueden ser tanto filibusteros a los que solo les importan las riquezas y el asesinato como corsarios con una sanción de la corona para atacar y saquear a los navíos de las naciones enemigas.

```statblock
name: Bandido
size: Humanoide
type: Mediano
subtype: (cualquier raza)
alignment: , cualquier alineamiento no legal
ac: 12 (armadura de cuero)
hp: 11
hit_dice: 2d8 +2
speed: 30 pies
stats: [11, 12, 12, 10, 10, 10]
senses: Percepción pasiva 10
languages: uno cualquiera (normalmente Común)
cr: 1/8
actions:
  - name: Cimitarra
    desc: "Ataque con arma cuerpo a cuerpo: +3 a impactar, alcance 5 pies, un objetivo. Impacto: 4 (1d6 + 1) de daño cortante."
  - name: Ballesta ligera
    desc: "Ataque de arma a distancia: +3 a impactar, alcance 80/320 pies, un objetivo. Impacto: 5 (1d8 + 1) de daño perforante."
```

```statblock
name: Capitán Bandido
size: Humanoide
type: Mediano
subtype: (cualquier raza)
alignment: , cualquier alineamiento no legal
ac: 15 (cuero tachonado)
hp: 65
hit_dice: 10d8 +20
speed: 30 pies
stats: [15, 16, 14, 14, 11, 14]
saves:
  - Fue: 4
  - Des: 5
  - Sab: 2
skillsaves:
  - Atletismo: 4
  - Engaño: 4
senses: Percepción pasiva 10
languages: dos cualesquiera
cr: 2
actions:
  - name: Ataque múltiple
    desc: "El capitán bandido realiza tres ataques: dos con su cimitarra y uno con su daga. O hace dos ataques a distancia con sus dagas"
  - name: Cimitarra
    desc: "Ataque con arma cuerpo a cuerpo: +5 a impactar, alcance 5 pies, un objetivo. Impacto: 6 (1d6 + 3) de daño cortante."
  - name: Daga
    desc: "Ataque de arma cuerpo a cuerpo o a distancia: +5 a impactar, alcance 5 pies o alcance 20/60 pies, un objetivo. Impacto: 5 (1d4 + 3) de daño perforante."
reactions:
  - name: Parada
    desc: "El capitán bandido añade 2 a su CA contra un ataque cuerpo a cuerpo que le fuera a impactar. Para poder hacer esto debe ver a su atacante y estar empuñando un arma cuerpo a cuerpo."
```
