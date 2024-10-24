# PROJETO: "AO REDOR DOS EUA" - BACKEND e FRONTEND

O projeto "Ao redor dos EUA - Autorização e Registro" consistiu na criação de uma página web onde os usuários podem se registrar, fazer login, adicionar, remover e curtir fotos, bem como editar informações e o avatar de seu perfil. O objetivo é utilizarmos a biblioteca React para criação do aplicativo, refatorar o código do [projeto anterior](https://github.com/VitorFGuimaraes/web_project_around) e adicionar uma página de registro e login (com rotas protegidas), bem como  a criação de um servidor com uma API e autenticação de usuário. Como resultados, espera-se um código mais limpo e modular, melhor usabilidade e integração eficiente entre frontend e backend.

## Funcionalidades

- O aplicativo foi estruturado conforme a [documentação do React](https://pt-br.legacy.reactjs.org/docs/getting-started.html).
- Os cartões iniciais da página foram obtidos da Api correspondente;
- Os botões de abertura e fechamento dos popups, submit e like dos cartões utilizaram Estados e Contextos.
- O fechamento dos popups com a tecla ESC ou clicando fora deles foram refatorados;
- Uso de ref para obter acesso direto ao elemento de entrada DOM e seu valor na edição do Avatar;
- As APIs foram estruturadas em Classe.
- Os Hooks Route, Switch, withRouter e useHistory foram utilizados para navegação entre páginas;
- O componente "Protected Route" é responsável por proteger a página principal, que só pode ser acessada por meio de login de usuário registrado;
- O componente "Info tool tip" é responsável por alertar o usuário se seu registro foi bem sucedido ou não;
- A Autorização (auth.js) foi feita com base na URL fornecida pela TripleTen e utilizei o método POST para login e registro e GET para obtenção do token que permite que o usuário permaneça logado.
-Manipulação de banco de dados;
-Instalção e utilização do ESLint;
-Criação de uma API própria;
-Criação de Esquemas e Modelos (GET, POST, DELETE para os cartões; GET e POST para usuários);
-Criação de rotas e controladores;
-Instalação e conexão com o MongoDb;
-Manipulação de Erros.


## Stack utilizada

**Back-end:** JavaScript, NODE, Express.
**Front-end:**  HTML, CSS, flexbox, grid, BEM, JavaScript/JSX, Git/Github, Figma, Webpack, NPM, React.



## Roadmap

- A validação dos formulários está funcionando, porém pode ser melhorada e as mensagens de erro personalizadas;

- O design pode ser melhorado.



## Apêndice

O desgin pode ser acessado no Figma:

- [Parte 1](https://www.figma.com/file/e0lUDoBuWEsFCJ9OQKHypo/Web_Brief_Sprint_5_PT-%7C-Ao-redor-dos-EUA.-%7C-desktop-%2B-mobile?type=design&node-id=0-1&t=KyUBYZhXDZZEHVx0-0)
- [Parte 2](https://www.figma.com/file/UEBC9WrjCqc74O4zfGn8ed/Web_Brief_Sprint_6_PT-%7C-Ao-redor-dos-E.U.A-%7C-desktop-%2B-mobile?type=design&node-id=0-1&t=IdrQyUMIy52wetOb-0)
- [Parte 3](https://www.figma.com/file/2lYBAAE2NJmfoD2q5j710S/Web_Brief_Sprint_6_PT-%7C-Ao-redor-dos-E.U.A?t=f6ckDy1M3pWAFXOf-0)
- [Parte 4](https://www.figma.com/file/zOeMl6rkzkNbETDtm9zohh/Web_Brief_Sprint_10_PT-%7C-JavaScript-Aplic%C3%A1vel?type=design&node-id=0-1&t=4oeZcqTjICWlGugo-0)
- [Parte 5](https://www.figma.com/file/YrtMoHGfwML1yeN5DfWEq3/Web_Brief_Sprint_15_PT-%7C-Registro-e-autoriza%C3%A7%C3%A3o?type=design&node-id=1-78&mode=design&t=hwoqMk9ct8gW4UuY-0)




<div align="center"><img src="https://nexax.in/wp-content/uploads/2020/11/giphy.gif" /></div>
