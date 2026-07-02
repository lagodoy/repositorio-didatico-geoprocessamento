# Repositório Didático de Geoprocessamento


## Objetivo

Este repositório reúne procedimentos comentados de geoprocessamento desenvolvidos com foco na compreensão dos conceitos, na reprodutibilidade e na documentação das decisões metodológicas.

Diferentemente de tutoriais convencionais, este material busca explicar não apenas como executar determinada operação, mas também por que ela é necessária, quais são suas limitações e quais pressupostos justificam sua utilização.

Cada procedimento é apresentado de forma independente, permitindo sua reprodução utilizando ferramentas livres, como o QGIS e a linguagem R, podendo também incluir implementações em Python quando pertinente.

O principal objetivo é produzir um material de caráter didático que possa servir simultaneamente como referência para estudantes, pesquisadores e profissionais da área de Geoprocessamento.

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

