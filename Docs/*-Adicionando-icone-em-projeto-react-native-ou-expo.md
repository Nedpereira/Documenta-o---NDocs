# Adicionar Ícones em Projeto React Native CLI ou Expo
&nbsp;


### Site com todos os icones: 
https://oblador.github.io/react-native-vector-icons/

&nbsp;

## Instalação de Dependências

&nbsp;

Para adicionar ícones em seu projeto React Native, você precisará do pacote `react-native-vector-icons`. Siga os passos abaixo para instalá-lo.
&#8203;

```
npm install react-native-vector-icons --save
```

Este comando adicionará as dependências necessárias ao diretório node_modules do seu projeto.

Instalação CocoaPods para iOS (apenas CLI)
Após instalar o pacote, se estiver usando a React Native CLI, prossiga com a instalação dos CocoaPods no iOS.

```
cd ios && pod install && cd ..
```

## Importar o Pacote de Ícones

&nbsp;

Para Android (apenas CLI)
Crie o diretório `assets/fonts` na pasta `android/app/src/main`

Copie todos os arquivos de node_modules/react-native-vector-icons/Fonts para o diretório recém-criado.

## Para iOS (apenas CLI)
&nbsp;

Crie um diretório fonts na pasta ios do seu projeto.

Copie todos os arquivos de node_modules/react-native-vector-icons/Fonts para este diretório.

Abra o projeto no Xcode (MeuProjeto.xcworkspace).

Selecione Add Files to “MeuProjeto” e adicione o diretório fonts.

Verifique Create Folder references e clique em Add.

Adicione Fonts provided by application no Info.plist com os arquivos de fonte necessários.

&#8203;

## Usando Ícones no Expo

&nbsp;

Para projetos Expo, a adição de ícones é simplificada. Siga os passos abaixo:

```
expo install @expo/vector-icons
```

Este comando instalará o pacote necessário para usar ícones no Expo.
&#8203;

## Criando o Código

&nbsp;

Após a instalação das dependências, você pode começar a adicionar ícones ao seu arquivo App.js. Aqui está um exemplo de como usar o componente Icon do react-native-vector-icons:

```
import React from 'react';
import {SafeAreaView, StyleSheet, Text, View} from 'react-native';
import Icon from 'react-native-vector-icons/FontAwesome';

// Exemplo de ícone
<Icon name="users" size={60} color="#900" />
```

&#8203;

## Propriedades do Ícone

&nbsp;

size: Tamanho do ícone (padrão: 12)

name: Nome do ícone a ser mostrado

color: Cor do ícone (padrão: herdado)
&#8203;

## Criar um Botão com Ícone

&nbsp;
Você também pode criar botões com ícones:

```
<Icon.Button
  name="facebook"
  size={40}
  backgroundColor="#3b5998"
  onPress={() => alert('Login com Facebook')}>
    <Text style={{fontSize: 25, color: 'white'}}>
      Login com Facebook
    </Text>
</Icon.Button>
```
&#8203;

## Propriedades do Ícone.Botão
&nbsp;

color: Cor do texto e do ícone

size: Tamanho do ícone (padrão: 20)

iconStyle: Estilos aplicados apenas ao ícone

backgroundColor: Cor de fundo do botão (padrão: #007AFF)

borderRadius: Raio da borda do botão (padrão: 5)

onPress: Função chamada ao clicar no botão

&#8203;
