# Análise rápida de precificação e elasticidade

Material complementar da videoaula **[“Quick and dirty”: análise de dados com Python — precificação e elasticidade](https://youtu.be/Vn45DCpdXNw)**.

O notebook [`precificacao_elasticidade.ipynb`](precificacao_elasticidade.ipynb) constrói dados sintéticos, agrega observações em faixas, visualiza preço e captação de clientes e ajusta aproximações lineares e quadráticas. O objetivo é demonstrar um fluxo exploratório curto e reproduzível.

## Interpretação

Na teoria econômica, a elasticidade-preço da demanda é definida por

\[
\varepsilon_{Q,P}=\frac{\partial Q}{\partial P}\frac{P}{Q}.
\]

No conjunto sintético do notebook, a coluna `Elasticidade` é construída por uma função escolhida para fins didáticos. Ela é, rigorosamente, um **índice sintético**, não uma elasticidade estimada a partir de variação observacional ou experimental. Da mesma forma, a curva chamada no código de `Laffer` é uma analogia visual de captação de clientes; a designação clássica de curva de Laffer refere-se à relação entre alíquota tributária e receita fiscal.

## Limites analíticos

A associação entre preço e demanda pode refletir segmentação, promoções, sazonalidade, seleção de clientes e simultaneidade. Uma análise aplicada deve definir o estimando, controlar confundidores relevantes e preferir experimentos, quase-experimentos ou modelos causais adequados. O notebook não substitui esse desenho de pesquisa.

## Execução

A partir da raiz do repositório:

```bash
conda activate ai-data-citizen
jupyter lab ciencia_de_dados/analise_exploratoria_rapida/precificacao_elasticidade.ipynb
```

Todos os dados são gerados localmente com semente fixa; nenhum dado comercial real é utilizado.
