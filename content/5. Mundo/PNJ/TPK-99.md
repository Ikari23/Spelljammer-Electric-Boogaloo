# TPK-99
*Sirviente Autógnomo*

![](https://th.bing.com/th/id/OIG.QLwHUiCfqYxySqWeIUrI?pid=ImgGn)
TPK-99 es un autógnomo programado para servir a Veena Nightguard. Su principal misión es proteger a Veena. No tiene voluntad propia y se comunica principalmente con pitidos y silbidos.

**Traidor.** Si es seleccionado como traidor, TPK-99 fue en realidad un regalo del mercenario Vocath a la familia Nightguard, y ha sido programado en secreto para cumplir las órdenes de Vocath. Al ser descubierto, Vocath desea recuperar el autógnomo antes de que se pueda rastrear hasta él cualquiera de sus datos.

```statblock
name: TPK-99
size: Autómata
type: Mediano
subtype: (Autognómo),
alignment: sin alineamiento
ac: 13 (armadura natural)
hp: 65
hit_dice: 10d8+20
speed: 30 pies
stats: [14, 14, 14, 10, 8, 8]
damage_resistances: Psíquico, Veneno
senses: Percepción pasiva 9
languages: Común
cr: 1
actions:
  - name: Pistola
    desc: "Ataque con arma a distancia: +4 a impactar, alcance 30/90 pies, un objetivo. Impacto: 7 (1d10 + 2) de Daño Perforante."
  - name: Torbellino de cuchillas
    desc: "Las cuchillas se extienden desde TPK-99 mientras gira. Todas las criaturas en un radio de 5 pies deben realizar una Tirada de Salvación de Destreza CD 13. Un objetivo recibe 8 (2d8) de Daño Cortante si falla, o la mitad si tiene éxito."
bonus_actions:
  - name: Inyección (2/Día)
    desc: TPK-99 puede inyectar una poción curativa a una criatura que se encuentre a 5 pies de él. El objetivo recupera 7 (2d4 + 2) Puntos de Golpe.
reactions:
  - name: Intercepción
    desc: Cuando una criatura que TPK-99 puede ver golpea a un objetivo, que no sea ella misma, a menos de 5 pies de ella con un ataque, puede usar su reacción para reducir el daño que recibe el objetivo en 7 (1d10 + 2) (hasta un mínimo de 0 de daño).
```