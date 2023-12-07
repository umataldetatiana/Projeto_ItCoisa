
## Projeto Parallax: It a coisa, Balões e a Cidade Misteriosa 🤡🎈🌃
Neste projeto, criamos uma página web com efeitos de parallax, onde um palhaço assustador, balões flutuantes e uma cidade misteriosa ganham vida. Créditos ao canal do @Frankslaboratory

## Descrição do Projeto
Neste projeto vamos usar a técnica do parallax para criar uma experiência visual impactante apenas com css. A página que vamos desenvolver apresenta uma cena com elementos como o palhaço do Filme It a coisa, balões flutuantes vermelhos e uma cidade sombria ao fundo.

Estrutura do Projeto
Aqui está a estrutura de arquivos do projeto para você se orientar:

📂 projeto_parallax
├── 📂 assets
│   ├── 🖼️ palhaco.png
│   ├── 🖼️ balao.png
│   └── 🖼️ cidade.png
├── 📄 index.html
└── 📄 styles.css

Vamos dar uma olhada em cada arquivo:

📂 assets - Este diretório contém os recursos utilizados no projeto:
🖼️ palhaco.png - Uma imagem assustadora do palhaço It, que será exibida no parallax. Prepare-se para um sorriso sinistro!
🖼️ balao.png - Imagens dos balões vermelhos que flutuam nessa cena. Os balões são elementos chave para criar o suspense!
🖼️ cidade.png - Uma imagem de fundo que representa uma cidade misteriosa.

📄 index.html - Este é o arquivo HTML principal do projeto, responsável por definir a estrutura da página e incluir os recursos necessários com a técnica do parallax.
📄 styles.css - Este arquivo contém as regras de estilo CSS para o parallax. Nele, vamos definir as posições e animações dos elementos.

Vamos começar?

margin: 0; define margem zero para todos os elementos.
padding: 0; define preenchimento zero para todos os elementos.
box-sizing: border-box; define a caixa de modelo como "border-box" para todos os elementos.
transition: 1s; aplica uma transição de 1 segundo a todas as propriedades animadas.
O seletor .wrapper estiliza o contêiner principal do elemento, com as seguintes propriedades:

position: absolute; posiciona o elemento de forma absoluta.
width: 600px; define a largura do elemento como 600 pixels.
height: 400px; define a altura do elemento como 400 pixels.
top: 50%; posiciona o elemento no centro vertical da página.
left: 50%; posiciona o elemento no centro horizontal da página.
transform: translate(-50%, -50%); move o elemento para o centro absoluto da página.
perspective: 1000px; define a perspectiva tridimensional do elemento.
O seletor .frame estiliza o quadro do elemento, com as seguintes propriedades:

position: absolute; posiciona o elemento de forma absoluta.
border: 5px solid black; define uma borda sólida preta com 5 pixels de espessura.
width: 100%; define a largura do elemento como 100% do contêiner pai.
height: 100%; define a altura do elemento como 100% do contêiner pai.
overflow: hidden; oculta o conteúdo que ultrapassa as dimensões do elemento.
background: url(assets/cidade.png); define uma imagem de fundo para o elemento.
background-size: 50%; define o tamanho da imagem de fundo como 50% do elemento.
background-position: 10% 90%; define a posição inicial da imagem de fundo.
background-repeat: repeat-x; define a repetição horizontal da imagem de fundo.
box-shadow: 0 0 0 rgba(0, 0, 0, 0.7); aplica uma sombra ao redor do elemento.
transition: 1s; aplica uma transição de 1 segundo a todas as propriedades animadas.
O seletor .palhaco estiliza a imagem do palhaço, com as seguintes propriedades:

position: absolute; posiciona o elemento de forma absoluta.
height: 300px; define a altura do elemento como 300 pixels.
top: 10px; posiciona o elemento a 10 pixels do topo.
right: 150px; posiciona o elemento a 150 pixels da direita.
Os seletores .balao1, .balao2 e .balao3 estilizam as imagens dos balões, com propriedades específicas para cada um.

.balao1: define a altura, a posição e a transição para o balão 1.
.balao2: define a altura e a posição para o balão 2.
.balao3: define a altura e a posição para o balão 3.
Os seletores .wrapper:hover .frame, .wrapper:hover .balao1, .wrapper:hover .balao2 e .wrapper:hover .balao3 aplicam estilos aos elementos quando o cursor do mouse está sobre o contêiner principal (.wrapper):

.wrapper:hover .frame: altera a posição de fundo, a rotação e a sombra do quadro.
.wrapper:hover .balao1: altera a posição, a rotação e a escala do balão 1.
.wrapper:hover .balao2: altera a posição, a rotação e a escala do balão 2.
.wrapper:hover .balao3: altera a posição, a rotação e a escala do balão 3.

O código cria um efeito de parallax e quando o cursor do mouse passa sobre o elemento, ocorrem animações que alteram a posição, rotação e escala dos elementos.

Divirta-se experimentando diferentes ajustes e efeitos para tornar a experiência ainda mais diferente! 👻💀💡





