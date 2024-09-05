# Copa-familia
COPA FAMÍLIA

A copa família é um campeonato de futebol society fut7 que ocorre em Mogi das Cruzes organizado pelo Mateus Martins, temos diversas informações que são anotadas a respeito dos jogos, como: Gols, assistências, desarmes, interceptações e mais, tudo isso vocês podem ver através do arquivo Google Sheets online disponibilizado a seguir:

https://docs.google.com/spreadsheets/d/1owM0oEisnNJtiqkouMIXLqeqbkJ9iwkMBIXns04GyVs/edit?gid=0#gid=0 (arquivo Google Sheets)

Está planilha é um projeto totalmente planejado para automatizar ao máximo as informações, diversas funções calculam informações automaticamente, como pontuação, que tem diversas regras de pontuação, principalmente a pontuação originada do saldo do time, que devem ser somados pela metade caso o jogador tenha pontuado com gols ou assistências.

Como este arquivo é disponibilizado online, o arquivo python fornecido nesse repositório, puxa essas informações através de uma função, que precisa apenas do nome da aba (sheet_name) do arquivo que você quer fazer as devidas transformações, assim o arquivo python lê com facilidade as informações de cada rodada, e já faz as devidas análises e tratamentos, para posteriormente podermos criarmos um dashboard visualmente mais atraente no Power BI, exemplos a seguir:

![teste1 (1)](https://github.com/user-attachments/assets/28bf4b66-1081-4eb9-a490-51eb582ac9a2)

![teste1 (2)](https://github.com/user-attachments/assets/596f6847-08a3-48de-a0db-fcc8fcb5c422)


Esses foram dados fictícios para trabalharmos o visual do projeto.

Melhorias posteriores: 
- Consigar transformar as imagens das tabelas que são preenchidas manualmente, em strings que iriam automatizar ainda mais o processo, atualmente precisamos preencher as informações obtidas de gols, assistências, desarmes e etc...
- Criar um dashboard visualmente atraente em python, para não ter que carregar os dados já tratados no python no Power BI (apesar de ser algo bem automático) obs: seria mais um desejo de criar dashboards visualmente bonitos em python.
- Estamos abertos a mais sugestões, mande uma mensagem no meu linkedin https://www.linkedin.com/in/felipe-dos-anjos-/
