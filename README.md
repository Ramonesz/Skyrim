# Relatório de Aprendizagem — Skyrim

## A ideia do projeto

Escolhi fazer o site sobre *The Elder Scrolls V: Skyrim* porque gosto muito do jogo e jogo há vários anos. Skyrim fez parte da minha infância e continua sendo um jogo que uso até hoje. Também me interessa a construção do mundo: a história, os povos, as regiões e a lore deixam o universo do jogo muito rico para pesquisar.

Como o tema do trabalho era livre, achei que esse assunto seria uma boa forma de estudar desenvolvimento web enquanto organizava informações sobre algo de que realmente gosto.

## Como o site foi desenvolvido

Comecei pelo `index.html`, que funciona como a página inicial. Nele montei a apresentação do tema, a navegação entre as páginas e o rodapé. Depois criei as outras páginas para separar os assuntos: armas, magia, monstros, DLCs, história, raças e mundo.

No planejamento apareceram mais ideias de abas, mas percebi que o site ficaria grande demais. Então reduzi o escopo e mantive as seções principais, fazendo alguns ajustes no conteúdo e na organização durante o desenvolvimento.

O arquivo `css/style.css` reúne as regras visuais compartilhadas. Usei classes para organizar os elementos, grades para os cartões e regras responsivas para adaptar as páginas a telas menores. Na página de Magia, o carrossel troca as imagens com controles HTML e CSS, sem JavaScript.

As imagens foram separadas em subpastas de `imagens/` por assunto, como armas, monstros, raças, DLCs, magia e mundo. Isso ajudou a localizar os arquivos e manter os caminhos usados no HTML organizados.

## Ferramentas e tecnologias

- **HTML:** usei para criar a estrutura, os textos, os links, as imagens e as seções de cada página.
- **CSS:** usei para cuidar das cores, tamanhos, posicionamento, cartões, navegação e adaptação para celular.
- **Visual Studio Code:** usei para editar e organizar os arquivos do projeto.
- **Navegador:** usei para abrir as páginas, conferir as imagens e testar o comportamento em diferentes larguras de tela.
- **Git e GitHub:** usei para versionar e guardar o código em um repositório público.
- **Google Imagens:** usei como ferramenta de busca para encontrar imagens relacionadas ao jogo. O Google Imagens não é necessariamente o autor dos arquivos; por isso, as fontes originais e as condições de uso precisam ser conferidas e creditadas quando identificadas.
- **ChatGPT:** usei como apoio para tirar dúvidas, pensar em soluções e revisar partes do trabalho. As sugestões foram conferidas e adaptadas ao projeto.

## O que aprendi

Durante o trabalho pratiquei a criação de várias páginas HTML conectadas por uma navegação comum, o uso de caminhos relativos para encontrar imagens e folhas de estilo e a organização dos arquivos por assunto. Também pratiquei seletores e classes CSS, layouts com grade e flexbox e regras para telas menores.

Também aprendi a pensar melhor em como usar imagens no site. Como coloquei várias, precisei organizá-las por assunto e escolher onde cada uma ajudava a apresentar o conteúdo. Os cartões ajudaram a agrupar textos e imagens por categoria, deixando as páginas mais fáceis de percorrer. Aprendi ainda a manter a navegação no topo das páginas para facilitar a troca entre as seções.

Outra coisa que aprendi foi que uma página pode ter uma interação simples sem JavaScript. No carrossel de Magia, os controles de rádio e os seletores CSS mostram uma imagem por vez. Também revisei como testar as páginas no navegador e procurar problemas como imagens que não carregam ou conteúdo que ultrapassa a largura da tela.

## GitHub Pages e uma experiência anterior

Eu já conhecia o GitHub Pages porque usei essa ferramenta para publicar um site do meu trabalho da **SEPE 2026**. Essa experiência anterior me ajudou a entender melhor como disponibilizar um site estático para outras pessoas acessarem.

O repositório do projeto está público no [GitHub](https://github.com/Ramonesz/Skyrim).

## Sobre o bônus de geradores estáticos

O enunciado cita ferramentas como Jekyll e Hugo. Um gerador de site estático combina conteúdo, modelos e arquivos de configuração e, durante uma etapa de geração, produz os arquivos finais do site, como HTML e CSS, que podem ser publicados no GitHub Pages. O Jekyll tem integração direta com o GitHub Pages; o Hugo também pode ser usado, normalmente com uma etapa de compilação configurada.

Esta versão foi feita diretamente em HTML e CSS, sem Jekyll ou Hugo. Por isso, esta explicação não afirma que o gerador foi usado nem que o bônus foi conquistado. Para cumprir esse critério, seria necessário integrar um gerador, manter o layout próprio e explicar no relatório por que e como ele foi usado.

