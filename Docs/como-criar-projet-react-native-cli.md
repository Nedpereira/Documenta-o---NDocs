# Guia de Início Rápido: React Native CLI

Este guia fornece instruções passo a passo para iniciar um novo projeto usando o React Native CLI.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- Node.js
- Watchman (para usuários de macOS)
- Java SE Development Kit (JDK)
- Android Studio e Android SDK
- Xcode (para usuários de macOS)

## Configurando o ambiente de desenvolvimento

Para configurar o ambiente de desenvolvimento do React Native, siga a documentação oficial:

[Configuração do Ambiente React Native](https://reactnative.dev/docs/environment-setup).

## Instalação do React Native CLI

Instale o React Native CLI globalmente usando o npm:

```bash
npm install -g react-native-cli
Criando um novo projeto
Para criar um novo projeto, execute:

bash
Copy code
react-native init NomeDoProjeto
Substitua NomeDoProjeto pelo nome desejado para o seu projeto.

Executando o projeto
Android
Para executar o projeto em um dispositivo ou emulador Android, navegue até a pasta do projeto e execute:

bash
Copy code
npx react-native run-android
iOS (apenas macOS)
Para executar o projeto em um dispositivo ou emulador iOS, primeiro instale as dependências do CocoaPods:

bash
Copy code
cd NomeDoProjeto/ios
pod install
cd ..
Em seguida, execute:

bash
Copy code
npx react-native run-ios
