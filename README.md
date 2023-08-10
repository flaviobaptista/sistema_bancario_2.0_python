<h1 style="color: #b298dc;">Gerenciamento de Conta Bancária VS 2.0</h1>

<img style="margin-right: 50px;" align="left" alt="Developer Art" width="250px" src="./img/1026870_OJZ2IH1.png">
<br>
<br>
<br>
<br>
<p align="justify">
Este projeto consiste em um sistema um pouco mais aprimorado de gerenciamento de conta bancária, esta versão do sistema foi desenvolvida com foco na usabilidade e na expansão das capacidades do usuário.
<br>
Uma das principais características do sistema é a utilização de um menu interativo, no qual o usuário pode escolher as opções desejadas através de um número correspondente. O menu foi projetado para proporcionar uma experiência intuitiva ao usuário, tornando a interação com o sistema mais fácil e acessível.
<br>
Além disso, o sistema foi aprimorado com a implementação de funções modulares, proporcionando uma organização mais clara e eficiente do código. Isso possibilita a manutenção e extensão do projeto de forma mais prática e compreensível.
<br>
Em suma, o sistema de gerenciamento de conta bancária oferece uma solução prática e funcional para controlar as movimentações financeiras, possibilitando que o usuário realize operações bancárias de forma eficiente e segura.
<p>

<h3 style="color: #b9faf8;">Funcionalidades</h3>

- **Depósito:** Os usuários podem realizar depósitos em suas contas, inserindo o valor desejado.

- **Saque:** Os usuários podem fazer saques de suas contas, desde que o valor solicitado não exceda o saldo disponível e o limite de saques diários.

- **Extrato:** Os usuários podem verificar o extrato de movimentações realizadas em suas contas, visualizando detalhes sobre depósitos e saques efetuados.

- **Limite de Saque:** O sistema possui um limite máximo de saques diários, evitando que os usuários excedam o número permitido de saques em um único dia.

- **Criação de Contas:** Os usuários podem criar novas contas bancárias associadas a um titular, permitindo um gerenciamento eficiente de múltiplas contas.

- **Listagem de Contas:** A funcionalidade de listagem de contas exibe informações detalhadas sobre as contas existentes, facilitando o acompanhamento das finanças.

- **Criação de Usuários:** O sistema permite a criação de usuários, proporcionando um controle mais completo e seguro das contas bancárias.

- **Listagem de Usuários:** A funcionalidade de listagem de usuários exibe informações detalhadas existentes, facilitando o acompanhamento dos cadastros.

<h2 style="color: #b9faf8;">Requisitos</h2>
- Python 3.x
<br>
<h3 style="color: #b298dc;">Como Utilizar</h3>

1. Clone o repositório para o seu computador:

2. Navegue até o diretório do projeto:

3. Execute o script Python:

4. Siga as instruções apresentadas no menu para realizar as operações bancárias.


<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 1:</span> Realizar um depósito de R$ 3000,00</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 1 ***<<< DIGITE O NÚMERO E APERTE ENTER NO TECLADO PARA DEPOSITAR***
- Informe o valor do depósito: 3000 ***<<< DIGITE O VALOR DO DEPÓSITO E APERTE ENTER NO TECLADO***
<pre>
=============== MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

Digite aqui a opção desejada => 1
Informe o valor do depósito: 3000

**** Depósito realizado com sucesso! ***

</pre>

</details>

<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 2:</span> Tentar sacar R$ 200,00 sem depositar (excedendo o saldo disponível)</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 2 ***<<< DIGITE O NUMERO 2 E APERTE ENTER NO TECLADO PARA SACAR***
- Informe o valor do SAQUE: 200 ***<<< DIGITE O VALOR DO SAQUE E APERTE ENTER NO TECLADO***

<pre>
=============== MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

Digite aqui a opção desejada => 2
Informe o valor do saque: 200

Operação falhou! Você não tem saldo suficiente.

</pre>

</details>

<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 3:</span> Realizar três saques de R$ 50,00 cada (excedendo o limite de saques)</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 2 ***<<< DIGITE O NUMERO 2 E APERTE ENTER NO TECLADO PARA REALIZAR O SAQUE***
- Informe o valor do SAQUE: 50 ***<<< DIGITE O VALOR DO SAQUE E APERTE ENTER NO TECLADO***

===================== <span style="color: #c7f9cc;">REPITA O PROCESSO 4 VEZES</span> =====================


<pre>
=============== MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

Digite aqui a opção desejada => 2
Informe o valor do saque: 50

Saque realizado com sucesso!

=============== MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

Digite aqui a opção desejada => 2
Informe o valor do saque: 50

