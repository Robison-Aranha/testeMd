# Don`t Stop
 > Sistema de integração social de equipes com trabalho majoritariamente remoto.
 
## O Problema:
> O atual modelo de trabalho remoto dificulta a integração social de novos colaboradores em um ambiente profissional, 
> principalmente em equipes muito grandes, pois é uma tendência natural do ser humano se fechar em pequenos grupos sociais.
> Este comportamento natural acaba acarretando alguns problemas, tanto para a empresa quanto para o contribuinte, como a falta de sensação de pertencimento, queda de produtividade e > a falta do debate, algo extremamente crucial para o aprimoramento e o surgimento de novas ideias.
    
 
## Fatores psicológicos:
> Segundo o historiador e filósofo israelense Yuval Noah Harari: 
>“A pesquisa de acompanhamento mostrou que os macacos órfãos de Harlow cresceram emocionalmente perturbados, embora tivessem recebido toda a nutrição de que precisavam. Eles nunca  se encaixaram na sociedade dos macacos, tinham dificuldades de comunicação com outros macacos e sofriam de altos níveis de ansiedade e agressão. A conclusão era inevitável: os macacos devem ter necessidades e desejos psicológicos que vão além de suas necessidades materiais e se não forem atendidos, sofrerão muito. Nas décadas seguintes, numerosos estudos mostraram que essa conclusão se aplica não apenas aos macacos, mas a outros mamíferos, assim como às aves.” (Sapiens: Uma Breve História da Humanidade, 2011, p. 294).
> “Os humanos, como os chimpanzés, têm instintos sociais que permitiram que nossos ancestrais formassem amizades e hierarquias, caçassem ou lutassem juntos.
> No entanto, como os instintos sociais dos chimpanzés, os dos humanos foram adaptados apenas para pequenos grupos íntimos.” (Sapiens: A Brief history of Humankind, 2011, p. 28).
> Assim como os macacos, seres humanos apresentam necessidades emocionais e sofrem distúrbios psicológicos em consequência ao isolamento social, não só nos anos iniciais de desenvolvimento, mas quando exposto a situações prolongadas, não faltam referências sobre o assunto após a pandemia da COVID-19, como no estudo: [Como o isolamento social afeta o cérebro – IBNeuro](https://ibneuro.com.br/blogs/noticias/como-o-isolamento-social-afeta-o-cerebro).
    
 
 
## Problemas Gerados:
> A falta do contato pessoal, seja durante o expediente ou nas pausas para o cafezinho, pode afetar não só o bem estar do indivíduo, mas o desenvolvimento da empresa como um todo,  pois o contato pessoal permite a troca de informação, sejam elas relevantes ou não, mas que podem levar a insights e ao surgimento de novas ideias, essa questão vai muito de acordo  > com a filosofia de Sócrates do uso do debate para o enriquecimento das ideias, usado hoje como método de ensino para aprimorar o senso crítico de crianças, citado no artigo:  [Adiscussão como ferramenta para o processo de socialização e para a construção do pensamento](https://www.scielo.br/j/edur/a/k7GGYYaPycJj7ZFDcKtvnBjc/?lang=pt).
> Outro problema que pode ser gerado é a falta de sensação de pertencimento, pois em equipes muito grandes, fica muito difícil manter o contato com todos, justamente pela limitação  do ser humano de manter contato com um grupo muito grande de pessoas, esta falta de contato, não permite o surgimento do sentimento de empatia pelo próximo, e cria a sensação
> “ninguém se importa”.
> Alguém que se sente não pertencente à organização onde atua e para a qual contribui, pode apresentar alguns sinais: procrastinação, baixa autoestima, falta de iniciativa, falta de > confiança (em si mesmo e no outro ou em relação à organização); problemas relacionados à saúde física, mental e emocional. Mais sobre o assunto pode ser lido no artigo: [Senso de  Pertencimento e a relação com o Trabalho](https://pt.linkedin.com/pulse/> senso-de-pertencimento-e-rela%C3%A7%C3%A3o-com-o-trabalho-tatiani-tozetti#:~:text=Algu%C3%A9m%20que%20se%20sente%20n%C3%A3o,sa%C3%BAde%20f%C3%ADsica%20mental%20e%20emocional).
> Um outro fator que a  sensação de não pertencimento pode gerar é a famosa Síndrome do impostor, que pode ocorrer pela falta de compreensão em como o sistema funciona, gerando a  sensação de que o indivíduo não é digno de estar onde está.
> Ao trabalhar sozinho em home office fica muito mais fácil cair em uma espiral de dúvidas sobre si mesmo, nossa mente fica muito mais suscetível a pensamentos de auto sabotagem, já > dizia Platão: “Vencer a si próprio é a maior das vitórias”, nossa mente pode ser nosso pior inimigo. Mais sobre o assunto pode ser lido no artigo: [O trabalho remoto em home office aumenta o risco da síndrome do impostor?](https://blog.trello.com/br/trabalho-remoto-home-office)
    
 
## Soluções estudadas:
 > Os jogos corporativos influenciam diretamente em três principais elementos da empresa: na prática do trabalho em equipe, no desenvolvimento e aperfeiçoamento de competências e habilidades dos colaboradores e no acolhimento de novos profissionais.
    
 
 
 - [4 maneiras de promover o sentimento de pertencimento no trabalho](https://forbes.com.br/carreira/2019/09/4-maneiras-de-promover-o-sentimento-de-pertencimento-no-trabalho/#foto1)
 - [Jogos Corporativos: O que são e como utilizar em seus treinamentos](https://risedh.com.br/blog/jogos-corporativos-o-que-e-e-como-utilizar-em-seus-treinamentos/)
 - [Já ouviu falar em jogos corporativos? Veja como eles podem facilitar a integração entre colaboradores!](https://www.pontotel.com.br/jogos-corporativos/)
 - [Jogos corporativos para engajar e motivar colaboradores - Ludos Pro.](https://www.ludospro.com.br/blog/jogos-corporativos#:~:text=Os%20jogos%20corporativos%20s%C3%A3o%20atividades,solucionar%20situa%C3%A7%C3%B5es%20dentro%20das%20organiza%C3%A7%C3%B5es)



## Integração:
 > A integração será feita utilizando o banco de dados PostgreSQl, teremos inicialmente uma tabela de identificação e descrição do usuário.

    
    Usuário:
    - Id
    - Nome
    - Email
    - Senha
    - Foto(opcional)


 
 
## Autenticação: 
 > Como forma de fazer a autenticação de usuário, iremos utilizar a funcionalidade do Spring Boot intitulada de Basic Authentic.  
 
## Funcionalidades do Sistema:
 > As funcionalidades do nosso sistema serão listadas a seguir:
 
- ###### Cadastro:
    > Ao se cadastrar em nosso sistema o usuário irá ter que fornecer as seguintes informações:

    - Nome
    - Email
    - Senha
    - Foto(opcional)

     > Dessa forma será possível autenticar e identificar cada usuário como único.

 - ###### Seleção De jogo:

    > Após o usuário fazer o login, ele irá poder selecionar qual jogo ele gostaria de jogar.
    
 - ###### Criar uma sala de jogo(dentro do jogo Stop):
    
    > Ao selecionar a opção dentro do jogo de criar a sala de jogos, o usuário deverá informar: 

    - Quantidade rodadas do jogo
    - Quais serão os tópicos do jogo, ex: Nome, País.
    - O tempo de duração de cada rodada 
    
 - ###### Entrar em uma sala de jogo:
   
    > Após a sua autenticação na plataforma e a entrada no jogo STOP, o usuário irá  conseguir entrar em alguma sala de jogo, logo após a seleção da opção de entrar na sala e o mesmo   inserir o código de identificação da sala. 
    
 - ###### Utilizar o chat:
   
    > A comunicação através de mensagens de texto, será possível quando o usuário estiver dentro da sala de jogo.
    
 - ###### Envio de respostas ao jogo:
    
    > O usuário enquanto estiver dentro da sala de jogo poderá responder ao questionário de forma individual cada resposta.
    
 
