# ✔️ CheckList React Redux

*Antes de começar*
- [ ] pensar como será o formato do seu estado global
- [ ] pensar quais actions serão necessárias na sua aplicação

*Instalando dependências e criando app*
Crie uma pasta, abra ela no terminal e rode os seguintes comandos em sequência:

- [ ] Criar aplicativo
```javascript 
    npx create-react-app my-app-redux
```
- [ ] Instalar as depenências dev do Redux para React
```javascript 
     npm install --save redux react-redux
```
- [ ] Instalar as demais denpendências, caso tenha.
```javascript 
    npm install
```

*Criar dentro do diretório src:*
- [ ] diretório actions;
- [ ] diretório reducers;
- [ ] diretório store.

*Criar dentro do diretório actions:*
- [ ] arquivo index.js.

*Criar dentro do diretório reducers:*
- [ ] arquivo index.js.

*Criar dentro do diretório store:*
- [ ] arquivo index.js.

*No arquivo App.js:*
- [ ] definir o Provider, `<Provider store={ store }>`, para fornecer os estados à todos os componentes encapsulados em `<App />`.

*No arquivo store/index.js:*
- [ ] importar o rootReducer e criar a store
- [ ] configurar o [Redux DevTools](https://github.com/reduxjs/redux-devtools)

*Na pasta reducers:*
- [ ] criar os reducers necessários
- [ ] configurar os exports do arquivo index.js

*Na pasta actions:*
- [ ] criar os actionTypes
- [ ] criar as actions necessárias

*Nos componentes:*
- [ ] criar a função mapStateToProps
- [ ] criar a função mapDispatchToProps
- [ ] fazer o connect


by Maitê Marques - Adaptado
