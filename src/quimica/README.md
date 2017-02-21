## QUIMICA

### [porcentagem.js](https://github.com/gkal19/estudos-do-colegio/blob/master/src/quimica/porcentagem.js)

Adicionei um arquivo onde você pode fazer o cálculo da Porcentagem em Massa e Volume.
No exemplo abaixo peguei da Porcentagem em Volume onde o `v1` seria o nosso soluto e o `75`, o nosso solvente (`v2`). No final da linha de código, ele se multiplica por Cem para obter a Porcentagem.

OBS: Caso queira experimentar outro cálculo esteja a vontade.

```node
node
> const porcentagemEmVolume = (v1) => v1 / (v1 + 75) * 100
undefined
> porcentagemEmVolume(25)
25
```