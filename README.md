# Relatorio_Por_E-mail
## Tratando de dados Excel e enviando por E-mail automaticamente ##

Elaborei esse código através de um minicurso do canal “Hashtag programação”, onde usei Python e as bibliotecas(Pandas, smtplib e email.message)

Comecei importando um arquivo .xlsx(Excel). 

![importando](https://user-images.githubusercontent.com/68728828/147604088-ce16b59e-37c7-4a20-9871-dc2d33e08fd0.jpg)

Então calculei o faturamento das lojas, quantidade vendidas por ambas e a média das vendas. 

![calculo](https://user-images.githubusercontent.com/68728828/147604101-5ee898eb-476e-43af-a0ca-bb79b07befe2.jpg)

Depois precisei mandar um relatório formatado por E-mail. Foi meio complicado de inicio, pois o primeiro método que vi usava o outlook, mas como é um programa pago do pacote office não tinha acesso. Mas então através do mesmo canal achei uma função que usava o Gmail.

![funcao](https://user-images.githubusercontent.com/68728828/147604105-7db789a0-1dc3-4f7e-9e02-5ca7d32f562a.jpg)

ATENÇÃO — Para que o código funcione corretamente, é necessário entrar na configuração de segurança do gmail da conta que esta enviando, e ativar a opção “Acesso à ‘app’ menos seguro”, assim ele conseguira logar e enviar o E-mail.

![liberando_email](https://user-images.githubusercontent.com/68728828/147604109-1fc4992b-8aa9-4a21-b3dc-63170306bcfe.jpg)
