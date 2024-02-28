# Guia de Início Rápido: React Native CLI
&nbsp;

Este guia fornece instruções passo a passo para iniciar um novo projeto usando o React Native CLI.

## Pré-requisitos
&nbsp;
Antes de começar, certifique-se de ter instalado:

- Node.js
- Watchman (para usuários de macOS)
- Java SE Development Kit (JDK)
- Android Studio e Android SDK
- Xcode (para usuários de macOS)

## Configurando o ambiente de desenvolvimento
&nbsp;

Para configurar o ambiente de desenvolvimento do React Native, siga a documentação oficial:

[Configuração do Ambiente React Native](https://reactnative.dev/docs/environment-setup).
&#8203;

## Instalação do React Native CLI

Instale o React Native CLI globalmente usando o npm:

```
npm install -g react-native-cli
```
> Criando um novo projeto
> Para criar um novo projeto, execute:

```
react-native init NomeDoProjeto
```
> Substitua NomeDoProjeto pelo nome desejado para o seu projeto.

Executando o projeto
Android
Para executar o projeto em um dispositivo ou emulador Android, navegue até a pasta do projeto e execute:

```
npx react-native run-android
```

iOS (apenas macOS)
Para executar o projeto em um dispositivo ou emulador iOS, primeiro instale as dependências do CocoaPods:

```
cd NomeDoProjeto/ios
pod install
cd ..
```

Em seguida, execute:

```
npx react-native run-ios
```
