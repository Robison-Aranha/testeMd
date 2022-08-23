## Integração:
A integração será feita utilizando o banco de dados PostgreSQl, teremos inicialmente uma tabela de identificação e descrição do usuário.
```
Usuário:
 - Id
 - Nome
 - Email
 - Senha
 - Foto(opcional)

 ```
 
 
## Autenticação: 
- Como forma de fazer a autenticação de usuário, iremos utilizar a funcionalidade do Spring Boot intitulada de Basic Authentic.  
 
## Funcionalidades do Sistema:
    - As funcionalidades do nosso sistema serão listadas a seguir:
 
###### Cadastro:
Ao se cadastrar em nosso sistema o usuário irá ter que fornecer as seguintes informações:
 - Nome
 - Email
 - Senha
 - Foto(opcional)
>Dessa forma será possível autenticar e identificar cada usuário como único.
###### Seleção De jogo:
```
Após o usuário fazer o login, ele irá poder selecionar qual jogo ele gostaria de jogar.
```
###### Criar uma sala de jogo(dentro do jogo Stop):
Ao selecionar a opção dentro do jogo de criar a sala de jogos, o usuário deverá informar: 
```
 - Quantidade rodadas do jogo
 - Quais serão os tópicos do jogo, ex: Nome, País.
 - O tempo de duração de cada rodada 
```
###### Entrar em uma sala de jogo:
```
Após a sua autenticação na plataforma e a entrada no jogo STOP, o usuário irá  conseguir entrar em alguma sala de jogo, logo após a seleção da opção de entrar na sala e o mesmo   inserir o código de identificação da sala. 
```
###### Utilizar o chat:
```
A comunicação através de mensagens de texto, será possível quando o usuário estiver dentro da sala de jogo.
```
###### Envio de respostas ao jogo:
```
O usuário enquanto estiver dentro da sala de jogo poderá responder ao questionário de forma individual cada resposta.
```
 
