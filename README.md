# Be The Hero - Semana Omnistack 11
Esse repositório contém tudo o que foi desenvolvido durante a semana omnistack 11, o objetivo dessa aplicação é criar um sistema para ajudar Ongs a encontrar voluntários para resolver algumas demandas e serem os seus heróis. O App mobile foi desenvolvido de maneira diferente do que foi abordado na semana omnistack, aqui decidi por não utilizar o Expo e sim via cli por meio do comando: 
```bash
npx react-native init <project-name>
```
O App mobile foi otimizado para Android, com splash screen e icones para cada densidade de tela.


## Ferramentas utilizadas:
- Nodejs
- Express
- Axios
- Sqlite3
- Knex
- ReactJs
- React Native
- Jest

## Como utilizar:
- Para rodar a API entre na pasta backend e execute o seguinte comando:
```bash
npm start
```

- Para rodar aplicação Web entre na pasta frontend e execute o seguinte comando:
```bash
npm start
```

- Para rodar o App mobile é preciso antes ter as depencias de sdk conforme o sistema Android ou IOS e na pasta mobile executar:
```bash
npx react-native start

# Android:
npx react-native run-android
# IOS:
npx react-native run-ios
```