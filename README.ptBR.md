# Teste Técnico - Formulário React
_Link:_
<br>
👉 https://react-tech-test-3kw6al3xu-paulomonezi.vercel.app

_Languages:_ 
<br>
- 🌎 Also avaliable in English 👉 [Here](https://github.com/paulomonezi/react-tech-test/blob/main/README.md)

## 💻 Sobre 
Esse Projeto é sobre um teste técnico de uma entrevista para o cargo de desenvolvedor react júnior<br>
Recebi esse formulário que outra pessoa desenvolveu, mas ele está incompleto e com alguns bugs, minha tarefa foi corrigir e enviar para o ambiente de produção o mais rápido possível<br>
<br><br>

### 📑 Instruções

* Você tem um formulário de login INCOMPLETO
* Não é permitido adicionar novos elementos HTML
* Não é permitido usar refs<br>
<br><br>

### 🖱️ Tarefas: 

* O botão de login deve disparar a função `login()`, importada no topo deste arquivo, e passar os dados necessários.
* Desabilite o botão de Login caso o e-mail esteja em branco OU a senha for menor que 6 dígitos.
* Desabilite o botão de Login equanto você está executando o login.
* Mostre uma mensagem de erro de `login()` caso o Login falhe. A mensagem deve ser limpa a cada nova tentativa de Login.
* Mostre um alerta caso o login seja efetuado com sucesso (javascript alert). Investigue a função `login()` para entender como ter sucesso na requisição.<br>
<br><br>

### 🚀 O que foi feito 
Além de completar as tasks acima usando `useState`:
* Eu usei renderização condicional na div que já estava preparada para mostrar a mensagem de erro
* Implementei `onKeyDown` para fazer o login também usando a tecla Enter, para melhor UX<br>

<img src="./src/gifs/readme.gif" alt="gif showing the form">
<br><br><br><br>

#### 🙏 Agradecimentos especiais
Eu queria agracer o [Fernandev](https://github.com/nandokferrari), por disponibilizar esse desafio no seu GitHub!<br>
https://github.com/nandokferrari/fernandev-react-challenge-02<br>
Se você quiser tentar resolver o desafio também, você pode clonar o repo acima, ou também clonar esse repo à partir do commit inicial