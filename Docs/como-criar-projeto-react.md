# Como Criar um Projeto React

Este tutorial passo a passo mostra como criar um novo projeto React usando o Create React App.

## Pré-requisitos

Antes de começar, você precisa ter o Node.js e o npm instalados no seu computador. O Node.js 12.0.0 ou versões posteriores são necessários. Você pode verificar a instalação do Node.js e do npm com os seguintes comandos:

node -v
npm -v

markdown
Copy code

## Passo 1: Criar o Projeto React

Use o Create React App, uma ferramenta oficialmente suportada para criar projetos React com uma boa configuração padrão.

1. Abra o terminal.
2. Execute o seguinte comando para criar um novo projeto React chamado `meu-app`:

npx create-react-app meu-app

bash
Copy code

3. Aguarde a conclusão do processo de instalação.

## Passo 2: Iniciar o Projeto

Depois de criar o projeto, você pode iniciá-lo para ver o aplicativo React em ação.

1. Mude para o diretório do projeto:

cd meu-app

markdown
Copy code

2. Inicie o servidor de desenvolvimento:

npm start

markdown
Copy code

3. O comando acima abrirá automaticamente uma janela do navegador exibindo o aplicativo React. Se isso não acontecer, você pode acessar `http://localhost:3000` manualmente.

## Passo 3: Editar o Aplicativo

Agora que o seu aplicativo está rodando, você pode começar a editar o código.

1. Abra o diretório do projeto no seu editor de código de escolha.
2. Encontre e abra o arquivo `src/App.js`.
3. Faça alterações no arquivo, como modificar o texto dentro da função `App`.
4. Salve o arquivo e veja as alterações refletidas automaticamente no navegador.
