
🟤Exercício sobre Flexbox CSS - ILanche
Este repositório contém uma página web simples que apresenta uma lista de itens de comida e bebida para um restaurante fictício chamado "ILanche". O objetivo deste exercício é demonstrar o uso do Flexbox no CSS para criar um layout responsivo e visualmente atraente para os cartões de produto. Realizo no DevMedia, para por em prática o aprendizado. 

🟤Como começar
Para visualizar o projeto, basta abrir o arquivo index.html em um navegador da web. O layout se adaptará a diferentes tamanhos de tela e dispositivos, graças às propriedades Flexbox usadas no arquivo styles.css.


🟤Estrutura do Projeto
index.html: Este arquivo HTML contém a estrutura da página web, exibindo os cartões de produto usando o Flexbox.

styles.css: O arquivo CSS contém as regras de estilo responsáveis pelo layout e apresentação dos cartões de produto.

imagens/: Esta pasta contém as imagens usadas no projeto.

🟤Layout com Flexbox
O layout principal deste projeto é alcançado usando o Flexbox, um poderoso modelo de layout CSS que permite alinhar e distribuir facilmente elementos dentro de um contêiner. Aqui está uma visão geral das propriedades Flexbox usadas neste projeto:

.main: Representa o contêiner principal dos cartões de produto. Ele tem uma cor de fundo e preenchimento para criar espaço entre o conteúdo e as bordas da página.

.topo h1: Estiliza o cabeçalho "Happy Lanches" no topo da página com uma cor chocolate e uma font-family específica.

.container: O contêiner para os cartões de produto individuais. Ele usa Flexbox para organizar os cartões em uma linha, com a propriedade justify-content definida como space-around para adicionar espaçamento igual entre os cartões. A propriedade flex-wrap garante que os cartões sejam ajustados para a próxima linha quando o tamanho da tela é reduzido.

.card-produto: Representa um cartão de produto individual. Ele usa Flexbox com a propriedade flex para permitir que os cartões cresçam e encolham conforme necessário, mantendo uma largura mínima fixa de 300px. As propriedades border-radius e box-shadow são usadas para fins estéticos.

.container-imagem: Um contêiner para a imagem do produto. Ele define uma altura fixa para o contêiner de imagem.

.container-imagem img: Estiliza a imagem do produto para preencher seu contêiner, mantendo sua proporção.

.container-info: Um contêiner para as informações do produto, como nome e descrição. Ele usa Flexbox para organizar o conteúdo em uma coluna e justify-content: space-around para distribuir uniformemente o conteúdo verticalmente.

.container-info h3: Estiliza o nome do produto com um tamanho de fonte de 18px.

.container-preco: Um contêiner para o preço do produto e o ícone do carrinho. Ele usa Flexbox com justify-content: space-between para posicionar os elementos nas duas extremidades do contêiner.

.container-icone: Um contêiner para o ícone do carrinho. Ele fornece algum preenchimento e estilização de borda para criar um efeito visual.


🟤 Agradecimentos
Agradecimentos especiais ao instrutor e a todos os envolvidos no curso do DevMedia sobre Flexbox CSS por fornecerem este exercício. As imagens usadas neste projeto são apenas para fins de demonstração e pertencem aos seus respectivos proprietários.
