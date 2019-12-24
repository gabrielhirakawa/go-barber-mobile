# GoBarber Mobile
Versão mobile do projeto GoBarber, desenvolvido em React Native. :iphone: :scissors:

### Executar o Projeto
Primeiro faça um clone desse repositório.(Necessário ter o projeto de backend rodando [GoBarber backend](https://github.com/gabrielhirakawa/go-barber-backend).)
```
git clone https://github.com/gabrielhirakawa/go-barber-mobile.git
ou
git clone git@github.com:gabrielhirakawa/go-barber-mobile.git
```

Dentro da pasta ***src/services*** encontre o arquivo ***api.js*** e altere o endereço de ip do backend para o ip da sua máquina.
```
const api = axios.create({
  baseURL: 'http://192.168.15.21:3333',
});
```

Com emulador aberto ou smartphone conectado, dentro da pasta raíz rode o código abaixo. (Necessário ter Node e Npm instalado)
```
react-native run-android
ou
react-native run-ios
```

