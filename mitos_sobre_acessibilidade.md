
## 1. Tornar seu produto acessível é lucrativo

Talvez, se no mercado nenhum dos seus concorrentes apresentar um produto minimamente acessível, pode até ser que, tornando  seu produto acessível, sua base de clientes aumente um pouco. Então sim: teoricamente tornar seu produto pode aumentar seu lucro. Mas em geral isso não vai acontecer e provavelmente você vai gastar mais com bons desenvolvedores tornando seu produto acessível, do que com a receita  dos poucos clientes que poderão eventualmente surgir.

Mas então não vale à pena tornar um produto acessível? Em termos financeiros provavelmente não. Mas acessibilidade não é uma questão financeira, e sim um compromisso social. Todos devem poder ter acesso ao seu produto. Mais adiante veremos que o acesso não é para todos literalmente, mas o esforço é necessário.

Se acessibilidade fosse lucrativa, não precisaríamos convencer ninguém da sua importância. O mercado por si estaria empreendendo uma verdadeira corrida pela acessibilidade.

O que não se leva em consideração é que tornar um produto acessível não torna os deficientes automaticamente mais ricos. De alguma forma nós deficientes já viemos gastando nosso dinheiro. Nós precisamos comer, nos vestir e viver como todo o mundo. Poder comprar através de aplicativos acessíveis poderá tornar-nos mais autônomos, melhorar nossa qualidade de vida, nossa auto estima, o prazer de viver... mas se não houver alternativas acessíveis, vamos dar um jeito de gastar nosso dinheiro com nossas necessidades da mesma maneira. Talvez pedindo ajuda a um amigo... e quem sabe até já sejamos seus clientes! Então que tal atender-nos de maneira decente?

Você não me conhecia... entendo. Mas agora que me conhece e sabe que eu sou um cara legal, que tal pensar em mim ao desenvolver seu produto?

Se minha simpatia não for motivo suficiente para você tornar seu produto acessível, saiba que acessibilidade agora é lei. E é lei justamente para impor a necessidade àqueles que ainda não se convenceram da sua importância.

## 2. Implementar uma interface acessível é fácil

Ao estudarmos os fundamentos do HTML, percebemos que sua estrutura foi criada tendo acessibilidade em mente. A linguagem foi criada originalmente para estruturar conteúdos de texto, com links e algumas imagens. O O visual dos documentos deveria ser responsabilidade do navegador do usuário, atendendo às preferências do próprio usuário, como cores em alto contraste, eventualmente texto com letras maiores, etc.

Porém, ao longo do tempo, o uso do HTML passou a se extender para além dos limites antes imaginados para sua aplicação. Atualmente HTML passou a ser a base para praticamente todas as aplicações do dia-a-dia. E à medida em que tornamos o HTML mais interativo com o uso do javascript, não nos é mais possível interferir no visual elaborado pelos desenvolvedores, ou corremos o risco de piorar ainda mais a experiência do usuário.

Isso implica que passou a ser responsabilidade do desenvolvedor atender às diferentes necessidades dos usuários. Algumas bastante óbvias, como apresentar o mesmo conteúdo em uma tela grande e uma tela pequena, outras nem tanto, como apresentar o mesmo conteúdo em diferentes esquemas de cores, apresentar o conteúdo sem animações ou ainda cuidar da maneira como leitores de tela irão narrar o conteúdo.

O HTML precisou ser extendido com novas tags e atributos que possibilitem a criação de novos componentes que não são nativos da linguagem. Controlar o comportamento destes componentes com javascript não é trivial. Além disso, diferentes leitores de tela, diferentes navegadores, se comportam de maneiras diferentes em relação à acessibilidade. Não há outro caminho que não seja testar exaustivamente, em cada sistema operacional usado pelo seu público, em cada tipo de dispositivo, cada tamanho de tela, cada navegador, cada leitor de tela, cada método de entrada (teclado, mouse, touch...).

## 3. Acessibilidade é para todos

Na verdade não. Todos abrange uma gama muito vasta de gente das mais variadas. Crianças, jovens, adultos e idosos; pessoas lúcidas, distraídas, bêbadas, confusas, irritadas, com déficit de atenção, senis; pessoas daltônicas, com baixa visão, cegas, surdas, com debilidades motoras ou sem um ou mais membros.., além das infinitas misturas disso tudo.

O que nos cabe é pensar em um "desenho universal", tentando atender a critérios mínimos que possam atingir a maior gama de necessidades. Mas talvez sua avó nunca venha a entender como é mesmo que funciona aquele aplicativo que você já explicou mais de uma dezena de vezes.

Foi pensando em critérios que o Consórcio Mundial para a Padronização da Internet - o W3C - desenvolveu as "Diretrizes de acessibilidade para conteúdos Web", ou WCAG.

## 4. Devemos seguir à risca o WCAG

Atender os critérios propostos pelo WCAG traz uma vantagem: por ser um documento elaborado por agentes do mundo todo, certamente você poderá usá-lo em sua defesa caso sua organização tenha de responder judicialmente  em casos de falta de acessibilidade.

Porém, as diretrizes propostas no WCAG não são leis ou regras, e existem exceções no próprio WCAG, que indicam que a experiência do usuário não deve ser pautada por teorias e sim por aquilo que se mostra mais vutilizável na prática.

Como exemplo, podemos citar a página de resultados de pesquisas do Google,  - talvez uma das mais acessadas no mundo - que possui uma estrutura de cabeçalhos de nível 1, cabeçalhos de nível 2 e cabeçalhos de nível 3. Embora no WCAG se recomende somente um único cabeçalho de nível 1, a página do Google possui uns 3, e o Google tem uma boa justificativa para isso.

Quer dizer que, se você souber o que está fazendo e se fizer bem feito, não vai precisar se preocupar em ser rígido com o WCAG. Por outro lado se tiver dúvidas, aí o melhor caminho é seguir suas recomendações.

## 5. Ao terminar meu projeto, devo submetê-lo a testes de acessibilidade

Embora esta seja a prática mais comum, é a mais ineficiente. Existem até instituições especializadas em testar produtos digitais, capazes de produzir infindáveis relatórios de falhas.

Porém, acessibilidade deve ser pensada durante todo o projeto, desde a escolha dos melhores componentes a serem utilizados, cores, estruturas de conteúdo, metodologias de interação, etc, até a execução e os testes finais. Obviamente isto exige técnicos especializados, que saibam operar minimamente um leitor de tela, que conheça a fundo os atributos role e aria e que saiba como produzir interações adequadas usando os eventos corretos do javascript.

Se sua equipe não possui um técnico com essa especialidade, considere contratar uma consultoria que possa orientar, testar e propôr soluções.

Relatórios de falha normalmente são inúteis, porque frequentemente quem os produz não possui conhecimentos para orientar a maneira correta de corrigir os problemas - que tampouco sua equipe soube solucionar. Pior ainda se a produção de relatórios for deixada para o final do projeto, quando não há mais recursos para corrigir os problemas encontrados. Normalmente são feitas apenas correções críticas enquanto a usabilidade que nunca havia sido discutida, permanecerá para sempre uma porcaria.

Frequentemente discuto soluções com as equipes com as quais trabalho e descobrimos que trocar um componente por outro pode tornar a usabilidade melhor para todos. Isso vai muito além de apontar falhas e produz resultados mil vezes melhor.
