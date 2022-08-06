Para executar a aplicação siga os seguintes passos:

1 - Buildando a imagem: docker image build -t conversao-temperatura .

2 - Verificando a imagem criada: docker image ls

3 - Criando o container: docker container run -d -p 8080:8080 conversao-temperatura

OBS: lembrando que os parâmentros -d é para executa o container em modo daemon e o -p para expor a porta.

4 - Testando a aplicação: colocar o endereço no browser http://localhost:8080
