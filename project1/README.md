## Projeto da 1º unidade

### Aluno: João Pedro Freire Cabral

Nessa atividade, foi desenvolvida uma forma de representação de um [dataset](https://www.kaggle.com/datasets/pavellexyr/the-reddit-climate-change-dataset) por meio de uma classe python.
De modo geral, foram feitas análises referentes a complexidade e métodos apresentados durante a disciplina.

O código pode ser visto em 3 partes que acompanham os requisitos dados:

1) Dado um id de uma mensagem no Reddit, retornar todas as informações sobre a mensagem; 
  - Existem dois métodos presentes. O primeiro método, `find_element`, percorre todas as linhas buscando o id desejado. Já o `find_element_fast` usa um dicionário python, cuja performance é melhor.
2) Dado um limite inferior e superior da coluna "sentiment", retornar todas as mensagens com valores de sentimento entre os limites inferior e superior; 
  - O método `find_messages_sentiment` recebe os limites inferior e superior e retorna todas mensagens que estão entre esses.
3) Dado um valor de parâmetro, retornar duas mensagens cuja soma do valor da coluna "score" é igual ao parâmetro. Retornar -1 se não existir. 
  - Dois métodos diferentes executam este passo. O `check_sum` performa com complexidade quadrática ao aninhar dois laços de repetição. Já o `check_sum_fast` usa uma técnica, mostrada em sala usando dicionários, para melhorar a performance.