Saque realizado com sucesso!

=============== MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

Digite aqui a opção desejada => 2
Informe o valor do saque: 50

Saque realizado com sucesso!

=============== MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

Digite aqui a opção desejada => 2
Informe o valor do saque: 50

Operação falhou! Número máximo de saques excedido.


</pre>

</details>

<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 4:</span> Exibindo extrato</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 3 ***<<< DIGITE O NUMERO 3 E APERTE ENTER NO TECLADO PARA VER O SALDO NO EXTRATO***

<pre>
================ MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.
__________________________________________

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

__________________________________________
Digite aqui a opção desejada => 3

================ EXTRATO ================
Depósito:       R$ 3000.00
Saque:          R$ 50.00
Saque:          R$ 50.00
Saque:          R$ 50.00


Saldo:          R$ 2850.00
==========================================

</pre>

</details>
<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 5:</span> Criando Usuário</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 6 ***<<< DIGITE O NUMERO 6 E APERTE ENTER NO TECLADO E SIGA CONFORME O EXEMPLO***

<pre>
================ MENU ================    
Olá, seja bem-vindo...

Escolha uma das opções a seguir.
__________________________________________

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

__________________________________________
Digite aqui a opção desejada => 6
Informe o CPF (somente número): 99966644432
Informe o nome completo: Jonas Miguel Oliveira
Informe a data de nascimento (dd-mm-aaaa): 12-05-1995
Informe o endereço (logradouro, nro - bairro - cidade/sigla estado): Rua dois, 325 - Nova aldeia - Osasco/SP      
*** Usuário criado com sucesso! ***   


</pre>

</details>

<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 6:</span> Criando uma Conta</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 4 ***<<< DIGITE O NUMERO 4 E APERTE ENTER NO TECLADO E DIGITE O MESMO CPF DO USUÁRIO QUE DESEJAR CRIAR A CONTA***

<pre>
================ MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.
__________________________________________

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

__________________________________________
Digite aqui a opção desejada => 4
Informe o CPF do usuário: 99966644432

*** Conta criada com sucesso! ***



</pre>

</details>

<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 7:</span> Listando Contas</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 5 ***<<< DIGITE O NUMERO 5 E APERTE ENTER NO TECLADO***

<pre>
================ MENU ================    
Olá, seja bem-vindo...

Escolha uma das opções a seguir.
__________________________________________

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

__________________________________________
Digite aqui a opção desejada => 5
====================================================================================================
Agência:        0001
C/C:            1
Titular:        Jonas Miguel Oliveira




</pre>

</details>


<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 8:</span> Listando Usuários</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 7 ***<<< DIGITE O NUMERO 7 E APERTE ENTER NO TECLADO***

<pre>
================ MENU ================
Olá, seja bem-vindo...

Escolha uma das opções a seguir.
__________________________________________

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

__________________________________________
Digite aqui a opção desejada => 7
====================================================================================================

CPF:    99966644432
Nome:   Jonas Miguel Oliveira
Data Nascimento:        12-05-1995
Endereço:       Rua dois, 325 - Nova aldeia - Osasco/SP



</pre>

</details>


<h3 style="color: white;"><span style="color: #ff7096;">Exemplo 9:</span> Saindo do sistema</h3> 

<details>
<summary style="color: #a5ffd6;">Exemplo</summary> 

- Selecionar a opção: 8 ***<<< DIGITE O NUMERO 8 E APERTE ENTER NO TECLADO PARA SAIR***

<pre>
================ MENU ================    
Olá, seja bem-vindo...

Escolha uma das opções a seguir.
__________________________________________

[1]----> Depositar
[2]----> Sacar
[3]----> Extrato
[4]----> Nova conta
[5]----> Listar contas
[6]----> Novo usuário
[7]----> Listar usuário
[8]----> Sair

__________________________________________
Digite aqui a opção desejada => 7
Obrigado pela preferência! :)

</pre>

</details>

<br>
<br>
<br>
<br>
<br>

<h1 style="color: #efebce;">Referências e Atribuições</h1>

<details align="left">
  <summary>Clique para visualizar</summary> 

  - GitHub Stats by <a href="https://github.com/anuraghazra/github-readme-stats">anuraghazra</a>
 <a href="https://br.freepik.com/vetores-gratis/projeto-do-fundo-do-banco_1026870.htm#query=bank&position=10&from_view=search&track=sph#position=10&query=bank">Imagem de GraphiqaStock</a> no Freepik
  <br>
  <br>
  <br>

 
  <div align="center">Created by <a href="https://github.com/flaviobaptista">Flávio P. Baptista</a>.</div>
    <br>

</details>

