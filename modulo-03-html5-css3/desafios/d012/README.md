# 📄 Desafio 012 - Módulo 03 - Capítulo 19

## 📌 Enunciado

Desafio proposto no material **"Cordel Moderno"** do curso de HTML e CSS da plataforma **Curso em Vídeo**.

👉 [Material original](https://github.com/gustavoguanabara/html-css/blob/fe6653ecdafa5b7275a5ecb4c36a8ca14f5043e7/desafios/d012/desafio-cordel.pdf)

## 💡 Objetivo

Transformar uma poesia em um site moderno, aplicando efeitos visuais com **imagens de fundo**, **parallax**, **tipografia personalizada**, **responsividade** e organização semântica em HTML5.

## 🌐 Visualização

👉 [Abrir projeto Cordel](https://giulia-mb.github.io/html-semantico/modulo-03-html5-css3/desafios/d012/index.html)

## 🛠️ O que foi praticado

* Estrutura semântica com:
  - `header`
  - `main`
  - `section`
  - `footer`

* Importação de fontes externas pelo Google Fonts:
  - `Passion One`
  - `Sriracha`

* Uso de variáveis CSS com `:root`

* Efeito **parallax** com:
  - `background-image`
  - `background-size: cover`
  - `background-attachment: fixed`

* Seções alternadas entre:
  - fundo branco (`section.normal`)
  - fundo com imagem (`section.imagem`)

* Aplicação de `box-shadow`

* Aplicação de `text-shadow`

* Uso de `vw` para tipografia responsiva

* Links externos com hover estilizado

## 📚 Aprendizados

* O efeito **parallax** cria profundidade visual ao manter a imagem fixa enquanto o conteúdo rola.

* A propriedade:

```css
background-attachment: fixed;
```

é essencial para esse efeito.

* Unidades como:

```css
font-size: 10vw;
```

adaptam o texto ao tamanho da tela.

* Variáveis CSS facilitam manutenção e padronização:

```css
:root {
  --fonte1: Verdana;
}
```

* Tipografia muda completamente a identidade visual de um projeto.

* HTML semântico melhora organização e legibilidade do código.

## 📄 Estrutura do desafio

### `index.html`

Página principal contendo:

* título do projeto  
* autoria da poesia  
* estrofes organizadas em blocos  
* seções com imagens decorativas  
* rodapé com créditos

### `style.css`

Arquivo responsável por:

* layout visual  
* responsividade  
* importação de fontes  
* efeitos de fundo  
* sombras  
* estilização textual

## 🚀 Resultado

Site estilizado inspirado em páginas modernas, combinando literatura e tecnologia com efeitos visuais elegantes e layout responsivo.

---

## 💬 Observação

Este desafio é um dos mais marcantes do curso, pois reúne vários conceitos importantes em um projeto real: tipografia, imagens de fundo, responsividade e organização visual profissional.