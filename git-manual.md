## Milestones

Milestone é um "objetivo". Você marca um determinado ponto no desenvolvimento com uma milestone, que deve ser criada previamente, como uma expectativa do progresso na determinada data. Pode-se dizer que é um "prazo" dado ao desenvolvedor, ou por si mesmo ou por seu empregador.

Os nomes de milestones são nomes de versões. As versões MAJOR, dadas por números inteiros(antes do ponto), são versões com mudanças significativas. As versões MINOR, dadas por números após o ponto, indicam mudanças pequenas no projeto. Há ainda as versões FIX, indicadas por um número após um segundo ponto, indicam correções de erros não-detectados.

Uma milestone deve estar no seguinte formato, no mínimo:

* v1.0 (MAJOR.MINOR)

* v1.0.1 (MAJOR.MINOR.BUGFIX)


#### Releases e Tags

Ao cumprir uma milestone, você dá uma tag no commit final daquela milestone, indicando o cumprimento do objetivo. 

O nome da tag deve ser o mesmo do nome da milestone.

Também há a forma mais organizada:

* v1.0.180418.172630 (MAJOR.MINOR.AAMMDD.HHMMSS)

* v1.0.1.180418.172720 (MAJOR.MINOR.BUGFIX.AAMMDD.HHMMSS)

No caso também dando a última data de compilação antes do commit final, informação escrita no arquivo VERSION, gerado utilizando o make para comilar, com os seguintes parâmetros:

```
make exemplo.x MAJOR=1 MINOR=0 DEBUG=0 FORTIFY=1
```

Caso queira ocultar avisos sobre scanf, utilize `FORTIFY=0`

## Issues



#### Labels



