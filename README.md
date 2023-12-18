
Projeto Parallax: It a coisa, Balões e a Cidade Misteriosa 🤡🎈🌃


📂 projeto_parallax
  ├── 📂 assets
  │   ├── 🖼️ palhaco.png
  │   ├── 🖼️ balao.png
  │   └── 🖼️ cidade.png
  ├── 📄 index.html
  └── 📄 styles.css


Detalhes dos Arquivos
📂 assets: Contém os recursos gráficos usados no projeto.
🖼️ palhaco.png: Imagem do palhaço do filme "It a coisa".
🖼️ balao.png: Imagens dos balões vermelhos.
🖼️ cidade.png: Imagem de fundo da cidade misteriosa.
📄 index.html: Arquivo HTML principal, define a estrutura da página e incorpora os recursos com a técnica do parallax.
📄 styles.css: Arquivo CSS com as regras de estilo para o efeito parallax.
Estilos CSS Básicos
Os seguintes estilos são aplicados para configurar o efeito parallax:

Gerais: margin: 0;, padding: 0;, box-sizing: border-box;, transition: 1s;
.wrapper: Elemento contêiner principal. Propriedades como position: absolute;, width: 600px;, height: 400px;, top: 50%;, left: 50%;, transform: translate(-50%, -50%);, perspective: 1000px;
.frame: Quadro do elemento. Propriedades como position: absolute;, border: 5px solid black;, width: 100%;, height: 100%;, overflow: hidden;, background: url(assets/cidade.png);, background-size: 50%;, background-position: 10% 90%;, background-repeat: repeat-x;, box-shadow: 0 0 0 rgba(0, 0, 0, 0.7);, transition: 1s;
.palhaco: Estiliza a imagem do palhaço. Propriedades como position: absolute;, height: 300px;, top: 10px;, right: 150px;
.balao1, .balao2, .balao3: Estilos específicos para cada balão.
Efeitos de Hover
Os seguintes estilos são aplicados quando o cursor do mouse passa sobre os elementos:

.wrapper:hover .frame, .wrapper:hover .balao1, .wrapper:hover .balao2, .wrapper:hover .balao3: Alteram a posição de fundo, rotação e escala dos elementos ao passar o mouse.
O projeto proporciona uma experiência única com animações que mudam a posição, rotação e escala dos elementos ao interagir com o cursor do mouse, aprimorando o efeito parallax.

Créditos ao canal @Frankslaboratory.

Divirta-se explorando e personalizando este projeto!madas.
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





