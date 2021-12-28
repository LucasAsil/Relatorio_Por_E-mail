# Relatorio_Por_E-mail
###Tratando de dados Excel e enviando por E-mail automaticamente###

Elaborei esse código através de um minicurso do canal “Hashtag programação”, onde usei Python e as bibliotecas(Pandas, smtplib e email.message)

Comecei importando um arquivo .xlsx(Excel). 

![importando](https://user-images.githubusercontent.com/68728828/147603592-64efb172-969f-4959-be83-b3dbd27fe6e6.jpg)

Então calculei o faturamento das lojas, quantidade vendidas por ambas e a média das vendas. 

![calculo](https://user-images.githubusercontent.com/68728828/147603772-b167f3b4-7224-4d09-8383-d70aa1431f7d.jpg)

Depois precisei mandar um relatório formatado por E-mail. Foi meio complicado de inicio, pois o primeiro método que vi usava o outlook, mas como é um programa pago do pacote office não tinha acesso. Mas então através do mesmo canal achei uma função que usava o Gmail.

![relatorio](https://user-images.githubusercontent.com/68728828/147603787-7cfe5187-e402-49fa-98f7-6af63ae9b836.jpg)


ATENÇÃO — Para que o código funcione corretamente, é necessário entrar na configuração de segurança do gmail da conta que esta enviando, e ativar a opção “Acesso à ‘app’ menos seguro”, assim ele conseguira logar e enviar o E-mail.

![liberando_email](https://user-images.githubusercontent.com/68728828/147603804-b23aedc6-dc3b-476e-b4be-f678d773b577.jpg)
