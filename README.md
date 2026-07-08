# Repositório Didático de Geoprocessamento


## Objetivo

Este repositório reúne procedimentos documentados de geoprocessamento. A ideia não é apresentar apenas tutoriais demonstrando como utilizar as ferramentas, mas também explicar os motivos de suas escolhas dentro de cada procedimento metodológico.

Cada procedimento é independente, apresentando um problema a ser investigado ou uma questão a ser respondida com base em dados espaciais. Como a metodologia também é explicada, a reprodução e a adaptação dos procedimentos para qualquer ferramenta de GIS ou linguagem de programação podem ser feitas independentemente das utilizadas nos exemplos apresentados (R, Python e PostGIS).

Portanto, este material serve de apoio a estudantes e profissionais que atuam nas áreas de geoprocessamento e análise de dados.

## Filosofia do repositório

Os procedimentos aqui apresentados seguem alguns princípios básicos.

+ Explicar conceitos antes de apresentar ferramentas.
+ Justificar as decisões metodológicas adotadas.
+ Disponibilizar o código utilizado nas análises.
+ Priorizar a reprodutibilidade e adaptabilidade dos resultados priorizando exemplos simples a partir de questões cotidianas.
+ Quando necessário, indicar referêcnias na literatura para complementar o procedimento.
+ Focar na clareza em vez de quantidade de conteúdo.

## Estrutura dos procedimentos

Normalmente os procedimentos seguem uma organização similar à demonstrada a seguir: 

```{r}
Procedimento
│
├── Objetivo
├── Breve fundamentação
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

Algumas exceções são os casos de roteiros apresentados externamente, como no Google Colab.

## Procedimentos disponíveis

| Procedimento                                                                    | Situação              |
| ------------------------------------------------------------------------------- | --------------------- |
| Redistribuição da população para malhas hexagonais utilizando áreas urbanizadas | 🚧 Em desenvolvimento |
| [Análise de redes e roteamento: Melhor rota para pedestres com pgRouting](./02_pgrouting_melhor_rota_pedestres/README.md) | Disponível |

## Licença

* **Código:** [MIT](LICENSE-CODE)
* **Material Didático:** [CC BY 4.0](LICENSE-DOCS)

