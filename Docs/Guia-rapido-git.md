# Guia Rápido dos Comandos Git
> Este guia serve como uma folha de consulta rápida para os comandos mais comuns do Git utilizados no dia a dia do desenvolvimento de software.

**Configuração**

`git config --global user.name "Seu Nome"`
> Define o nome que será anexado aos seus commits e tags.
  
`git config --global user.email "seuemail@exemplo.com"`
> Define o email para ser associado aos seus commits.
   
**Iniciando um Projeto**

`git init [nome_projeto]`
> Inicializa um novo repositório Git local no diretório especificado.

`git clone [url]`
> Clona um repositório remoto para o seu local.

**Alterações e Staging**

`git status`
> Mostra o estado do diretório de trabalho e da área de staging.

`git add [arquivo]`
> Adiciona um arquivo à área de staging.

`git rm [arquivo]`
> Remove um arquivo do diretório de trabalho e da área de staging.

`git checkout -- [arquivo]`
> Descarta as alterações no diretório de trabalho para o arquivo especificado.

**Commit**

`git commit`
> Realiza um commit dos arquivos que estão na área de staging.

`git commit -m "mensagem"`
> Realiza um commit com uma mensagem de commit anexada.

**Branches**

`git branch`
> Lista todos os branches locais no repositório atual.

`git branch -a`
> Lista todos os branches, locais e remotos.

`git branch [nome_branch]`
> Cria um novo branch.

`git branch -d [nome_branch]`
> Exclui o branch especificado.

`git checkout [nome_branch]` 
> Muda para o branch especificado.

`git checkout -b [nome_branch]`
> Cria um novo branch e muda para ele.

**Atualização e Merge**

`git pull [remote]`
> Busca e faz merge de mudanças do repositório remoto para o branch local.

`git merge [nome_branch]`
> Faz merge de um outro branch no seu branch atual.

**Publicando Alterações**

`git push origin [remote]`
> Envia os commits locais para o repositório remoto.

`git fetch [remote]`
> Baixa objetos e refs de outro repositório.

**Desfazendo Alterações**

`git restore [arquivo]`
> Restaura os arquivos para o último estado do commit, desfazendo as alterações no diretório de trabalho.

`git reset [arquivo]`
> Remove o arquivo da área de staging e opcionalmente desfaz as mudanças no diretório de trabalho.

`git reset --hard`
> Reseta o índice e o diretório de trabalho para o último commit, eliminando todas as alterações.

`git revert [file]`
> Gera um novo commit que desfaz todas as mudanças introduzidas no commit especificado.
