# Tarefa Final de Google Sheets para Análise de Dados

- Link para o Google Sheets: https://docs.google.com/spreadsheets/d/1eXwWm9TLkUPMHCFFC5jEIKFNOH0UtONLz2y8_YzIAWY/edit?usp=sharing

## Tabelas Utilizadas

- Eventos
<img width="1918" height="943" alt="Captura de tela 2026-03-05 111821" src="https://github.com/user-attachments/assets/334b5348-5c17-4889-bf86-8e32537783eb" />

- Produtos
<img width="1919" height="943" alt="Captura de tela 2026-03-05 112309" src="https://github.com/user-attachments/assets/57a44e5e-545f-4979-bfc1-c598291a9a82" />

- Países
<img width="1919" height="943" alt="image" src="https://github.com/user-attachments/assets/d5bd742a-b63d-4e77-b016-ec505ee78538" />

## Fórmulas utilizadas

- Para as datas foram utilizadas `SPLIT`, `RIGHT`, `LEFT`, `DATEDIF`, `WEEKNUM`, `WEEKDAY`.
- Para conexão entre tablelas foi utilizado o `VLOOKUP`, mas o ideal seria utilizar `INDEX`, assim não é necessário alterar a ordem de colunas das tabelas.
- Foi utilizado também a função `IFNA`, para retornar um valor padrão caso aquela linha esteja vazia.
- Também foi utilizada a função Data Cleanup, com remoção de duplicatas e de espaços vazios.

## Parte Analítica
- Dados importantes
<img width="270" height="285" alt="image" src="https://github.com/user-attachments/assets/e988b0f4-8157-4370-b3a9-211880ff9c46" />

- Análise ABC
<img width="664" height="387" alt="image" src="https://github.com/user-attachments/assets/7030e1e2-2bed-4bee-95f7-1e1b70fddd63" />

## Dashboard
<img width="1275" height="804" alt="image" src="https://github.com/user-attachments/assets/6bda05c3-dc92-4208-851c-baabc8b73f28" />

<img width="1284" height="805" alt="image" src="https://github.com/user-attachments/assets/05537484-4d5e-476f-afd5-8da398e7b01a" />

## Conclusões

A empresa vende seus produtos para 45 diferentes países, a imensa maioria localizados na Europa, principalmente para a região sul;
Praticamente não há diferença entre vendas online e offline. As categorias de produtos mais vendidos são: cosméticos, itens de escritório e produtos de casa. Não parece haver uma correlação entre os produtos mais vendidos e um menor tempo de envio;
Também em relação ao tempo de envio, analisando a tabela de dados, temos uma Ordem de Prioridade, que presume-se ser: C - Critical (crítico), H - High (alto), M - Medium (médio) e L - Low (baixo). Comparando isso aos tempos de envio, a diferença é muito pequena entre as classificações, com a prioridade baixa ficando até com tempo menor que a prioridade média.
Os dias da semana com mais número de pedidos são: domingo, segunda-feira e sábado. Já os meses com maior número de pedidos são: março, janeiro e junho;
Em relação ao crescimento da empresa, tanto o lucro quanto a quantidade de unidades vendidas está em uma tendência de queda. Houve uma alta até 2012, mas desde então tivemos sucessivas baixas, até o menor valor no último ano dos dados, 2017;

Análise ABC:
Através dela, podemos concluir que cosméticos, itens de escritório, produtos de casa, papinhas para bebês, roupas, cereais e vegetais, fazem parte do grupo A e devem continuar sendo priorizados, são o “carro-chefe” da empresa;
Já carnes e aperitivos estão no grupo B, onde a empresa pode priorizá-los para levá-los ao grupo A, ou então deixá-los “de lado”, no grupo C;
Por fim, itens de cuidado pessoal, bebidas e frutas devem ser estudados pela a empresa para serem eliminados.
