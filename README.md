# 💰 Meu B.I. Financeiro

**Meu B.I. Financeiro** é um projeto em Python desenvolvido para ajudar na análise e visualização de finanças pessoais.  
O notebook realiza a limpeza e organização dos dados, gera gráficos interativos e oferece uma previsão simples de gastos futuros.

---

## Funcionalidades

- **Importação automática de planilhas CSV** com detecção de colunas (data, valor, categoria, descrição)  
- **Limpeza e padronização de dados** (remoção de erros, conversão de formatos e preenchimento de valores ausentes)  
- **Resumo financeiro automático**, incluindo saldo total, total de receitas e despesas  
- **Visualização de dados** com gráficos mensais e por categoria  
- **Previsão de gastos futuros** utilizando regressão linear simples  
- **Exportação dos dados tratados** em um novo arquivo `.csv`

---

## Como usar

1. Faça o download ou clone este repositório:  
   ```bash
   git clone https://github.com/seuusuario/meu-bi-financeiro.git

2.Acesse o diretório do projeto:

cd meu-bi-financeiro


Instale as dependências necessárias:

pip install pandas numpy matplotlib scikit-learn


4. Abra o arquivo meu_bi_financeiro_v2.ipynb no Jupyter Notebook, JupyterLab ou Google Colab.

Execute as células na ordem em que aparecem.
Quando solicitado, informe o caminho do seu arquivo .csv com os dados financeiros.

Estrutura do projeto
├── meu_bi_financeiro_v2.ipynb   # Notebook principal
├── README.md                    # Documento de explicação do projeto
└── dados/                       # (opcional) Pasta para armazenar planilhas financeiras

🧠 Tecnologias utilizadas

Python 3.8+

Pandas — manipulação de dados

NumPy — operações numéricas

Matplotlib — criação de gráficos

Scikit-learn — previsão com regressão linear

Observações

O modelo de previsão tem caráter ilustrativo e serve apenas para identificar tendências básicas.

Todos os dados são processados localmente, garantindo privacidade.

O notebook pode ser facilmente adaptado para novas colunas, categorias ou métodos de previsão.

Licença

Este projeto é de uso livre para fins pessoais e educacionais.
Sinta-se à vontade para modificar e compartilhar melhorias, desde que mantenha os créditos originais.

Autor: Carlos Ryan Sousa Guimarães
📧 Contato: c.ryansousa@gmail.com

📅 Última atualização: outubro de 2025
