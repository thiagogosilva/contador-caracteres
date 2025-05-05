# Contador de Caracteres e Palavras

Este é um projeto simples para contar caracteres e palavras digitadas em um campo de texto, com algumas funcionalidades extras para melhorar a experiência do usuário.

## 🚀 Funcionalidades

* **Contagem de caracteres**: Exibe o total de caracteres digitados.
* **Contagem de caracteres sem espaços**: Conta apenas os caracteres, desconsiderando os espaços.
* **Contador de palavras**: Exibe a quantidade de palavras digitadas.
* **Alerta visual**: Muda a cor do contador quando o limite de 200 caracteres é ultrapassado.
* **Botão Limpar**: Reseta o campo de texto e os contadores.
* **Contador regressivo**: Mostra a quantidade de caracteres restantes até o limite de 200.
* **Bloqueio de digitação**: Impede que o usuário digite mais caracteres ao atingir o limite de 200, mas sem bloquear o backspace.

## 🧑‍💻 Tecnologias usadas

* HTML
* CSS
* JavaScript

## 📜 Como usar

1. Abra em seu navegador.
2. Digite no campo de texto e observe o contador de caracteres e palavras atualizarem em tempo real.
3. Ao atingir 200 caracteres a digitação será bloqueada.
4. Clique no botão "Limpar" para resetar os contadores e o campo de texto.

## 🐞 Problemas encontrados

Durante o desenvolvimento, um bug foi identificado onde os contadores de "palavras" e "caracteres sem espaço" não estavam sendo atualizados corretamente. Isso foi causado por um erro no nome do ID dos elementos no HTML, que foi corrigido para garantir que o `getElementById` fosse chamado corretamente.

## 📚 Aprendizados

* Manipulação dinâmica de estilos com `classList.add()` e `classList.remove()`.
* Criação de feedback visual progressivo (alterando cores conforme o limite de caracteres é atingido).
* Implementação de validação em tempo real utilizando JavaScript puro.
* Manipulação de propriedades de texto como `.slice()`, `.replace()`, `.split()`, e `.length`.

## 🔧 Como contribuir

Sinta-se à vontade para sugerir melhorias ou corrigir eventuais erros. Fique à vontade para criar um pull request com suas contribuições!

## 🧑‍💻 Desenvolvido por

**Thiago Silva**  
- [GitHub](https://github.com/thiagogosilva)
- [LinkedIn](https://www.linkedin.com/in/thiagogosilva)

## 🔗 Acesse o projeto

Você pode visualizar o projeto em funcionamento aqui:  
👉 [Contador de Caracteres - GitHub Pages](https://thiagogosilva.github.io/contador-caracteres/)

**Link para visualizar meu Mini Portfólio:**  
🔗 [Mini Portfólio 💻](https://thiagogosilva.github.io/desafio-90dias-dev/)