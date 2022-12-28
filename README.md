# Bot de Votacao em Python
Bot simples de votação para o realite Corrida das Blogueiras, desenvolvido em Python.

## Como rodar:

- python robo.py

## Necessario
- Ter Python 3 instalado

## Conceito

- São 3 participantes na votação final, sendo 1 Elay, 2 Erick e 3 Jade.

- A votação possui reCaptcha do Google "Não sou robô". 

- O envio da votação é feito por um POST, contendo um body com:
     
     blogueira -> ID_BLOGUEIRA
     g-recaptcha-response  ->  NÃO SOU ROBÔ
     
O re-Captcha serve apenas para confirmar que não é um robo. No envio do voto, ele não validado.

Com isso conseguimos enviar o voto para o candito desejado, coletando o serial de um recaptcha.
