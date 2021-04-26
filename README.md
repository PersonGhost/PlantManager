<h1 align="center"><img alt="PlantManager" title="PlantManager" src="https://github.com/PersonGhost/PlantManager/blob/main/src/assets/logo.svg" style="max-width:100%;"></h1>
<p align="center">Projeto desenvolvido no evento Next Level Week da <a href="https://rocketseat">RocketSeat 🚀 💜</a> entre os dias 19-25 de abril de 2021.</p>

<h2><b>💡 Sobre o Projeto</b></h2>
<p>As plantas são vistas no cotidiano de muitas pessoas, sendo em sua casa, trabalho ou até mesmo em restaurantes, sendo assim uma preocupação que se precisa ter é não ter tempo para lembrar de cuidar de sua planta, o PlantManager veio para resolver este problema. Agora com o nosso aplicativo você não precisa saberá quando e como regar suas plantas!</p>

<p>Veja o layout do projeto no <a href="https://www.figma.com/file/jGBbCVh1IyA76Ly05WUpCs/Projeto-PlantManager" target="__blank">figma</a>.</p>

<h2><b>🚧 Tecnologias Utilizadas</b></h2>
<p>Veja abaixo todas tecnologias utilizadas no projeto.</p>

<ul>
  <li><a href="https://reactnative.dev/">React Native</a></li>
  <li><a href="https://www.typescriptlang.org/">TypeScript</a></li>
  <li><a href="https://nodejs.org/en/">Node.JS</a></li>
  <li><a href="https://expo.io/">Expo</a></li>
</ul>

<h2><b>💻 Visualizar Projeto</b></h2>
<p><b>Requerimentos</b></p>
<ul>
  <li><a href="https://nodejs.org/en/">Node.JS</a></li>
  <li><a href="https://expo.io/">Expo</a></li>
  <li><a href="https://yarnpkg.com/">Yarn</a> ou <a href="https://www.npmjs.com/">NPM</a></li>
</ul>
<p><b>Instalando e executando o projeto</b></p>

<p><b>Clone o projeto e logo após acesse a pasta.</b></p>

```
# Clonando o projeto
$ git clone https://github.com/PersonGhost/PlantManager.git

# Entrando na pasta do projeto
$ cd plantmanager
```

<p><b>Instale as dependências nescessárias</b></p>

```
# Instalar as dependências utilizando o npm
$ npm install

# Instalar as dependências utilizando o yarn
$ yarn
```

<p><b>Antes de executar o projeto, vamos também instalar o Json-server</b></p>

```
# Instalar o json-server utilizando o npm
$ npm install -g json-server

# Instalar o json-server utilizando o yarn
$ yarn add -g json-server
```

<p><b>Agora vamos executar o projeto</b></p>

```
# Escolha um método para iniciar o projeto abaixo

# Iniciar o projeto utilizando o npm
$ npm start

# Iniciar o projeto utilizando o yarn
$ yarn start

# Iniciar o projeto utilizando o expo
$ expo start

# Em outra janela cmd vamos executar o json-server
$ json-server ./src/services/server.json --host 000.000.0.000 --port 3333
```

<p><b>Aviso:</b> Você deve alterar o endereço de ip (000.000.0.000) para o do seu computador, para isto você pode encontar seu ip através do cmd</p>

```
# Procure pelo IPv4 address
$ ipconfig
```

<p><b>Também é preciso alterar o link de consulta da api</b></p>

```
# Acesse o diretório /src/services/api.ts
# Você deve alterar o endereço ip do baseURL para o do seu computador, o mesmo que foi utilizado para iniciar o json-server.
```
![image](https://user-images.githubusercontent.com/28011941/116101582-52348680-a684-11eb-91ad-d29977fc7be7.png)
<hr>
📝 Licença
Este projeto está sob a licença do MIT. Para maiores informações acesse o arquivo <a href="https://github.com/ericviinny/PlantManager/blob/main/LICENSE">LICENÇA</a>.

Feito por 💜  Eric Vinicius 👋 <a href="https://www.linkedin.com/in/eric-vinicius-nascimento-6215b8205/">linkedin</a>
