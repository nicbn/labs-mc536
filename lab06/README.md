# Modelo para Apresentação do Lab06 - Artigo de Dataset Público

# Aluno

* `222903`: `Nicolas Bissoli Nattis`

# Análise do Artigo `Extracting and Composing a Dataset of Competitive Counter-Strike Global Offensive Matches`

| campo | valor |
|------------|----------------------------------------|
| referência | `Erick Rocha, Henrique Maio, Daniel S. Menasché, Claudio Miceli: Extracting and Composing a Dataset of Competitive Counter-Strike Global Offensive Matches.` |
| link       | `https://drive.google.com/file/d/106Ps__OM8ryapvP958FAIyhEWkzf_XfS/view` |
| dataset | `https://tinyurl.com/csgodataset` |
| formato | `Parquet` |

## Resumo

O artigo apresenta desafios apresentados na acquisição de dados de partidas competitivas enquanto a resultados de partidas e dados internos do jogo em Counter Strike: Global Offensive, e métodos aplicados para passar estes objetivos e adquirir e analisar esses dados. Através de arquivos de jogo providos pelo site HLTV, o artigo mostra coleta de dados para partidas jogadas na "ESL Pro League Season 13", e as diversas tabelas que se tornam disponíveis a partir de tais dados.

## Perguntas de pesquisa/análises

Perguntas que podem ser feitas através do dataset:
* Qual a relação quantitativa entre quantidade de mortes de jogadores em cada equipe e o status do ciclo de vida da bomba (plantada, coletada, explodida, defusada)?
* Em que tempo do round os jogadores costumam ficar com qual quantidade de vida (exemplo, exibição de um gráfico de probabilidade de vida para cada 30 s de jogo)?
* Quais granadas costumam ser jogadas aonde no mapa?
* Quais armas são mais usadas em que round?
* Quais estratégias configuram quais usos de granada, tiros, e movimentação?

O dataset é "proof-of-concept" e através do workflow é possível incluir mais dados no dataset.

## Trabalhos relacionados

* Coleta e análise de dados no Second Life \[Varvello e Voelker 2020, Vavevello et al. 2008\].
* Outros trabalhos com foco no Counter Strike \[Bednárek et al. 2017\] e \[Xenopoulos et al. 2020\].
