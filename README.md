# Repositório Didático de Geoprocessamento


## Objetivo

Este repositório reúne procedimentos documentados de geoprocessamento. A ideia não é apresentar apenas tutoriais demonstrando como utilizar as ferramentas, mas também explicar os motivos de suas escolhas dentro de cada procedimento metodológico.

Cada procedimento é independente, apresentando um problema a ser investigado ou uma questão a ser respondida com base em dados espaciais. Como a metodologia também é explicada, a reprodução e a adaptação dos procedimentos para qualquer ferramenta de GIS ou linguagem de programação podem ser feitas independentemente das utilizadas nos exemplos apresentados (R, Python e PostGIS).

Portanto, este material serve de apoio a estudantes e profissionais que atuam nas áreas de geoprocessamento e análise de dados.

## Filosofia do repositório

Os procedimentos aqui apresentados seguem alguns princípios básicos.

+ Explicar conceitos antes de apresentar ferramentas.
+ Justificar as decisões metodológicas adotadas.
+ Priorizar a reprodutibilidade dos resultados.
+ Utilizar exemplos simples e facilmente reproduzíveis.
+ Disponibilizar o código utilizado nas análises.
+ Fundamentar decisões importantes na literatura científica.
+ Priorizar clareza em vez de quantidade de conteúdo.

## Estrutura dos procedimentos

Todos os procedimentos seguem a mesma organização.

```{r}
Procedimento
│
├── Objetivo
├── Fundamentação
├── Dados de entrada
├── Procedimento comentado
│     ├── Etapa 1
│     ├── Etapa 2
│     ├── ...
│
├── Código em R
├── Código em Python (quando aplicável)
├── Considerações finais
└── Referências
```

## Procedimentos disponíveis

| Procedimento                                                                    | Situação              |
| ------------------------------------------------------------------------------- | --------------------- |
| Redistribuição da população para malhas hexagonais utilizando áreas urbanizadas | 🚧 Em desenvolvimento |

## Licença

* **Código:** [MIT](LICENSE-CODE)
* **Material Didático:** [CC BY 4.0](LICENSE-DOCS)

