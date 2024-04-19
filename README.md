
# Exercício sobre Flexbox CSS - ILanche 📚
Este repositório contém uma página web simples que apresenta uma lista de itens de comida e bebida para um restaurante fictício chamado "ILanche". O objetivo deste exercício é demonstrar o uso do Flexbox no CSS para criar um layout responsivo e visualmente atraente para os cartões de produto. Realizo no DevMedia, para por em prática o aprendizado. 

## Como começar
Para visualizar o projeto, basta abrir o arquivo index.html em um navegador da web.<br>
O layout se adaptará a diferentes tamanhos de tela e dispositivos, graças às propriedades Flexbox usadas no arquivo styles.css.


## Estrutura do Projeto
<ul>
<li>index.html:</li>Este arquivo HTML contém a estrutura da página web, exibindo os cartões de produto usando o Flexbox.

<li>styles.css:</li> O arquivo CSS contém as regras de estilo responsáveis pelo layout e apresentação dos cartões de produto.

<li>imagens/:</li> Esta pasta contém as imagens usadas no projeto.
</ul><br>

##  Layout com Flexbox
O layout principal deste projeto é alcançado usando o Flexbox, um poderoso modelo de layout CSS que permite alinhar e distribuir facilmente elementos dentro de um contêiner. Aqui está uma visão geral das propriedades Flexbox usadas neste projeto:
<ul>
<li>main:</li> Representa o contêiner principal dos cartões de produto. Ele tem uma cor de fundo e preenchimento para criar espaço entre o conteúdo e as bordas da página.

<li>topo h1:</li> Estiliza o cabeçalho "Happy Lanches" no topo da página com uma cor chocolate e uma font-family específica.

<li>container:</li> O contêiner para os cartões de produto individuais. Ele usa Flexbox para organizar os cartões em uma linha, com a propriedade justify-content definida como space-around para adicionar espaçamento igual entre os cartões. A propriedade flex-wrap garante que os cartões sejam ajustados para a próxima linha quando o tamanho da tela é reduzido.

<li>card-produto:</li> Representa um cartão de produto individual. Ele usa Flexbox com a propriedade flex para permitir que os cartões cresçam e encolham conforme necessário, mantendo uma largura mínima fixa de 300px. As propriedades border-radius e box-shadow são usadas para fins estéticos.

<li>container-imagem:</li>Um contêiner para a imagem do produto. Ele define uma altura fixa para o contêiner de imagem.

<li>container-imagem img:</li> Estiliza a imagem do produto para preencher seu contêiner, mantendo sua proporção.

<li>container-info:</li> Um contêiner para as informações do produto, como nome e descrição. Ele usa Flexbox para organizar o conteúdo em uma coluna e justify-content: space-around para distribuir uniformemente o conteúdo verticalmente.

<li>container-info h3:</li> Estiliza o nome do produto com um tamanho de fonte de 18px.

<li>container-preco:</li> Um contêiner para o preço do produto e o ícone do carrinho. Ele usa Flexbox com justify-content: space-between para posicionar os elementos nas duas extremidades do contêiner.

<li>container-icone:</li> Um contêiner para o ícone do carrinho. Ele fornece algum preenchimento e estilização de borda para criar um efeito visual.
</ul>

##  Agradecimentos
Agradecimentos especiais ao instrutor e a todos os envolvidos no curso do DevMedia sobre Flexbox CSS por fornecerem este exercício. As imagens usadas neste projeto são apenas para fins de demonstração e pertencem aos seus respectivos proprietários.

![Mega64SwededGIF](https://github.com/ErikaMendes89/exercicio-flexbox/assets/95776659/c0d0f2a3-1bda-4ba2-b46e-3f2b01992f9e)


