````markdown
# Contagem Regressiva ⏳

Um projeto simples de **contagem regressiva** criado com HTML, CSS e JavaScript. Este app exibe o tempo restante (dias, horas, minutos e segundos) até uma data alvo configurada no código.

## 📌 Sobre

Este repositório contém uma página web que mostra uma contagem regressiva em tempo real. A implementação inclui:

- Estrutura HTML (`index.html`)
- Estilos CSS para layout e visual (`style.css`)
- Lógica JavaScript para o cálculo e atualização do tempo (`script.js`)
- Imagens/ícones utilizados no projeto (`img/`)

> O projeto foi desenvolvido como um exercício/interativo de front-end.

## 🛠️ Tecnologias

Este projeto foi construído com:

- **HTML5**
- **CSS3**
- **JavaScript **

## 🚀 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/EmillySRamalho/Contagem-Regressiva.git
````

2. Entre na pasta:

   ```bash
   cd Contagem-Regressiva
   ```

3. Abra o arquivo `index.html` no seu navegador favorito.

## ✍️ Configurando a data alvo

No arquivo `script.js` você pode definir a data para a qual a contagem deve regressar. Por exemplo:

```js
const targetDate = new Date('Dec 31, 2026 23:59:59').getTime();
```

Ajuste conforme sua necessidade para eventos, aniversários, finais de ano etc.

## 🎯 Funcionalidades

* ✔ Exibe dias, horas, minutos e segundos restantes
* ✔ Atualiza automaticamente a cada segundo
* ✔ Fácil de personalizar e reutilizar
