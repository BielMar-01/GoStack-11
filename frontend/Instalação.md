Escreva 
# yarn init -y
Esse comando serve para instalar o package.json

Para instalar o React escreva
# yan add react react-dom
O react-dom serve com a arvore para ser o react na web se fosse no mobile seria ( react react-native)

Para adicionar o Babel e o Webpack é so rodar o comando
# yarn add @babel/core @babel/preset-env @babel/preset-react webpack webpack-cli

Para tester se esta o que as configurações do babel instale
# yarn add @babel/cli

Instalar o babel-loader
# yarn add babel-loader

Para converter o arquivo no bundle.js rode o comando 
# yarn webpack --mode development

Para que o Webpack fique monitorando constantemente é nessecesario instalar o webpack server
# yarn add webpack-dev-server -D 

Para roda o webpack server rode o comando
# yarn webpack-dev-server --mode development

Para que o .css rode normal vamos instalar o 
# yarn add style-loader css-loader 

Para carregar arquivos dentro da aplicação instalar 
# yarn add file-loader