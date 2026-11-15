# Gravidade dos acidentes nas rodovias federais

Projeto final da disciplina de Ciência de Dados (Instituto de Computação, UFAL).

Equipe: Felipe da Silva Araújo, Fernando Gabriel Feitosa Leite e Karllisson Henrique da Silva.

## Estrutura

- `dados/brutos/`: acidentes registrados pela PRF, agrupados por ocorrência, de 2017 a 2025 ([Dados Abertos da PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf)).
- `proposta/`: proposta da Parte 1.
- `modelo/`: modelo de artigos da SBC, mantido como referência.
- `docs/`: especificação do projeto e slides da aula sobre ele.

## Ambiente

Com o [uv](https://docs.astral.sh/uv/) instalado, `uv sync` cria o ambiente com Python 3.13 e as mesmas versões de pacotes do Google Colab.

Os documentos LaTeX compilam com `latexmk -pdf` dentro da pasta de cada um.
