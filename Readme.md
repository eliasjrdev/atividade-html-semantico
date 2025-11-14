Esta atividade foi desenvolvida com o objetivo de demosntrar meus conhecimentos práticos e teóricos sobre as tags semânticas do HTML5.
O tema da página a ser desenvolvida era livre então decidi fazer uma página para um restaurante, usando todas as tags exigidas, sendo elas:

"header", "nav" (com uma lista de links)

"main"

"section"

"article"

"aside"

"footer"

"h1" a "h3" (uso hierárquico correto)

"p", "strong", "em"

"figure" e "figcaption" (com uma imagem em assets/)

"img" com alt adequado

"time" (com atributo datetime)

"address"

"table", "caption", "thead", "tbody", "tfoot" (tabela simples de dados relacionados)

"details" e "summary"

"mark"

"abbr" (com title)

"form" com "fieldset" e "legend" (pelo menos um campo input e um button)

"dialog" (uso demonstrativo; pode ser aberto via botão)

A atividade também exigia o uso de alguns arquivos obrigatórios, sendo eles:
1 arquivo index.html
1 arquivo css
1 arquivo Readme.md
1 pasta assets contendo uma imagem
Todos estes requisitos fora atendidos !


Todas as tags HTML no projeto contém uma explicação imediatamente acima dela (como exigido) respondendo a 3 perguntas seobre as mesmas: 

1 - FUNÇÃO SEMÂNTICA DA TAG:  

2 - PORQUE USEI NESTE CONTEXTO: 

3 - EXEMPLO DE IMPACTO EM ACESSIBILIDADE OU SEO: 

E abaixo, trago uma explicação mais detalhada para cada tag utilizada:

1. "header"

Representa a área de cabeçalho da página ou de uma seção. Ela foi usada para agrupar o logotipo e o título principal, facilitando a identificação imediata do tema do site. Em SEO, essa tag contribui para destacar o conteúdo introdutório da página e em acessibilidade ajuda leitores de tela a localizar a área inicial do documento.
Essa tag Deixa claro o propósito do conteúdo para desenvolvedores e máquinas, melhorando a organização e a legibilidade do código e estruturalmente,
Permite a criação de uma estrutura lógica e hierárquica para o documento. 

2. "nav"

Esta foi utilizada para envolver os links de navegação do site. Ela informa aos mecanismos de busca e leitores de tela que aquele bloco contém links principais para outras seções. Isso melhora tanto o SEO quanto a experiência de navegação para usuários de tecnologias assistivas. Imagine por exemplo que um usuário com deficiencia visual está usando esta página, a tecnologia assistiva que ele estaria usando poderia através da tag <nav> identificar para o usuário de antemão, todas as seções que o site possui.

3. "main"

Esta tag identifica o conteúdo principal da página, que é único e diretamente relacionado ao propósito do site. O uso dessa tag ajuda leitores de tela a pular conteúdo repetitivo como menus e headers. Em SEO, indica aos motores de busca qual parte da página é realmente relevante.
Dentro da tag "main" é comum vermos outras tags que compõem e estruturam o conteúdo principal do documento, como "section" e "div" isso denota que a tag "main" é responável por englobar todos esses elementos que são blocos do conteúdo principal. 

4. "section"

Esta tag foi usada para dividir o conteúdo em blocos temáticos, como "Sobre nós", "Serviços" ou "Contato". Ela fornece uma estrutura clara para o conteúdo e facilita a leitura pelos mecanismos de busca. Em acessibilidade, ajuda a segmentar o conteúdo em partes lógicas permitindo que leitores de tela conseguem navegar facilmente entre cada tópico do documento.

5. "article"

Esta tag representa um conteúdo independente, como um post ou item destacado. Utilizei ela para englobar o texto da história do restaurante 
porque é uma parte do conteúdo que é autosuficente fora deste conteúdo específico. E esta tag é semânticamente adequada para estes
casos. Ela melhora o SEO ao deixar claro quais partes possuem conteúdo autônomo e facilita navegação de usuários com leitores de tela.

6. "aside"

Esta tag é usada para conteúdos complementares, como informações extras, promoções ou links externos. Ela separa informações não essenciais do fluxo principal do texto. Por isso, usei nesta página para englobar o conteúdo sobre "o prato destaque do mês" porque é uma informação extra, que não afetaria o conteúdo principal caso não estivesse ali.

7. "footer"

Esta tag é geralmente aplicada ao final do documento para informações como direitos autorais e contatos. Ou seja, ela é ideal para comportar conteúdos de rodapé,  por isso usei nesta página para englobar os conteúdos de endereço, CNPJ, contatos, e copyright. Isso ajuda por exemplo, leitores de tela a identificar que aquele é o conteúdo final da página. 

8. "h1" a "h3"

