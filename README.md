# Previsão de Renda

Aplicação de ciência de dados que estima a renda de clientes a partir de informações cadastrais. O projeto foi desenvolvido no curso Profissão: Cientista de Dados da EBAC e segue as etapas do CRISP-DM.

## Funcionalidades

- análise exploratória dos dados;
- relatório automatizado de perfil;
- visualizações univariadas e bivariadas;
- preparação das variáveis;
- treinamento de árvore de regressão;
- simulação interativa em Streamlit.

## Executar localmente

Requer Python 3.10 ou superior.

```bash
git clone https://github.com/EduardoQuero/previsao-renda.git
cd previsao-renda
python -m venv .venv
```

Ative o ambiente virtual e instale as dependências:

```bash
pip install -r requirements.txt
pip install streamlit pandas numpy matplotlib seaborn
streamlit run Projeto_02.py
```

A aplicação ficará disponível em `http://localhost:8501`.

## Estrutura

```text
Projeto_02.py                              aplicação Streamlit
ebac-projeto02-previsao_eduardo-quero.ipynb análise completa
input/                                     dados de entrada
output/                                    artefatos gerados
pages/                                     páginas adicionais
requirements.txt                           dependências
```

## Metodologia

O fluxo cobre entendimento do negócio, exploração, preparação, modelagem, avaliação e implantação. A árvore de regressão é usada como modelo principal para relacionar o perfil cadastral à renda observada.

> Projeto educacional. As previsões não devem ser usadas isoladamente para decisões financeiras.