Contador do período de teste

Página simples com um contador regressivo (dias, horas, minutos e segundos) até o fim do período de teste do Intelligence. Ela é exibida dentro do Appcues por meio de um iframe.

Conteúdo
index.html: página única com o contador. Não depende de nenhum outro arquivo.
Data de término

A data fica no script, dentro do index.html:

js
var end = new Date('2026-11-03T23:59:59-03:00');
O formato é AAAA-MM-DDTHH:MM:SS, seguido do fuso horário.
-03:00 corresponde ao horário de Brasília.
Para mudar o prazo, altere somente essa linha e publique o arquivo de novo.
