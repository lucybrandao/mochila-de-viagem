# Mochila de Viagem :school_satchel:
Projeto de estudos sobre como armazenar dados no navegador por meio da propriedade `localStorage` ([ver mais](https://developer.mozilla.org/pt-BR/docs/Web/API/Window/localStorage)).

![image](https://user-images.githubusercontent.com/39086256/190651111-d0ffc19c-4eb2-45d8-9338-62533716c698.png)

A propriedade `localStorage` permite acessar um objeto [Storage](https://developer.mozilla.org/pt-BR/docs/Web/API/Storage) local. A `localStorage` é similar ao [sessionStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/sessionStorage). A única diferença é que enquanto os dados armazenados no `localStorage` não expiram, os dados no `sessionStorage` tem os seus dados limpos ao expirar a sessão da página — ou seja, quando a página (aba ou janela) é fechada.

## Sintaxe
```javascript
meuStorage = localStorage;
```
## Exemplo
O seguinte trecho acessa o objeto [Storage](https://developer.mozilla.org/pt-BR/docs/Web/API/Storage) local do domínio atual e adiciona um item usando o [Storage.setItem()](https://developer.mozilla.org/pt-BR/docs/Web/API/Storage/setItem).
```javascript
localStorage.setItem('meuCachorro', 'Toy');
```

## Setup
Apenas faça dawnload do projeto e abra o arquivo `index.html` em seu browser.

Sugestão: usar o liveServer do VSC.

## Font
- [Alura / JavaScript na Web: armazenando dados no navegador](https://cursos.alura.com.br/course/javascript-web-armazenando-dados-navegador);
- [Mozilla / localStorage](https://developer.mozilla.org/pt-BR/docs/Web/API/Window/localStorage).
