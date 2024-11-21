# Projeto de perfumaria do frontend mentor

<div><img aling="center" src="img/projeto.jpg" alt="header"></div>

## VISÃO GERAL

- Uma interface de aplicativo de compra online, sobre venda de perfume. Com um título bem chamativo e uma breve explicação do produto. Com um botão que ser tocado muda levemente de cor.

## DESAFIOS

- Neste projeto tive dificulade em organizar os elementos e principalmente na sua responsividade. Demorei muito para concluir fiquei bem confuso na hora codar. Revisitei vários materiais e anotações, não sei o que conteceu porém aprendi muito com as etapas. Eu fiz um novo projeto depois de quase tudo pronto. Estou feliz por concluir mais um desafio.

- Uma das coisa que estava me atormentando era a largura do card e olha que já tinha feito outros, mas parece que algo estava errado -"mas estava mesmo". Quando a tela aumentava os elementos ficam em desordem. Foi ai que me lembrei que na documentação do W3C tem uma explicação muito boa para largura do card.

- Outra cois que não estava saindo bem eram as imagens, não conseguia de jeito algum fazer com que se adaptasem. Consegui resolver dessa forma também consultando o W3C.

´´´´´´html
    <div class="capa">
        <img class="mobile" src="img/image-product-mobile.jpg" alt="imagem do perfume chanel">
        <img class="desktop" src="img/image-product-desktop.jpg" alt="imagem do perfume chanel">
    </div><!--capa-->
´´´´´´

````css
div.capa{
    overflow: hidden;
    width: 100%;
    height:500px;
}
.capa > img.mobile{
    display: block;
    max-width: 100%;
    height: auto;
    object-fit: cover;
    object-position: center;
}
.capa > .desktop{
    display: none;
}
````

### Para telas grandes

````css
div.capa{
        overflow: hidden;
        width: 50%;
    }
    .capa > img.mobile{
        display: none;
    }
    .capa > img.desktop{
        display: block;
        max-width: 100%;
        height: auto;
        object-fit: cover;
        object-position: center;
    }
````

## Cores

- #3c8067 VERDE
- #fafbff BRANCO
- #f2ebe3 BEJE CLARO
- #6C7289 CINZA
- #1c232b PRETO

## Tipografia

- Montserrat 500
- Montserrat 700
- Fraunces 700

## Links
- [URL-da-solução]()
- [URL-do-site-ativo]()

## Construído com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- Fluxo de trabalho que prioriza os dispositivos móveis

## Aprendizagem

De como posicionar melhor as imagens quando elas estão dentro da estrutura do html. Na primeira vez que tentei utilizei o css para melhor adaptá-las, porém não obtive sucesso, mas com esforço e persistencia conclui o desafio.

## Autor

- [Instagram](https://www.instagram.com/denner_souza.s/)