# Modelo de Recomendação - Amazon
Criar um sistema de recomendação para os clientes da Amazon.

## Contexto
O CEO da Amazon contratou um time de cientistas de dados para trabalhar em diferentes vertentes da empresa, e você ficou encarregado de fazer um sistema de recomendação para os clientes Amazon. Para isso, te deram acesso à uma base de dados não muito estruturada em Json: um arquivo de metadata com informações dos produtos e outro com as avaliações.

### Projeto
O CEO deseja que seu algoritmo de recomendação seja exclusivamente em cima de avaliações verificadas (campo `verified=True` no arquivo de avaliações). Contudo, há uma base sem classificação e que o CEO faz questão de que seja adicionada no sistema de recomendação (valores com missing value na coluna `verified`). Para isso, você precisará classificar se estas avaliações são verificadas ou não, e no caso positivo, adicioná-los no sistema de recomendação.

Adicionalmente, o CEO também deseja saber de possíveis associações e/ou correlações nesta base de dados que você vai trabalhar.

- Carregar, limpar e fazer análises exploratórias no banco de dados fornecido;
- Classificar a base sem informação para incluir as observações das avaliações verificadas no sistema de recomendação;
- Desenvolver e entregar um sistema de recomendação, com exemplos de aplicação.
