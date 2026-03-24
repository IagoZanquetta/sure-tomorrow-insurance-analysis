# sure-tomorrow-insurance-analysis
Projeto de análise de clientes de seguros com machine learning para similaridade, previsão de benefícios e proteção de dados.

## Visão Geral

Este projeto analisa dados de clientes da empresa fictícia **Proteja Seu Amanhã** com o objetivo de resolver diferentes problemas de negócio relacionados a seguros. A proposta combina análise exploratória, técnicas de machine learning e conceitos de álgebra linear para investigar similaridade entre clientes, prever recebimento de benefícios, estimar o número de benefícios e avaliar estratégias de proteção de dados.

O foco principal é demonstrar como modelos analíticos podem gerar valor de negócio sem comprometer a privacidade das informações.

## Problema de Negócio

A empresa **Proteja Seu Amanhã** deseja utilizar seus dados de clientes para apoiar decisões mais inteligentes em diferentes frentes. Entre os objetivos do projeto estão identificar clientes semelhantes para ações direcionadas, prever a probabilidade de um cliente receber benefício de seguro, estimar a quantidade de benefícios e testar técnicas de mascaramento de dados que preservem a utilidade analítica das informações.

## Conjunto de Dados

O conjunto de dados contém informações sobre clientes da seguradora, incluindo variáveis relacionadas ao perfil pessoal e ao histórico de benefícios.

Dependendo da versão do projeto, o conjunto pode incluir atributos como:

- gênero
- idade
- renda
- número de membros da família
- quantidade de benefícios recebidos

Arquivo utilizado no projeto:

- `insurance_us.csv`

## Objetivos da Análise

Este projeto busca responder perguntas como:

- É possível encontrar clientes semelhantes com base em suas características?
- É possível prever se um cliente receberá benefício de seguro?
- É possível estimar a quantidade de benefícios recebidos?
- O mascaramento de dados compromete o desempenho analítico dos modelos?
- Como conceitos de álgebra linear podem ser aplicados para proteger informações sensíveis?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. análise exploratória
3. busca de clientes semelhantes
4. preparação dos dados para modelagem
5. treinamento de modelos de classificação
6. treinamento de modelos de regressão
7. aplicação de transformação de dados para obfuscação
8. comparação de resultados antes e depois da transformação
9. conclusões finais

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Estrutura do Repositório

```text
sure-tomorrow-insurance-analysis/
├── .gitignore
├── README.md
├── requirements.txt
├── sure_tomorrow_insurance_analysis.ipynb
└── insurance_us.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/sure-tomorrow-insurance-analysis.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd sure-tomorrow-insurance-analysis
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `sure_tomorrow_insurance_analysis.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos do projeto, estão:

* identificação de clientes semelhantes
* aplicação de algoritmos de classificação
* modelagem de regressão para estimativa de benefícios
* uso de métricas adequadas para avaliação
* transformação e obfuscação de dados
* preservação de desempenho após proteção das informações

## Resultados

O notebook inclui:

* análise inicial dos dados
* busca de vizinhos mais próximos
* treinamento e avaliação de modelos
* estimativa de benefícios
* aplicação de transformação linear nos dados
* comparação entre resultados antes e depois da obfuscação
* conclusões com foco em negócio e privacidade

## Conclusão

Este projeto demonstra como técnicas de machine learning e álgebra linear podem ser combinadas para resolver problemas de negócio no setor de seguros. Além de apoiar tarefas como classificação, regressão e análise de similaridade, o projeto mostra que é possível proteger dados sensíveis por meio de transformação matemática sem necessariamente comprometer o valor analítico das informações.

## Autor

**Iago Zanquetta**
