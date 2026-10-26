# Lei de Diretrizes Orçamentárias 2027 -- São José do Norte

Este repositório contém os parâmetros macroeconômicos, os históricos de arrecadação e a memória de cálculo detalhada utilizada para a estimativa das receitas orçamentárias na Lei de Diretrizes Orçamentárias (LDO) para o exercício de 2027.

## Visão geral

O objetivo deste modelo é garantir a transparência, a consistência técnica e o cumprimento da Lei de Responsabilidade Fiscal (LRF), demonstrando a metodologia de cálculo para a previsão das receitas correntes do município.

## Como usar

- O documento [`ldo.ipynb`](ldo.ipynb) contém todo o detalhamento das estimativas para consulta.
- O documento [`estimativas.csv`](estimativas.csv) contém as estimativas propriamente ditas.

## Estrutura do projeto

O projeto está assim organizado

```
├── data/               # Diretório dedicados aos dados
│   ├── ipm.csv         # Dados brutos de IPM usados no projeto
│   └── revenues.csv    # Dados brutos de receita usados no projeto
├── estimativas.csv     # Saída com as estimativas de receita
├── ldo.ipynb           # Memória de cálculo / script de geração dos dados
├── LICENSE             # Arquivo com a licença de uso
├── pyrightconfig.json  # Regras de tipagem
├── README.md           # Este arquivo
└── requirements.txt    # Dependências do projeto
```

## Como replicar os resultados

Após clonar este repositório,
* Crie um ambiente virutal com `python -m venv .venv`
* Entre no ambiente virtual com `source .venv/bin/activate`
* Instale as dependências com `pip -m requirements.txt`
* Utilize o arquivo `ldo.ipynb` para realizar a replicação

## Licenciamento

Este repositório está sob a licença [GNU Affero General Public License na versão 3](https://www.gnu.org/licenses/agpl-3.0.en.html). Consulte o arquivo [`LICENSE`](LICENSE) para mais detalhes.

Copyright (c) 2026 Prefeitura Municipal de São José do Norte, RS.