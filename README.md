# ROTAS-JAVA-SPRINGBOOT-API-MVC
Projeto de rotas com padrão MVC, utilizando a rota raiz para guiar para um calculo de notas, com @RequestParam e o calculo da média. Utilizamos API para fazer a busca de um CEP que o usuário digitar. Utilizamos Factory Method para retornar uma nova instância de endereco criando uma classe separada.


Projeto de Montagem de Rotas

Esse é um projeto de montagem de rotas, utilizando SpringBoot, dependências e API de CEP. Trabalhamos com o padrão Factory Method.

Para acessar as rotas basta digitar localhost:4000/notas para acessar a rota de cálculo de notas.

Para acessar as rotas basta digitar localhost:4000/cep para acessar a rota de cep.

Mas basta também clicar no NAVBAR e escolher qual serviço deseja acessar

Utilizamos o padrão MVC(Model-View-Controller) nesse projeto

Temos o Model sendo endereco.java e EnderecoFactory.java armazenando informações de endereço

Temos VIEW em cada um dos templates

O sistema possui 3 controllers, sendo cepController, IndexController e Notas Controller

Utilizamos Factory Method criando a classe "EnderecoFactory.java" que encapsula

a lógica de criação de instâncias da classe "endereco". Ele se apresenta no método "createEndereco"

que retorna uma instância nova de "endereco", criando uma classe separada

e abstraindo a criação de objetos.

Participantes: Naira Rivelli, Ayrton Senna e João Rosa
