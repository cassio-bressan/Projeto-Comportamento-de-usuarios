# # 🧪 Análise de Funil de Vendas e Teste A/A/B no App de Produtos Alimentícios

Este projeto consiste na análise do comportamento dos usuários em um aplicativo de vendas de uma startup de alimentos. A análise se divide em duas partes principais: o estudo do funil de conversão dos usuários dentro do app e a avaliação dos resultados de um teste A/A/B, cujo objetivo é verificar o impacto de uma mudança de fonte na taxa de conversão. O projeto foi desenvolvido durante o bootcamp de Análise de Dados da TripleTen e tem fins educacionais e de portfólio.

## 🗂️ Estrutura do Projeto
- ``Projeto/`` — Notebook final com os códigos organizados e comentários do autor.

- ``Feedback/`` — Notebook com comentários do revisor técnico do bootcamp.

- ``Dados/`` — Arquivo .csv com os dados utilizados na análise.

## 🧠 Objetivos do Projeto
- Analisar o comportamento dos usuários no funil de vendas do app.

- Identificar gargalos nas etapas do funil e propor melhorias.

- Avaliar o impacto da mudança de fonte no design do app por meio de um teste A/A/B.

- Verificar a consistência entre os grupos de controle e o grupo de teste.

## 🛠 Técnicas Utilizadas
- Análise exploratória de dados (EDA)

- Análise de funil de conversão

- Testes de hipóteses (teste de proporções com scipy.stats)

- Manipulação de dados com pandas

- Comunicação de resultados com Jupyter Notebooks

## 🧪 Metodologia A/A/B
- Os usuários foram divididos em três grupos:

    - A1 e A2: grupos de controle com a fonte original

    - B: grupo de teste com a nova fonte

- Foram realizadas comparações entre A1 vs A2 (validação do teste) e A1/A2 vs B (impacto da nova fonte).

- Conclusões baseadas em testes estatísticos e análise descritiva.

## 📈 Exemplos de Análises Realizadas
- Qual porcentagem de usuários conclui o funil de compras?

- Em que etapa os usuários mais abandonam o processo?

- A nova fonte tem impacto negativo na conversão?

- Os grupos de controle são estatisticamente semelhantes?

## 💾 Como Executar
- Clone este repositório em sua máquina local.

- Certifique-se de ter Python 3 instalado com as seguintes bibliotecas:

    - Pandas

    - Numpy

    - Scipy

- Abra o notebook em Projeto/ com Jupyter ou VSCode.

- Execute as células para reproduzir a análise.