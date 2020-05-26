![Alt Text](https://github.com/jorgeolvr/BeTheHero/raw/master/frontend/src/assets/logo.svg)

Códigos desenvolvidos durante a **Semana Oministack 11.0** da plataforma [Rocketseat](https://rocketseat.com.br/).
O objetivo da aplicação é cadastrar incidentes registrados por ONG's utilizando Node, React e SQLite.

## Como testar na própria máquina?

Para baixar, basta clonar este repositório na sua máquina:

```sh
git clone https://github.com/jorgeolvr/BeTheHero.git
```
## Bibliotecas
As seguintes bibliotecas foram utilizadas na implementação do projeto:

### Backend
- [Express](https://www.npmjs.com/package/express) - Framework projetado para criar aplicativos da Web e APIs
- [Cors Package](https://www.npmjs.com/package/cors) - Permite que os recursos sejam acessados por uma aplicação de domínio diferente
- [Nodemon](https://nodemon.io/) - Utilitário que irá monitorar as alterações nos arquivos e reiniciar automaticamente o servidor

### Frontend
- [React.js](https://pt-br.reactjs.org/) - Framework JavaScript de código aberto com foco em criar interfaces de usuário em páginas web
- [Axios](https://www.npmjs.com/package/axios) - Cliente HTTP para realizar requisições Ajax

### Mobile
- [React Native](https://facebook.github.io/react-native/) - Framework JavaScript para desenvolver aplicativos de forma nativa
- [Axios](https://www.npmjs.com/package/axios) - Cliente HTTP para realizar requisições Ajax

## Endpoints da API REST
- **<code>GET</code> ongs**
- **<code>GET</code> incidents**
- **<code>GET</code> profile**
- **<code>POST</code> ongs**
- **<code>POST</code> incidents**
- **<code>POST</code> sessions**
- **<code>DELETE</code> incidents/:id**

## Inicialização da aplicação
O *npm* foi utilizado como gerenciador de pacotes nesse projeto. Para isso é necessário instalar todas as dependências antes prosseguir:

### Dentro das pastas *frontend* e *backend*
Se for necessário rodar em ambiente de desenvolvimento, execute o comando abaixo para utilizar o *nodemon*:
```
npm install && npm start
```

### Dentro da pasta *mobile*
Para usar em um simulador do **iOS** execute:
```
npm install && npx react-native run-ios
```
Se desejar executar em simulador **android**:
```
npm install && npx react-native run-android 
```