As tags h1 a h6 serve para organizar de maneira hierarquica titulos e subtitulos, muita gente usa essas tags para fins visuais (Colocar titulos com tamanhos de fontes maiores ou menores) mas não é para esse fim que elas devem ser usadas. Mas sim, para estruturar de maneira lógica o conteúdo, dividindo entre titulos e subtitulos. Neste caso, a tag h1 seria considerado o titulo com maior relevancia e a medida que vai se aproximando do h6
vai ficando menos relevante. 

9. "p"

Esta tag tem o significado semântico de "parágrafo" ela indica que o conteúdo que esta dentro dela é um bloco de texto que forma um parágrafo. No contexto desta página por exemplo, além de outros momentos, eu usei para contar a história do restaurante em 2 parágrafos. Usar a tag <p> para estes casos ajuda os motores de busca identificar melhor o conteúdo e melhora a acessibilidade e indexação da página. 

10. "strong"

Esta tag é ultilizada para destacar trechos de conteúdos que são considerados "importantes" dentro do documento. Elementos que são envoltos com a tag "strong" normalmente vão aparecer em negrito na página, mas é importante ter em mente que não é para isso que essa tag serve, ela deve ser usada buscando alcançar um objetivo semântico e não visual. Ou seja, não deve ser usada só para deixar um texto em negrito, mas para pontuar que aquele trecho possui um grau de importancia mais relevante que o resto do trecho.

11. "em"

Assim como a tag "strong"a tag "em" destaca um trecho de um conteúdo ou uma palavra. Mas existem algumas diferenças claras entre elas. Visualmente por exemplo, "strong" destaca o texto deixando negrito, enquanto "em" deixa em itálico. E a diferença mais importante é semântica. "em" da ênfase ou mudança na entonação da fala, como se o leitor estivesse destacando aquela palavra ao falar. Leitores de tela por exemplo ao estar auxiliando uma pessoa com deficiencia visual costumam alterar a entonação da voz naquele trecho. "strong" costuma marcar uma forte importância de algo, dar um significado mais forte a algo, mais crítico ou prioritário.

12. "figure"

Esta tag é usada para imagens que possuem relação direta com o conteúdo e podem ser referenciadas. Ela permite agrupar imagem e sua legenda de forma semântica. Ajuda no SEO pois permite que buscadores entendam o contexto visual acompanhado.
Ela agrupa o conteúdo (que pode ser uma "img", "iframe", "table" ou outro elemento) e sua legenda opcional, definida pela tag "figcaption", tratando ambos como uma unidade coerente.

13. "figcaption"
Esta tag acompanha a "figure" e fornece uma descrição textual da imagem. Isso é usado para melhorar acessibilidade, permitindo por exemplo, que usuários com deficiência visual compreendam o conteúdo da imagem (Leitores de tela vão poder ler o conteúdo de "figcaption" e descrever a imagem ou outro conteúdo para a pessoa com deficiencia). Também oferece contexto adicional para mecanismos de busca.

14. "img"

Esta tag tem o objetivo semântico de representar uma imagem diretamente no documento, apontando para um arquivo externo com o atributo src. 
Embora seja uma tag fundamental para incluir imagens, o uso semântico dessa tag foi aprimorado no HTML5 porque ela pode ser combinada com outras tags semânticas, especialmente figure e figcaption, para agrupar a imagem com sua legenda.

15. "time"
Esta tag  tem o significado semântico de representar uma data ou horário de forma estruturada. Ela marca um período específico, como uma data de evento, publicação ou hora, tornando essa data ou horário, leível tanto para humanos quanto para máquinas através do atributo datetime. Semânticamente falando, esta tag fornece um contexto sobre a natureza temporal da informação.

16. "address"

Esta tag é usada para informações de contato, como endereço ou e-mail. Ela fornece significado semântico claro e melhora o SEO local quando usada corretamente. Leitores de tela conseguem identificar rapidamente que se trata de uma forma de contato direto. Nesta tag pode ser incluido qualquer tipo de informação de contato necessária, como endereço físico, URL, email, telefone, mídia social, coordenadas geográficas e etc...

17. "table"

Esta tag representa dados em uma tabela bidimensional, ou seja, com duas dimensões (linhas e colunas). O propósito principal desta tag é descrever a natureza do seu conteúdo como sendo uma tabela de dados, o que é muito importante para questões de acessibilidade, manutençao de código e otimização para motores de busca.

18 "caption"

Esta tag é usada para especificar a legenda ou titulo de uma tabela. Seu principal propósito é Fornecer um resumo ou descrição concisa do conteúdo da tabela, indicando sobre o que são os dados apresentados. Isso é crucial para questões de acessibilidade. Por exemplo, através dessa tag leitores de tela conseguem ajudar usuários com deficiência visual a entender rapidamente o propósito da tabela sem precisar navegar por todas as células.

