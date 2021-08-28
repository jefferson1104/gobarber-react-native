<div align="center" style="margin-bottom: 20px;">
  <img alt="gobarber" src="./assets/images/goBarber-logo.svg" width="auto" heigth="auto"/>
</div>

<p align="center">
  <img alt="technology" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
</p>

## :barber: O projeto

Este projeto é uma versão mobile do projeto gobarber, seu código fonte foi desenvolvido com a tecnologia React Native para funcionar em dispositivos Android e IOS.
<p align="center">
  <img alt="gobarber" src="/assets/img/mobile-screenshot.png" width="200"/>
</p>

## :rocket: Principais tecnologias

- [TypeScript](https://www.typescriptlang.org/docs/)
- [React Native](https://reactnative.dev/)
- [Axios](https://github.com/axios/axios)
- [Styled-Components](https://styled-components.com/)

## :zap: Como executar este projeto
Para iniciar o aplicativo do **gobarber** na versão mobile (APP) também é necessário que o [Back-end (API)](https://github.com/jefferson1104/gobarber-nodejs) do projeto esteja iniciada e em execução, tambem certifique-se de ter um ambiente configurado para executar um emulador de smartphone em seu computador, em minha máquina eu utilizei um emulador android do proprio android estudio, o AVD (Android Virtual Device) utilize uma vm com no minímo android Pie 9 ou mais atualizado, e uma versao tambem com acesso a google play, no meu exemplo eu utilizei uma vm do **_Google Pixel 3a_**

Voce também pode utilizar o Expo, para isso saiba como configurar o expo em seu computador para emular ou até mesmo utilizar seu proprio smartphone.

<div align="center" style="margin-bottom: 20px;">
  <img alt="gobarber" src="/assets/img/screenshot_avd.png" width="auto" heigth="auto"/>
</div>

> **IMPORTANTE**: Caso você utilize o mesmo método que eu para executar a aplicação em um emulador do android studio, logo após iniciar o emulador é importante executar o comando `adb reverse tcp:3333 tcp:3333` no terminal para ter comunicação com o emulador e você conseguir instalar o app do goBarbar.

Para iniciar a versão mobile (APP) do projeto:

```Bash
# Acesse o diretório mobile
$ cd gobarber-react-native

# Instale todas as dependencias do projeto
$ yarn

# Considerando que seu emulador ja esteja iniciado e que voce ja tenha executado o comando de reverse, instale o aplicativo no emulador.
$ yarn android

# Iniciar app no emulador
$ yarn start
```


### :memo: Licença

Este projeto é desenvolvido sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para saber mais detalhes.
