# Trilha rápida do analista de dados

Material complementar da videoaula **[Trilha rápida do analista de dados: exemplos de funções Python, SQL e DAX muito utilizadas](https://youtu.be/dLDmXewxwpA)**.

## Conteúdo

O notebook parte de um conjunto sintético de estudantes e percorre operações recorrentes em três ecossistemas:

- **Python e pandas:** inspeção, seleção, filtros, agrupamentos, ordenação, valores ausentes e leitura ou escrita de arquivos CSV e Parquet;
- **SQL e DuckDB:** `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, agregações e operações básicas de criação, inserção e exclusão;
- **DAX e Power BI:** agregadores, contexto de filtro, iteradores e funções condicionais.

## Arquivos

| Arquivo | Finalidade |
|---|---|
| [`fast_track.ipynb`](fast_track.ipynb) | Roteiro computacional da aula |
| [`df_fast_track.csv`](df_fast_track.csv) | Dados tabulares com separador `;` |
| [`df_fast_track.parquet`](df_fast_track.parquet) | Versão colunar dos mesmos dados |
| [`fast_track.pbix`](fast_track.pbix) | Relatório para Power BI Desktop |

## Execução

A partir da raiz do repositório, ative o ambiente e inicie o JupyterLab:

```bash
conda activate ai-data-citizen
jupyter lab
```

Execute o notebook dentro desta pasta para que os caminhos relativos dos arquivos CSV e Parquet sejam resolvidos corretamente. A geração de dados sintéticos utiliza semente e data de referência fixas, permitindo reproduzir os resultados.

## Observação sobre DAX

DAX não é apenas uma variante de SQL. Suas expressões são avaliadas em contextos de linha e filtro próprios do modelo tabular. As funções listadas no notebook constituem uma introdução; medidas reais exigem um modelo dimensional coerente e relações corretamente definidas.
