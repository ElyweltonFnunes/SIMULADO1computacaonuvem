# SIMULADO1computacaonuvem

1. Qual a diferença entre nginx:alpine e o contêiner comunicado?

nginx:alpine é a imagem utilizada como base para criar o contêiner. O comunicado é o contêiner em execução criado a partir dessa imagem.

2. O que significa o mapeamento 8090:80?

A porta 8090 do ambiente é direcionada para a porta 80 do Nginx dentro do contêiner. Assim, ao acessar localhost:8090, a requisição chega ao Nginx na porta 80.

3. Qual saída comprova que a página solicitada respondeu?

A saída do comando curl http://localhost:8090, pois ela mostra o conteúdo HTML da página, incluindo a mensagem “Comunicado interno disponível”.