19. "thead"

Esta tag é usada para definir um conjunto de linhas de cabeçalho de uma tabela. Ou seja, ela agrupa as linhas que servem de cabeçalho para cada coluna da tabela. Seu principal semântico é indicar que aquele trecho do conteúdo é a seção de cabeçalho da tabela.

20. "tbody"

Esta tag é responsável por agrupar as linhas de dados que constituem o corpo principal de uma tabela. Isso é importante para diferenciar na tabela, o que é cabeçalho "thead", corpo principal "tbody" e rodapé "tfooter" de uma tabela HTML. Melhorando assim a manutenção do código, trazendo significado semântico para cada parte do conteúdo e melhorando a acessibilidade da página.

21. "tfoot"

Esta tag define o rodapé de uma tabela. Ela é usada para agrupar as linhas que contêm informações de resumo, como totais, subtotais, notas explicativas ou quaisquer outros dados que se apliquem ao final das colunas da tabela. Isso ajuda a forncer uma estrutura lógica para a tabela, separando de maneira clara o conteúdo entre cabeçalho, corpo e rodapé.

22.  "details"

Esta tag serve para agrupar informações adicionais ou detalhes que o usuário pode expandir ou ocultar se assim desejar. Sua função principal é dar sentido ao conteúdo como um bloco de informação secundária, que não é essencial para a compreensão inicial da página, mas que pode ser relevante para quem quiser se aprofundar. 

23. "sumary"

Serve para definir uma legenda para o conteúdo de um elemento. Esta tag deve ser sempre o primeiro elemento filho da tag "details" pois a semântica desta tag está totalmente ligada a este relacionamento entre as duas. Pois assim, elas criam widget nativo do HTML que pode ser expandido ou recolhido pelo usuário para mostrar ou ocultar determinado conteúdo.

24. "mark"

Usada para destacar trechos importantes dentro de um texto, simulando marcação. Isso ajuda usuários a localizar rapidamente informações-chave. Em acessibilidade, leitores de tela identificam que o texto foi marcado como relevante. A maioria dos navegadores renderizam visualmente essa tag com um fundo amarelo, mas é importante saber seu valor principal é semântico. Ela comunica aos navegadores, leitores de tela e motores de busca que aquele texto tem um propósito específico de destaque relacionado ao conteúdo. Isso melhora a acessibilidade e a interpretação do documento.

25. "abbr"

Esta tag tem o objetivo de  identificar uma abreviação ou sigla.  Ela dá um significado claro ao texto que envolve, indicando, para navegadores, mecanismos de busca e tecnologias assistivas, que aquele conteúdo é uma forma abreviada de uma palavra ou frase. Ela também é muito usada junto com o seu atributo "title" que oferece uma explicação completa da abreeviação, fora do fluxo normal do conteúdo da página (Quando o usuário para o mouse em cima da abreviação).

26. "form"

Esta tag representa uma seção do documento que agrupa controles interativos (como inputs, botões, caixas de seleção, etc.) com o objetivo de coletar dados do usuário e enviá-los para um servidor web para processamento. Essa tag traz vários beneficios ao ser usada no HTML, ela torna o código mais legível e fácil de dar manutenão, vem com muitos atributos úteis imbutidos e os mecanismos de busca conseguem identificar melhor a estrutura e a função da página.

27. "fieldset"

Esta tag é usada para agrupar elementos dentro de um formulário web. Ela fornece estrutura e significado a um conjunto de campos, o que é crucial para a acessibilidade e a compreensão do formulário por parte dos usuários e tecnologias assistivas, como leitores de tela. Embora visualmente os navegadores renderizem essa tag com uma borda ao redor dos elementos, seu propósito principal é a semântica, não apenas a aparência visual. Seu uso semântico também permite funcionalidades práticas, como por exemplo desativar todos os campos dentro de um "fieldset" de uma só vez usando o atributo disabled.

28. "legend"
Esta tag Fornece um título claro e descritivo para um grupo de campos de formulário relacionados (como um grupo de endereços, detalhes de contato ou opções de rádio/checkbox) esta tag tem como elemento pai, a tag "fieldset" por tanto, ela vai fornecer um titulo para os elementos que estão agrupados dentro do "fieldset" isso traz o significado semântico de que todos aqueles campos fazem parte de um mesmo tema/objetivo.

29. "dialog"

Esta tag é usada para representar uma caixa de diálogo (modal ou não modal) ou outro componente interativo, pode ser um alerta dispensável ou subjanela por exemplo. Essa tag permite por exemplo que desenvolvedores criem modais e pop-ups de forma nativa e semântica, em vez de usar elementos "div" genéricos com CSS e JavaScript para imitar esse comportamento.