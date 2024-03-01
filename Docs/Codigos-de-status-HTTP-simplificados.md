# Códigos de Status HTTP

**Bem-vindo(a) a este guia simples sobre os códigos de status HTTP!**

> Este README tem como objetivo fornecer uma visão geral rápida e de fácil compreensão sobre o que são os códigos de status HTTP e como eles são utilizados no desenvolvimento web. Se você é um(a) desenvolvedor(a) front-end ou back-end, entender esses códigos será extremamente útil.

- O que são Códigos de Status HTTP?
> Códigos de status HTTP são códigos padronizados que servidores web usam para comunicar o resultado de uma tentativa de compreender e satisfazer um pedido do cliente (geralmente um navegador ou aplicativo). Estes códigos são parte do protocolo HTTP e são divididos em cinco categorias, cada uma indicando uma classe de resposta.

**1. Informativo (100-199)**

> 100 Continue: O servidor recebeu os cabeçalhos iniciais da requisição e o cliente deve continuar a enviar o corpo da requisição.
> 
> 101 Switching Protocols: O cliente pediu para o servidor trocar protocolos e o servidor concordou em fazer isso.

**2. Sucesso (200-299)**

> 200 OK: A requisição foi bem-sucedida e a resposta enviada pelo servidor depende do método da requisição (GET, POST, etc.).
> 
> 201 Created: Uma nova resource foi criada com sucesso.
> 
> 204 No Content: A requisição foi bem-sucedida mas o servidor não tem conteúdo para enviar na resposta.

**3. Redirecionamento (300-399)**

> 301 Moved Permanently: A resource solicitada foi movida permanentemente para uma nova URL.
> 
> 307 Temporary Redirect: A resource foi movida temporariamente para uma nova URL, e futuras requisições devem continuar usando a URL original.

**4. Erro do Cliente (400-499)**

> 400 Bad Request: O servidor não conseguiu entender a requisição devido à sintaxe inválida.
> 
> 401 Unauthorized: A autenticação é necessária e falhou ou ainda não foi fornecida.
> 
> 404 Not Found: O servidor não encontrou a resource solicitada.

**5. Erro do Servidor (500-599)**

> 500 Internal Server Error: O servidor encontrou uma condição inesperada que impediu de atender à requisição.
> 
> 503 Service Unavailable: O servidor não está pronto para lidar com a requisição, geralmente por estar sobrecarregado ou em manutenção.
