<h1 align="center">
  <img alt="Happy" src="./web/src/images/map-marker.svg">
  <br>
  <strong> Happy </strong>
</h1>

<h3 align="center"> NLW #3 | Rocketseat | Trilha OmniStack </h3>

<br>

# 📑 SUMÁRIO
* [Sobre](#Sobre)
* [Apresentação](#Apresentacao)
* [Instalação](#Instalacao)
  * [Pré Requisitos](#Pre-requisitos)
* [Rodando a Aplicação](#Rodando-a-Aplicacao)
* [Tecnologias Utilizadas](#Tecnologias-utilizadas)
* [Licença](#Licenca)

<br>

<a id="Sobre"></a>
# ✏️ SOBRE

<br/>

<p>  A semana do projeto iniciou com o Dia das Crianças, e por isso, o tema é voltado a esse dia.

O sistema é composto por aplicação web e mobile, onde as pessoas podem encontrar orfanatos na sua cidade, com o intuito de visitá-los, presentear as crianças, etc, desde que a visita seja previamente combinada.</p>

<br>

<a id="Apresentacao"></a>
# 💻📱 APRESENTAÇÃO
<h2 align="center">
  <img alt="Preview" src="./preview.png">
</h2>

<br>

> Todas as telas do projeto - _web_ e _mobile_ - podem ser vistas no site **[Figma](https://www.figma.com/files/project/16541979/Happy-%5BRocketseat%5D)**.

<br/>


<a id="Instalacao"></a>
# 📥 INSTALAÇÃO

<a id="Pre-requisitos"></a>
## 📋 ✔️ PRÉ REQUISITOS

➡️ [Node.js](https://nodejs.org/en/) 

➡️ Gerenciador de pacotes [NPM](https://nodejs.org/en/download/package-manager/) ou [Yarn](https://yarnpkg.com/getting-started/install#global-install) 

➡️ [Expo](https://expo.io/learn) e **recomendável** aplicativo para celular [Android](https://play.google.com/store/apps/details?id=host.exp.exponent) ou [iOS](https://apps.apple.com/br/app/expo-client/id982107779)

➡️ [Git](https://git-scm.com) é _opcional_ de se ter instalado na máquina. O projeto também pode ser baixado diretamente como `.zip`
<br><br>

<a id="Rodando-a-aplicacao"></a>
# ⚙️ RODANDO A APLICAÇÃO

```bash
# CLONE O REPOSITÓRIO
  git clone https://github.com/J-LineB/Happy

# ACESSE A PASTA DO PROJETO NO TERMINAL/CMD
  cd happy

# INSTALE AS DEPENDÊNCIAS (DENTRO DE CADA DIRETÓRIO)
  npm install
# OU
  npm i

# CRIE O BANCO DE DADOS
  cd backend
  npm run typeorm migration:run

# RODE O SERVIDOR
  npm run dev

# INICIE A APLICAÇÃO WEB
  cd web
  npm start

# INICIE A APLICAÇÃO MOBILE
  cd mobile
  npm start
# OU
  expo start
```

<br>

<a id="Tecnologias-utilizadas"></a>
# ⚒️ 🌟 TECNOLOGIAS UTILIZADAS

- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js](https://nodejs.org/en/) + [NPM](https://nodejs.org/en/download/package-manager/)
- [Git](https://git-scm.com)

### WEB
- [ReactJS](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [CSS](https://www.w3.org/Style/CSS/)
- [Axios](https://www.npmjs.com/package/axios)

### BACK-END
- [Express.js](https://expressjs.com/pt-br/)
  - [express-async-errors](https://www.npmjs.com/package/express-async-errors)
- [JSON](https://www.json.org/json-en.html)
- [API REST](https://restfulapi.net/)
- [Insomnia](https://insomnia.rest/)
- [TypeORM](https://typeorm.io/)
  - [SQLite Connection](https://typeorm.io/#/connection-options/sqlite-connection-options)
- [Beekeeper Studio](https://www.beekeeperstudio.io/)
- [Multer](https://www.npmjs.com/package/multer)
- [Yup](https://www.npmjs.com/package/yup)
- [Cors](https://www.npmjs.com/package/cors)

### MOBILE
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/learn)
  - [MapView](https://docs.expo.io/versions/latest/sdk/map-view/)
  - [Google Fonts](https://github.com/expo/google-fonts)
  - [ImagePicker](https://docs.expo.io/versions/latest/sdk/imagepicker/)
- [React Navigation](https://reactnavigation.org/docs/getting-started)
- [Axios](https://www.npmjs.com/package/axios)

<br>

<a id="Licenca"></a>
# 🔓 LICENÇA
## 👉 [MIT](./LICENSE.md)
_Uma licença permissiva curta e simples com condições que exigem apenas a preservação de direitos autorais e avisos de licença. Obras licenciadas, modificações e obras maiores podem ser distribuídas em termos diferentes e sem código-fonte._

**Permissões** <br>
 ✔️ Uso comercial | ✔️ Modificação | ✔️ Distribuição | ✔️ Uso privado

**Limitações** <br>
 ❌ Responsabilidade | ❌ Garantia

**Condições** <br>
 ❗ Licença e aviso de direitos autorais