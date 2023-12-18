
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


Divirta-se experimentando diferentes ajustes e efeitos para tornar a experiência ainda mais diferente! 👻💀💡





