# O erro "Permission denied" (Permissão negada)

> ao tentar executar o comando `./gradlew clean` indica que o arquivo `gradlew` não tem permissão de execução no seu sistema. Isso é comum em sistemas baseados em Unix, como Linux e macOS, especialmente se o script foi criado em um ambiente Windows ou se as permissões de arquivo foram modificadas de alguma forma.

> Para resolver esse problema, você precisa adicionar permissões de execução ao arquivo `gradlew`. Você pode fazer isso usando o comando `chmod`. Aqui está como você pode fazer isso:

- 1. Abra o terminal.

- 2. Navegue até o diretório **android** do seu projeto React Native.

- 3. Execute o seguinte comando para adicionar a permissão de execução ao script **gradlew** :

`
chmod +x gradlew
`

> Esse comando modifica as permissões do arquivo `gradlew`, permitindo que ele seja executado como um script.

- 4. Após adicionar a permissão de execução, tente executar o comando `./gradlew clean` novamente:

`
./gradlew clean
`

> Isso deve permitir que o comando execute sem o erro de permissão. Se você ainda enfrentar problemas, certifique-se de que está executando o terminal com permissões adequadas. Se necessário, você pode usar `sudo` para executar o comando como superusuário, mas isso normalmente não é recomendado para operações de compilação como essa, porque pode introduzir problemas de permissão com os arquivos gerados:

`
sudo ./gradlew clean
`

- No entanto, tente primeiro sem `sudo`. Adicionar as permissões de execução com `chmod +x gradlew` geralmente resolve esse tipo de problema.