Como executar

1. Instalar o Newman

No terminal, execute:

npm install -g newman

Para verificar a instalação:

newman -v

2. Executar a coleção

Com o terminal aberto na pasta que contém o arquivo da coleção, execute:

newman run "demo qa.postman_collection.json"

O Newman executará as requisições e apresentará no terminal os resultados das validações, incluindo os testes aprovados e reprovados.