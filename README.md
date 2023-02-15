# 👆 🖱️ Drag In Drop Raiz



https://user-images.githubusercontent.com/91230559/219097243-5578a36d-bd60-46cc-b09f-46f71e468119.mp4



## 📝 Descrição
Projeto simples utilizando HTML, CSS e JavaScript para implementar a funcionalidade de drag and drop (arrastar e soltar) de elementos.

## 🔗 Acesse o Projeto
Clique [aqui](https://drag-in-drop-raiz.vercel.app/) para acessar o projeto.

## 💻 Uso
Para utilizar o projeto, basta acessar a página HTML em seu navegador e arrastar as cartas para outras colunas.

## 📋 Índice
- [Instalação](#-instalação)
- [Execução](#-execução)
- [Ferramentas](#%EF%B8%8F-ferramentas)
- [Conceitos Aplicados](#-conceitos-aplicados)
- [Explicação Detalhada do Código](#-explicação-detalhada-do-código)

## 🔧 Instalação
Para instalar o projeto em sua máquina, basta clonar o repositório e abrir o arquivo index.html em seu navegador. Você pode fazer isso através do seguinte comando no terminal:
</br>
```
git clone https://github.com/usuario/repo.git
```


## 🚀 Execução
Para executar o projeto, basta abrir o arquivo index.html em seu navegador.

## 🛠️ Ferramentas
- HTML
- CSS
- JavaScript

## 🧩 Conceitos Aplicados
* Drag and drop
* Eventos de mouse
* Seletores CSS
* Responsividade
* Modularização de código

## 🔎 Explicação Detalhada do Código

A página HTML é composta por três colunas (boards), cada uma com um título (Todo, In Progress e Done), contendo uma única caixa (card) arrastável em cada uma. A página utiliza um arquivo CSS para definir a aparência da página e um arquivo JavaScript para implementar a lógica de arrastar e soltar.

Cada caixa (card) contém duas divs, uma com a classe "status" que é usada para definir a cor de fundo da caixa e a outra com a classe "content", que contém o conteúdo da caixa em si. Cada card é definida com o atributo "draggable=true", permitindo que ela seja arrastada pelo usuário.

A página CSS é responsável por definir a aparência visual dos elementos da página, incluindo as cores de fundo, fontes, tamanhos e espaçamentos.

O arquivo JavaScript é responsável por implementar a lógica de arrastar e soltar dos elementos na página. Ele adiciona eventos de arrastar e soltar a cada card e a cada dropzone (área na qual uma caixa pode ser solta). Quando uma caixa começa a ser arrastada, o sistema adiciona a classe "is-dragging" à caixa, destacando-a visualmente e permitindo que o sistema saiba qual caixa está sendo arrastada.

Enquanto a caixa é arrastada, a função "dragover" é executada para permitir que a caixa seja solta em uma dropzone. Quando a caixa é solta em uma dropzone, a função "drop" é executada para mover a caixa para a nova posição.

Essa é uma implementação simples de arrastar e soltar que pode ser adaptada para diferentes tipos de projetos.
